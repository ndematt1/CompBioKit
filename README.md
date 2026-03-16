# CompBioKit
CompBioKit is a Python toolkit that provides tools for analyzing DNA, RNA, and protein sequences.

It provides common functions used in the field of computational biology, such as transcription, translation, and sequence analysis functions.

### Currently in the Toolkit:
1. complement(dna_seq) // Returns the complementary DNA sequence
2. reverse_complement(dna_seq) // Returns the reverse complement of the DNA sequence
3. transcribe(dna_seq, coding_strand=True) // Transcribes the DNA sequence. If coding_strand = True, it assumes the DNA sequence is the coding strand. If coding_strand = False, it assumes the DNA sequence is the template strand.
4. transcribe_back(rna_seq, coding_strand=True) // Converts the RNA transcript into DNA. If coding_strand = True, it assumes the DNA sequence is the coding strand. If coding_strand = False, it assumes the DNA sequence is the template strand.
5. gc_content(dna_seq) // Calculates the GC content of the DNA sequence.
6. translate(rna_seq, one_letter=True) // Translates the RNA sequence. Returns one-letter amino acid abbreviations if one_letter = True, and three-letter abbreviations if one_letter = False.
7. translate_orfs(rna_seq, one_letter=False) // Finds all proteins encoded in an RNA sequence by identifying open reading frames (ORFs). Returns one-letter amino acid abbreviations if one_letter = True, and three-letter abbreviations if one_letter = False.
