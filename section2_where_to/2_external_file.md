# External file.
In ordinary, you have wrote your JS in your own HTML file so what you want to write your own JS code to js file?. So 'external file' is the solution for that.
## What is external file.
external file means the file you have imported from other files to your own HTML code (external file also knowed as '.js' file), external file will be used when various HTML files or HTML webs uses the same Javascript code, in that case we will done by import external file to required HTML files (Its similaries that you have main.py(could compared to HTML file) file but you have your own module(external .js files) then you have imported that module into main.py)
## Using external JS script in HTML.
This methods can be done by put script file location in src attribute in script tag.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <script>
        function change_text() {
            document.getElementById("test1").innerHTML = "Java";
        }
    </script>
    <script src="test.js"></script>
</head>
<body>
    
    <h2 id = "test1">Python</h2>
    <button onclick="change_text()">change_text</button>
    <button onclick="change_size()">change_size</button>
</body>
</html>
```
## Advantages of external Javascript. 
The obviously advantage of external file is that HTML and JS will be seperated from each other, which means you can read or maintain your code easier.
## External reference.
You can reference your external JS in 3 different ways:
### 1. Reference from full URL.

