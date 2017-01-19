# Your First Web Page
Now that you know the basics of HTML it is time to write an HTML document and get it up on the web!

## 1: Create an HTML document
In your `/341-work` directory, create a new child directory labeled `/week-03-hw`.

Within that directory create a new html document labeled `index.html`.
![Showing the creation of index.html in the terminal.app](imgs/addIndexHTML.png)

## 2: Open the file
Open the new file in your text editor. If you simply double-click the file, it will likely open in your default browser. Instead, you may need to drag it to the icon of your text editor app, or select “open file”

## 3: Create a Basic Document
Now that this blank index.html document is in front if you, we need to fill it.

### i. doctype declaration
Add the HTML5 doctype declaration on line 1.

```html
<!DOCTYPE html>
```

### ii.  Fill in the Basic Structure
Add the basic structure elements (`<html>`, `<head>`, & `<body>`), starting in line 2. Also include the uff-8 charset declaration and title elements in the head.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title></title>
    </head>
    <body>

    </body>
</html>
```

### iii. Add Some Content!
Finally, add a h1 element and 2 p elements. Populate these elements with your name, and the statement “Hello World!”, respectively.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title></title>
    </head>
    <body>
        <h1>Michael Musick</h1>
        <p>Hello World!</p>
    </body>
</html>
```

### iv. Open the File in a Browser
OK, time to view your first webpage! You have a view options to open this file
1. Double click the `index.html` file, as it should open in your default web-browser.
2. From terminal type `open index.html` (This should accomplish the same as above).
3. Drag the file to the browser you want it to open in.
4. Instal the "open-in-browser" package for Atom and then either press cntrl + opt + q (mac) or from the command palate type "Open in Browser".

You should now see your file open in a web browser, looking something like this.
![Example of the first web page](imgs/firstWebPage.png)

### v. Make Some Changes