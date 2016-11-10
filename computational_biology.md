# Mate Pair (Paired End Tags)
[Wikipedia](https://en.wikipedia.org/wiki/Paired-end_tag)

"Paired-End diTags" or "ditags"

short sequences at the 5' and 3' ends of a fragment of DNA which are
unique enough that they (theoretically) exist together only once in a
genome, therefore making the sequence of the DNA in between them
available upon search (if full-genome sequence data is available).

PET libraries have the PETs with intervening DNA absent.

A PET "represents" a larger fragment of genomic of cDNA by consisting
of a short 5' linker sequence, a short 5' sequence tag, a short 3'
sequence tag, and a short 3' linker sequence.

# Homology

The existance of shared ancestry between a pair of structures. In
bioinformatics, often protiens or DNA sequences. Two segments of DNA
can have shared ancestry because of either a speciation event
(orthologs) or a duplication event (paralogs). Homology is inferred
from their sequence similarity. Alignments of multiple sequences are
used to indicate which regions of each sequence are homologous.

# Dealing with sequence repeats
From the **BLAST** Wikipedia page

**low-complexity-region**: A region of a sequence comprised of a few
kinds of elements. These can trigger high scores that mask actual high
significance sequnces, so they are filtered out. Regions are marked
with an **N** in nucleic acid sequences or an **X** in protein
sequences. Other programs can filter these out.

So I took a look at `Genome/hg19-GRCh37` and `chr1.fa`. The first few
hundred lines in that file are all **N**, and there are long sequences
of **N** within the whole thing separated byt actual nucleic acid
sequences.

# More general hacked notes.

**Read**:  A segment of nucleotides. Could be viewed as a sequence of nucleotides, but sequence is overloaded in this space.

## Alignment

Discovering how and where a segment of nucleotides (read) or full on
sequences are similar to some reference sequence. Identifies and
quantifies similarity.

**Global alignment**:  the search involves all nucleotides in the read. Normal and pathological reads are aligned to a reference genome.

**Local alignment**:  some of the nucleotides don't participate in the alignment.

Examples:

Global
Read:          GACTGGGCGATCTCGACTTCG
Reference:     GACTGCGATCTCGACATCG

Alignment:
Read:          GACTGGGCGATCTCGACTTCG
Reference:     GACTG--CGATCTCGACATCG

Local
Read:          ACGGTTGCGTTAATCCGCCACG
Reference:     TAACTTGCGTTAAATCCGCCTGG

Read:          ACGGTTGCGTTAA-TCCGCCACG
                   ||||||||| ||||||
Reference:     TAACTTGCGTTAAATCCGCCTGG

## Three forms of changes:

- Substitutions:  ACGA => AGGA
- Insertions:     ACGA => ACCGGAGA
- Deletions:      ACGGAGA => AGA

## How do you align sequences?

### Alignment Scoring

Score is used to give a measure to the degree of similarity between a given read and some reference sequence.

Different aligners have different scoring schemes.

Example

Sequence 1 = AGTCA, Sequence 2 = CGTTGG

Scoring matrix:

----------------------------------------
|   |    A |    G |    T |    C |    - |
----------------------------------------
| A |    1 | -0.8 | -0.2 | -2.3 | -0.6 |
| G | -0.8 |    1 | -1.1 | -0.7 | -1.5 |
| T | -0.2 | -1.1 |    1 | -0.5 | -0.9 |
| C | -2.3 | .0.7 | -0.5 |    1 |   -1 |
| - | -0.6 | -1.5 | -0.9 |   -1 |  n/a |
----------------------------------------

Selected alignment:

A-GTC-A
-CGTTGG

Score = -0.6-1+1+1-0.5-1.5-0.8 = - 2.4

# Interesting Links
[Evolutionary Biology/Computers](http://biology.stackexchange.com/questions/14168/book-recommendations-for-algorithms-used-in-evolutionary-biology/14191#14191)
