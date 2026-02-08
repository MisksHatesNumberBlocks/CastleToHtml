<!-- I'm sorry, i didn't get a computer :( -->
![Logo](https://raw.githubusercontent.com/MisksHatesNumberBlocks/CastleToHtml/refs/heads/main/327%20Sem%20T%C3%ADtulo_20260207192421.png)
# CastleToHtml
A guide on how to port your castle.xyz game to html5.

---

# Basic HTML Stucture
First, add an html file with the following content: 
``` html
<!doctype html>
<html>
  <head>
    <style>
      body {
        background-color: black;
      }
    </style>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Any title</title>
  </head>
  <body>
    <canvas id="screen" width="280" height="400" style="
    border: 6px solid;
    border-radius: 25px;
    background-color: white;
    "></canvas> <!-- This will be for the main screen-->
    <img src="https://alinktoyourimage" width="50" style="display: none;"> <!-- This will be very important -->
    <script src="script.js">
  </body>
</html>
```
Then, go to the 2th part.
# Javascript Code
For the main `script.js` file, add the following content:
``` javascript
function wall() {
  // 'wall' can be any actor
  let position = [0,0] /* This will be the position */
}
```
