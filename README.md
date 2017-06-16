# Div inside div horizontally center

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
