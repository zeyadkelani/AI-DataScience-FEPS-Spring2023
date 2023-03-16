
# Components of a Web Page
<br/>
When you visit a webpage, the browser you are using makes a request to a web server. This request is called a GET request, based on the logic that we are getting files from the server. Then, the server sends the files back and tell the browser to render the page for us. Usually, a web pgae files falls into the following types:

<br/>

`HTML` — contain the main content of the page.<br/>
`CSS` — add styling to make the page look nicer.<br/>
`JS` — Javascript files add interactivity to web pages.<br/>
`Images` — image formats, such as JPG and PNG allow web pages to show pictures.

<br/>
Once the browser recieves all the files, it renders the page and displays it to us. For this process to happen, there are many interrelated processes functioning in the backend. For our purposes, we are interested in contents of a web page.

<br/>

### HTML

HyperText Markup Language (HTML) is a language that web pages are created in. HTML is a markup language that basically sets the layout for a webpage and tells the browser how to render it. Think of HTML as a word processor like Microsoft Word; that allows you to make text bold, create new lines, insert pictures and so on. Still, HTML can be very complicated markup language.
<br/>
HTML consists of elements called tags, the most basic tag is `<html>` tag. This tag tells tells the web browser that everything is inside it belongs to HTML markup language. The most simple HTML document can be done using this basic tag:


```
<html>
</html>
```
The document above would render a blank HTML page.

```

```

<br/>

We can add more tags under a html tag, to indicate a heading `<html>` that includes data about the title of the page and body `<body>` to include the main content of the web page.

```
<html>
<head>
</head>
<body>
</body>
</html>
```
This HTML document would also render:

```

```
We can use the `<p>` tag that defines a paragraph and any text inside it is shown as a separate paragrah, consdier the following example:

```
<html>
<head>
</head>
<body>
<p>
Here's a paragraph of text!
</p>
<p>
Here's a second paragraph of text!
</p>
</body>
</html>
```
This would yield the following HTML page:

```
Here's a paragraph of text!

Here's a second paragraph of text!

```
Tages are typically named based on their position in relation to other tags, for instance:

- child — a child is a tag inside another tag. So the two p tags above are both children of the body tag.
- parent — a parent is the tag another tag is inside. Above, the html tag is the parent of the body tag.
- sibiling — a sibiling is a tag that is nested inside the same parent as another tag. For example, head and body are siblings, since they’re both inside html. Both p tags are siblings, since they’re both inside body.

<br/>

Consider the following example:

```
<html>
<head>
</head>
<body>
<p>
Here's a paragraph of text!
<a href="https://www.dataquest.io">Learn Data Science Online</a>
</p>
<p>
Here's a second paragraph of text!
<a href="https://www.python.org">Python</a> </p>
</body></html>
```
It would yield the following:

```
Here’s a paragraph of text! Learn Data Science Online

Here’s a second paragraph of text! Python
```
In the above example, we added two more tags, that are links. The `href` property of the tag determines where the link goes. `a` and `p` are extremely common html tags. Other types of tags include:
<br/>
`div` — indicates a division, or area, of the page.<br/>
`b` — bolds any text inside.<br/>
`i` — italicizes any text inside.<br/>
`table` — creates a table.<br/>
`form` — creates an input form.

<br/>
For a comeplete list of tags:

[Click Here](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
