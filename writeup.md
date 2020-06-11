# Introduction to HTML and CSS

## How web works

I have learned how a web works and about the client(front-end) and server(backend).

* Client(Front-end)
  * HTML
  * CSS
  * JavaScript
* Server(Backend)
  * Python
  * All other programming languages


 I got to know that HTML and CSS is not a programming language while JavaScript is a programming language. This assignment helps me to understand the concept of the HTML and CSS.


## HTML

 About HTML I have learned that why we should use `<!DOCTYPE html>` in the top of the HTML page. I have learn about the indentation how to write a code by indenting child elements. I got to know how to setting up a standard HTML document(DOCTYPE, HTML, head, body) and how to mark up the HTML file with elements, tags and attribute. Lets create a paragraph
  and heading with standard HTML document and also apply indentation :

  ```
  <!DOCTYPE html>
  <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Examples</title>
    </head>
    <body>
      <h1>THIS IS THE HEADING</h1>
      <p>THIS IS THE PARAGRAPH</p>
    </body>
  </html>
  ```



## CSS

 How can I target an element of HTML in CSS with selectors(type, class and id). What are the main things we have to use in CSS with selectors , properties and values.

```
<p>This is first paragraph</p>
<p class="para">This is second paragraph</p>
<p id="paragraph">This is third paragraph</p>

<!--to target all paragraph-->
p{
  background: red;
}

<!--to target second paragraph-->
.para {
  background: green;
}

<!--to target third paragraph-->
#paragraph {
  background: gray;
}
```

  I learned about the inline CSS , internal CSS and external CSS and how we reference them.

```
<!--inline css-->

<p style="background: green">This is a paragraph</p>
```
```
<!--inline css-->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Examples</title>
    <style>
      p {
        background: green;
      }
    </style>
  </head>
  <body>
    <p>This is a paragraph</p>
  </body>
</html>
```

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Examples</title>
    <link rel="stylesheet" href="main.css">
  </head>
  <body>
    <p>This is a paragraph</p>
  </body>
</html>


<!--This is main.css file-->
p {
  background: green;
}
```
