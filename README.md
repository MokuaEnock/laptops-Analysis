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

## HTML structure.

Below is a basic structure of HTML documents.

<pre>
    <code>

        <!DOCTYPE html>
        <html>
        <head>
            <meta charset="utf-8" />
            <title>HTML Structure</title>
        </head>
        <body>
            <h1>This is a heading.</h1>
            <p>This is a paragraph.</p>
            <span>This is a span.</span>s
            <span>So is this.</span>
            <img src="image.jpg" alt="a picture" />
        </body>
        </html>
    </code>
 </pre>

HTML elements follow a similar structure.
`<tag> I am a tag.</tag>`

#### Elements Can Go Inside Other Elements.

We can create a tree structure in HTML by putting elements inside other elements. To do this we often use a `<div>` element as a container. `<div>` elements are used to group chunks of content together.

## HTML data.

HTML files are text files that can be opened and inspected in text editors which means you can write your code to parse the text. There's some confusing code at the top of the file, but the actual text content of the web page is easy to read, e.g.

> Title
> Critic scores
> Audience scores

For example, to get our audience score metrics, we could find all instances of the `span` tag using Python tools like `str.find` or regular expressions, to search for and extract patterns in text. But we have a better tool!

## Beautiful soup

Beautiful Soup is an HTML parser written in the Python programming language. The name is derived from the "tag soup" which refers to the unstructured and difficult-to-parse HTML found on many websites.

## Using Beautiful Soup

#### 1. Import beautiful soup
To get started we import the soup.
#### 2. Make the soup.
We pass the HTML file into a filehandle, then pass that filehandle into the Beautiful Soup constructor along with a parser.

#### 3. use the find method
`find()` is one of the most popular Beautiful Soup methods. It is similar to the find feature in a text editor.

## References

Pandas flat file - https://pandas.pydata.org/pandas-docs/stable/reference/io.html#flat-file

Beautiful soup - https://www.crummy.com/software/BeautifulSoup/
