# Javascript where to
In the first part we will talk about script tag
## The < script > tag
< script > tag will be used to inserted your javascipt code into HTML file
```
<!DOCTYPE html>
<body>
    <h1 id = "no1">Js is great!!!.</h1>
    <script lang="Javascript">
        document.getElementById("no1").innerHTML = "Js is the best."
    </script>
</body>
</html>
```
In lang argument in script tag, if you haven't specifed any progaming lang then HTML will set lang to JS by default (In lastest ver, JS is the default script lang in HTML.) 
## Javascript functions and events.
Javascript funtions is a block of code that will work when an event occurs such as when users click button, it similaries as event listeners.
## Javascript in < head > or < body >.
You can place your Javascript code in head or body part in HTML.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <script>
        function change_text() {
            document.getElementById("test1").innerHTML = "Java";
        }
    </script>
</head>
<body>
    
    <h2 id = "test1">Python</h2>
    <button onclick="change_text()">change</button>
</body>
</html>
```

