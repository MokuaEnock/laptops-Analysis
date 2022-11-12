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

Because flat files are human readable, you can easily write your code to parse or understand these files using Python:

> Open the file
> Read the text line by line
> Separate each line's content by the delimiter
> Store everything in your data structure of choice.

## How Does Web Scraping Work?

Website data is written in HTML (HyperText Markup Language) which uses tags to structure the page. Because HTML and its tags are just text, the text can be accessed using parsers. We'll be using a Python parser called Beautiful Soup.

## Accessing the HTML

#### Manual Access

The quick way to get HTML data is by saving the HTML file to your computer manually. You can do this by clicking Save in your browser.

#### Programmatic Access

Programmatic access is preferred for scalability and reproducibility. It includes two these are:
1. Downloading HTML files programmatically.
2. Working with the response content live in your computer's memory using the BeautifulSoup HTML parser

## References

Pandas flat file - https://pandas.pydata.org/pandas-docs/stable/reference/io.html#flat-file

Beautiful soup - https://www.crummy.com/software/BeautifulSoup/
