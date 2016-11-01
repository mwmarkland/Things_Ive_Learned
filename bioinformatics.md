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

