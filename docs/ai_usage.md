AI Use Log

Tool/model & version: Gemini 1.0 Pro

What I asked for: Guidance on a Python assignment about data types—examples for strings, integers, and floats—and a brief demo of using type() to inspect a variable’s type.

Prompt snippet:
“P4. Data types: use type() to find a variable’s type… TASK P4.1: Give an example of each data type so I can see the outputs.”

What I changed before committing:
Added print() statements and shown outputs for str, int, and float so the type() behavior is visible. Cleaned up formatting with Markdown for readability.

How I verified correctness:
Ran the snippets locally with sample values (x = "Hello, world!", y = 10, z = 3.14) and confirmed that type() returns the expected types and the outputs match the assignment requirements.

Rosalind Tasks Summary

Rosalind #1 (P6.2): Computed the sum of squares for two user-provided sides of a right triangle. Used input() to read values, float() to cast, and a**2 + b**2 for the calculation.

Rosalind #2 (P8.3): Performed string slicing. Read a string and four integers, then printed two inclusive slices using s[a:b+1] and s[c:d+1] (Python’s end index is exclusive).

Rosalind #3 (P12.3): Summed all odd numbers in a closed interval. Used range(a, b+1) with n % 2 == 1, implemented concisely via sum(n for n in ... if ...).

Rosalind #4 (P15.2): Worked with files and line numbers. Iterated over a text file with enumerate(..., start=1) and printed only even-numbered lines.

Rosalind #5 (P18.2): Counted word frequencies using dictionaries. Split the file contents with .split() and used collections.Counter to tally occurrences, then printed word count pairs.

Rosalind #6 (P19.1): Counted nucleotides in a DNA string using the built-in .count() for 'A', 'C', 'G', and 'T'.

Rosalind #7 (P21.1): Transcribed DNA to RNA with Biopython. Read DNA from a file, created a Seq object, and called .transcribe() to convert T → U.

Rosalind #8 (P21.2): Translated RNA to protein with Biopython. Used .translate(to_stop=True) on a Seq object to convert codons to amino acids and stop at the first stop codon.

Rosalind #9 (P23.2): Found the FASTA record with the highest GC content. Parsed records with Bio.SeqIO.parse, computed GC% via Bio.SeqUtils.gc_fraction, and tracked the max value and its ID.
