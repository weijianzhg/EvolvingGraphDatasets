# Evolving Graph Datasets

The data is stored in CSV format. The format files contains
three ordered sections:

1. *Header*. The first 15 characters must be `%%EvolvingGraph`. This
   is followed by the type of the evolving graph: either `directed` or
   `undireced`.

2. *Comments*. Zero or more lines of comments, each line starts with
   character `%`.

3. *Data*. The first line is the header of the data. The first three
   header names are `i` and `j` and `timestamp`. It follows by
   other attributes.








