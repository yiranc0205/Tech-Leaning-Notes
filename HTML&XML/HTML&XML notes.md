## What is Element? 
An element is the section from (including) the start tag to (including) the end tag.  

```html
<p>This is a paragragh.</p>
```

## What is property of a element?   
Property of a element is the additional information of elements.  
  
```html
<a href="https://www.google.com">This is a link.</a> 
```
```xml
<file type="gif">computer.gif</file>
```

## What is the basic structure of HTML?   
+   **HEAD**: This contains the information about the HTML document. For Example, Title of the page, version of HTML, Meta Data etc.
+   **BODY**: This contains everything you want to display on the Web Page.  

```html
<! DOCTYPE html>
<html>

<head>
	<title>Page Title</title>
</head>

<body>
	<h2>Heading Content</h2>
	<p>Paragraph Content</p>
</body>

</html>
```

## Differences between HTML and XML?  
+ HTML is used to **display data**, focusing on **the appearance** of data.
+ XML is used to **transmit and store data**, focusing on **the content** of data.
+ HTML has **predefined tags** (like  `<p>`, `<h1>`) while XML doesn't. XML tags can be defined by its creator.

## What is the basic structure of XML?   
XML documents form a tree structure that starts at **the root (root element)** and branches to **the leave (child elements)**.  
```xml
<?xml version="1.0" encoding="UTF-8"?> 
<note> 
	<to>Tove</to> 
	<from>Jani</from> 
	<heading>Reminder</heading> 
	<body>Don't forget me this weekend!</body> 
</note>
```

## How to velidate an XML doc?
+ Use a **validator** to check the grammar. 
+ velidate the XML according to **DTD** in Internet Explorer.   
	<https://www.runoob.com/xml/xml-validator.html>