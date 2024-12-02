# Web Design

## Intro to HTML 1
Introduction to HTML
HTML (HyperText Markup Language) is a markup language used to define the structure of and to display the content of a web page. It essentially defines the content the browser should display. It is made up of elements which define what the content is (i.e. the meaning of the content). For example, everything within the <body> element is the body of the page.

Each HTML element is formed with one or more tags with each tag enclosed within angle brackets (in the example above, "<body>"). Most tags need to be closed and will have a corresponding closing tag denoted by a slash (e.g. "</body>"). Elements should be properly nested or strange errors or behaviors can occur.

### Example:
<body>
<p>This is a paragraph. <strong>This is bolded text while <em>this
is bolded and italicized.</em></strong></p>
</body>

The above HTML is only the body portion of an HTML page. It defines that within the body of the page, there is a paragraph, denoted by the <p> tag. The text of the paragraph is within the <p> tags. Note the slashes in the closing tags. Two other tags are present: <strong> and <em>. The <strong> text is used to bold the text while <em> is used to italicize or emphasize the text. In this case, because the <em> tag is within the <strong> element, the words within the <em> tags are both bolded and italicized. Note that because the <strong> tag was opened first the <em> tag must be closed before the strong tag. This is what is meant by proper nesting. The closing </em> tag cannot be placed after </strong>

