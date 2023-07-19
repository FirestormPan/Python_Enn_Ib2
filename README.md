# Python_Enn_Ib2
Data Editing and Reduction with Enn and IB2 after normalization

1. Assume that the training datasets are csv files comprised of numerical attributes only with the
exception of the class attribute. You can also assume that the class attribute is the last attribute
of the file.
2. Implement program NormalizeValues that takes as input a csv file and normalizes the values of
all its attributes (i.e., transforms them in the [0, 1] range). Obviously, the class attribute should
be excluded. The normalized file should be written to disk.
3. Implement program ENN that takes as input a normalized csv file and applies the editing
algorithm ENN on it. The edited file should be written to disk.
4. Implement program IB2 that takes as input a normalized csv file and applies the instance
reduction algorithm IB2 on it. The reduced file should be written to disk.

The program can be tested with the iris or leter-recognition datasets provided
