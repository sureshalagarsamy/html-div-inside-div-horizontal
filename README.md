# Div inside div horizontally center

# Example-1

### HTML

```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Div inside div center</title>
<link rel="Stylesheet" type="text/css" href="style.css">
</head>

<body>
  <div class="parent">
    <div class="child">test</div>
  </div>
</body>

</html>
```

### CSS

```css
.parent {
  width : 200px;
  height: 200px;
  border: 1px solid #DDD;
}

.child {
  width : 50px;
  height: 50px;
  border: 1px solid #DDD;
  margin: 0 auto;
  text-align:center;
  background-color: #F6F6F6;
}
```


### Output

![ScreenShot](https://user-images.githubusercontent.com/6780840/27214759-adbc5006-528b-11e7-91d6-4bac8c8c8440.png)


# Example-2

### HTML

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Div inside div center</title>
</head>
<body>
  <div class="flex-container">
    <div class="item">item 1</div>
  </div>
</body>
</html>
```

### CSS

```css
.flex-container {
    display: -webkit-flex;
    display: flex;
    -webkit-justify-content: center;
    justify-content: center;
    width: 200px;
    height: 100px;
    background-color: #F6F6F6;
    border: 1px solid #BBB;
    border-radius: 6px;
    box-shadow: 0 0 9px #BBB;
}

.item {
    background-color: #DDD;
    text-align:center;
    width: 50px;
    height: 50px;
    margin: 10px;
    border-radius: 3px;
    border: 1px solid #BBB;
}
```


### Output

![ScreenShot](https://user-images.githubusercontent.com/6780840/27222938-fc0f786c-52ab-11e7-852a-cf7125180c06.png)

### Note

These 2 properties only used make inner div as center.. other properties will be used for cosmetic effects only.

```
display: flex;
justify-content: center;
```

