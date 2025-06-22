

HTML (HyperText Markup Language)

What is HTML?

HTML is the structure of a webpage — it defines the content and layout using tags.

Basic Concepts

HTML uses tags enclosed in < > to mark up elements.

Elements have an opening tag <tag> and a closing tag </tag>.

Common tags:

<h1> to <h6> — headings

<p> — paragraph

<a> — hyperlink

<img> — image

<div> — division/container

<ul>, <ol>, <li> — lists



Simple Example

<!DOCTYPE html>
<html>
<head>
  <title>My First Webpage</title>
</head>
<body>
  <h1>Welcome to HTML!</h1>
  <p>This is a paragraph of text.</p>
  <a href="https://www.example.com">Visit Example</a>
</body>
</html>


---

CSS (Cascading Style Sheets)

What is CSS?

CSS controls the appearance of HTML elements — colors, fonts, layout, spacing, and more.

How to Use CSS?

Inline: directly inside an HTML tag

Internal: inside a <style> tag in the <head>

External: in a separate .css file linked to HTML


Basic CSS Syntax

selector {
  property: value;
}

Example:

body {
  background-color: lightblue;
}

h1 {
  color: navy;
  font-family: Arial, sans-serif;
}

p {
  font-size: 16px;
  color: #333333;
}


---

Putting HTML and CSS Together

<!DOCTYPE html>
<html>
<head>
  <title>Styled Page</title>
  <style>
    body {
      background-color: #f0f0f0;
      font-family: Verdana, sans-serif;
    }
    h1 {
      color: darkgreen;
    }
    p {
      color: #555555;
      font-size: 18


