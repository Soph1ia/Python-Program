# Understanding HTML & CSS  

## HTML (Hypertext Markup Language)
HTML is the language used to create web pages. Here's a basic tutorial to get you started:

### Create a new file with a .html extension: 
Open up a text editor (such as Notepad on Windows or TextEdit on Mac) and create a new file with a .html extension.

### Add the basic HTML structure: 
Start your HTML document with the following code:

``` html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>

```

This code defines the basic structure of an HTML document, including the <!DOCTYPE html> declaration, the opening and closing html tags, the head section, and the body section.

### Add content to your HTML document: 
You can add content to your HTML document by adding tags within the body section. For example, to add a heading to your document, use the h1 tag. 

```` html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	<h1>Hello, world!</h1>
</body>
</html>

```` 

This will display the text "Hello, world!" as a large heading on your web page.

## CSS (Cascading Style Sheets)
CSS is used to style HTML documents. Here's a basic tutorial to get you started:

### Create a new file with a .css extension: 
Create a new file in the same directory as your HTML file, but with a .css extension.

### Link your CSS file to your HTML document: 
In your HTML document, add the following code to the head section:

```` html
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
	<h1>Hello, world!</h1>
</body>
</html>

````

This code links your CSS file to your HTML document using the <link> tag.

### Add styles to your CSS file: 
In your CSS file, you can add styles to elements in your HTML document using selectors. For example, to change the color of the text in your heading to red, use the following code:

```` css
h1 {
	color: red;
}

````

This will change the color of the text in your heading to red.