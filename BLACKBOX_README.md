 Assistant
## Project: ALICE

### Step 1: Create a folder for the project and initialize a new Git repository

```
mkdir alice
cd alice
git init
```

### Step 2: Create the HTML file

Create a file named `index.html` and add the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALICE</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Amatic+SC:wght@700&display=swap" rel="stylesheet">
</head>
<body>
    
<div class="flex-container">
    <h1>ALICE</h1>
</div>
<div id="btn">
    <a href="./2ndPage.html" class="myButton">Clica aqui!</a>
</div>

</body>
</html>
```

### Step 3: Create the CSS file

Create a file named `style.css` and add the following code:

```css
body {
  font-family: 'Amatic SC', cursive;
  margin: 0;
}

.flex-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

h1 {
  font-size: 100px;
}

#btn {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  text-align: center;
}

.myButton {
  display: inline-block;
  padding: 10px 20px;
  background-color: #000;
  color: #fff;
  text-decoration: none;
}
```

### Step 4: Create the second HTML

Generated by [BlackboxAI](https://www.useblackbox.ai)