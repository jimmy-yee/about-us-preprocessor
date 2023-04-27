# How to run?
### 1. Install the Node.js for the basic environment
<https://nodejs.org/en>  
### 2. Install the Pug html preprocessor in VS Code by command 
```
npm install -g pug-cli
```
### 3. Install the SASS CSS preprocessor in VS Code by command
```
npm install -g sass
```
### 4. Use the command to compile the .html from .pug
```
pug -w about-us.pug -o ./html -P
```
### 5. Use the command to compile the .css from .sass
```
sass --watch about-us.sass:css/about-us.css
```
### 6. The .html and .css files are ready to run in the browser
[百岳人才圖鑑](https://jimmy-yee.github.io/about-us-preprocessor/html/about-us.html)