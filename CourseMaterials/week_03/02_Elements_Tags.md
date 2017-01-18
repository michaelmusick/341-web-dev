# Elements & Tags in HTML

**HTML** (_Hypyertext Markup Language_) is a language that describes the structure of a document intended for viewing through a browser.
The browser's processor identifies _elements_ of the document by looking for _tags_ embedded directly in the text.
These elements are then parsed into the _Document Object Model_ (DOM).

An HTML document is composed of a tree of HTML elements. An **element** is an individual component of an HTML document. Elements denote to the processor structure and semantic meaning of the document. Elements may also be nested or encapsulated within other elements.

Elements are identified in a document through tags. A **tag** is code that is syntactically unique from the text content of the document. In HTML, all tags include a less than and greater than sign, with the tag typed between.
```html
<html>
```

Most elements include an "opening" and "closing" tag that the processor uses to identify the begining and end of the element with. Closing tags are identical to opening tags, except that they contain a forward-slash between the less than sign and the tag text.
```html
<html>
</html>
```

### Main Document Elements
`<!DOCTYPE>`
The document type element is the first element in an HTML document, and should be places on the first line in a document. This element tells the browser's processor what type of HTML document it is.


`<html>...</html>`
The _Root element_ of an HTML document contains all other elements and text.

`<head>...</head>`
The _head_ element is a container for processing information and document metadata. This will include elements that may link to other files, hold the author information, and pass the name of the page to the processor.

`<body>...</body>`
The _body_ element is a container for all of the content and data that is intended to be displayed in a browser as a page.

These elements will always be nested as follows for an HTML document:
```html
<!DOCTYPE html>
<html>
	<head>
	</head>

	<body>
	</body>
</html>
```
