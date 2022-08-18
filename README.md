# hmmer_to_gff

This script is designed to transform hmmer tbl output (tabular with 16 columns) into a gff file, along with some filters.

## Syntax

hmmer_tbl_to_gff.py --file [FILE] --source [SOURCE] --bitscore [BITSCORE]

## Options

| Options | Description |
| --- | --- |
| file | The input file produced by hmmer with output format 6 (tabular). |
| source | The mode in which hmmer was performed, e.g. hmmer, nhmmerscan, ... |
| bitscore | Bitscore obtained by hmmer. Used to add a level of filter to the result. If 0, all results will be maintained. |
