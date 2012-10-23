# Markdown Syntax

Markdown is a markup language that uses simple syntax and can be compiled into html. Let's
look at some examples of markdown syntax.

**********

# Headings
##Heading Sizes:
Headings come in 6 different sizes. The six sizes are denoted h1 - h6, with the largest
being an h1, and the smallest an h6. Below are examples of each heading size:

# Heading 1 / h1

## Heading 2 / h2

### Heading 3 / h3

#### Heading 4 / h4

##### Heading 5 / h5

###### Heading 6 / h6  ######
...

## Heading Syntaxes:
There are 2 different ways to make headings in Markdown.
The first method is by using a `#` (pound sign) before the text of the 
header. The number of `#` characters that you use denotes the level of 
the header tag. So, `#` translates to `<h1>`, `##` translates to 
`<h2>` and so on, up to `<h6>`. You may enclose the header by the same 
number of `#` signs. This is not required, but it does make your plain 
text easier to read. Below are some code examples of Atx-style headings.

    #Heading 1
    ## Heading 2 ##
`### Heading 3`
  
The second method is by 'underlining' the text of the header with `-` 
(minus sign) or `=` (equal sign) characters. These are called setext style headers. The `=` translates to 
h1, while `-` translates to h2. In this syntax, h3 - h6 lever header tags are 
not supported. Below are some examples of code that produces setext-style headings:

    Heading 1
    ==========

    Heading 2
   `-`

(You don't have to underline the whole heading, but it makes your code more readable).

**********

# Emphasis

Markdown uses `*` (asterisk) and `_` (underscore) characters as 
indicators of emphasis. Enclose the emphasized text with one character 
for italic text (HTML `<em>` tags), two characters for bold text (HTML 
`<strong>` tags), and three characters for text that is both 
italicized and bold. For example:

    *Italic Text*
    or
    _Italic Text_
Produces: *Italic Text*

    **Bold Text**
Produces: **Bold Text**

    ___Bold & Italic Text___
Produces: ___Bold & Italic Text___

**********

# Lists

Markdown supports both unordered and ordered lists. 

Unordered lists are displayed as bulleted lists. Markdown uses `*`, `-`, or 
`+` to define a list. This is an unordered list:  

    * Apples
    * Bananas
`* Oranges`

Produces:

* Apples
* Bananas
* Oranges

Ordered lists are numbered lists. To start a list, you just have to begin with a number 
followed by a period, and Markdown will number the list correctly for you.
For example:

    1. Apples
    2. Oranges
    3. Bananas

and

    4. Apples
    5. Oranges
 `8. Bananas`

Both Produce:

1. Apples
2. Oranges
3. Bananas

**********

# Links

Link Text - The text that will appear on the HTML page.
url - The url of the link.
Title - The text that will appear when the user hovers over the link. 
        This is an optional parameter. It is equivalent to the `title` 
        attribute of an HTML link.

Let's look at an example:

[Visit my site](http://example.com "Visit example.com")

**********
