## Introduction to flat files.

Flat files contain tabular data in plain text format with one data record per line and each record or line having one or more fields. These fields are separated by delimiters, like commas, tabs, or colons.

#### Advantages of flat files

They're text files and therefore human readable
Lightweight
Simple to understand
Software that can read/write text files is ubiquitous, like text editors
Great for small dataset

#### Disadvantages of flat files, in comparison to relational databases

Lack of standards.
Data redundancy
Sharing data can be cumbersome.
Not great for large datasets

## Using Python for Flat Files

Because flat files are human readable, you can easily write your own code to parse or understand these files using Python:

> Open the file
> Read the text line by line
> Separate each line's content by the delimiter
> Store everything in your data structure of choice.
## References

Pandas flat file - https://pandas.pydata.org/pandas-docs/stable/reference/io.html#flat-file
