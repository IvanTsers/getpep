# [`getpep`](https://owncloud.gwdg.de/index.php/s/um4GqoSNq1Qy7c3): find peptides or proteins by their CDS sequences

Given a `fasta` of a reference proteome as a subject and a nucleotide
`fasta` as a query, find protein or peptide sequences that match the
query nucleotides.

## Installation

Assuming that you have
[`blast+`](https://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/) and
[`Go`](https://go.dev/doc/install), and git installed:

```sh
git clone https://github.com/ivantsers/getpep
cd getpep
make
```

This will compile the executable `getpep`.

Basic usage:

```sh
getpep -q dna.fasta -s protein.fasta
```