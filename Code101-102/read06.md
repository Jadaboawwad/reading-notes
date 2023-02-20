# What is CSS? 
it's cascading style sheet allows us to style our html webpages and making it looks better or maybe awsome using a series of attributes and values.


# CSS Syntax:
in this example we colored h1 elemant and changed its size into 15px:

```CSS
  h1 {
  font-size:15px;
  color:red;
  }
  ```
  
  # How we add css to our website?

  * three ways can help us in adding css to websites:
    - External CSS: the css file is seprated form html file.

    ```html
    <!DOCTYPE html>
    <html>
    <head>
    <link rel="stylesheet" href="mystyle.css">
    </head>
    <body>

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

    </body>
    </html>
    ```

- Internal CSS: the css file is embaded with html file as an element.
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    <style>
    body {
      background-color: linen;
    }

    h1 {
      color: maroon;
      margin-left: 40px;
    }
    </style>
    </head>
    <body>

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

    </body>
    </html>
    ```

 - Inline CSS : the css code is embaded inside the elements it self.

    ```html
    <!DOCTYPE html>
    <html>
    <body>

    <h1 style="color:blue;text-align:center;">This is a heading</h1>
    <p style="color:red;">This is a paragraph.</p>

    </body>
    </html>
    ```


<hr>

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)
