# Introduction
## What is Javascript.
Javascript is the one of the most important progaming language that used for web developers and it designed to integrated with HTML.
## Important Javascript method.
Today we will talk about an important method that could work along with HTML element 
called 'getElementId'
### What is getElementId.
'getElementId' is the method that is used for get HTML element from specify Id and you can make any change to that HTML element from this
### Change HTML content with JS.
You can change each Id section of HTML by get that element by Id
```
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>
        The usege of Javascript method along with HTML.
    </h2>
    <p id = "test">Hello Javascript</p>
    <button type ="button" onclick = 'document.getElementById("test").innerHTML = "Hello mister Joestar."'>Click_me</button>
</body>
</html>
```
The code above will change text 'Hello Javascript' to 'Hello mister Joestar' when you click button .
### Change HTML styes with JS.
In the same way as below you can change any style in each part of HTML by Id.
```
<button type ="button" onclick = 'document.getElementById("test").style.fontSize = "50px"' >click_this</button>
```
By click button element part that Id named is 'test' will change fontSize to 50px.
### Hide each part in HTML with JS.
```
<button type ="button" onclick = 'document.getElementById("test").style.display = "none"' >click_this</button>
```
When you click button the element that named 'test' will be hide.
### Show hidden part in HTML with JS.
```
<!DOCTYPE html>
<html lang="en">
<body>
    <h2>
        The usege of Javascript method along with HTML.
    </h2>
    <p id = "test">Hello Javascript.</p>
    <p id = "test2" style="display:none">Hello Kira Yoshikage.</p>
    <!-- Tutorial 1 JS can change HTML Attribute. -->
    <!-- One of the useful methods of JS is getElementById() 
    this method has been used forn getting HTML element by Id. -->
    <button type ="button" onclick = 'document.getElementById("test2").style.display = "block"' >click_this</button>
</body>
</html>
```
From code above at the beggining the element with id named 'test2' has been hidden then we will use onclick to show that element.
