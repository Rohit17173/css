# css
## inline 
```
<tag style="css" />
<html style="background:blue"
```
## internal
  ```
<style>css</style>
  <html>
    <head>
      <style>
        html{
          backkground:red;
          }
      </style>
    </head>
  </html>
  ```
## external
```
<link href="style.css>
style.css
html{
background:green;
}
```
## Selector
### class selector in style.css or internal stylesheet
```
.red-text{
  color: red;
}
```
```
<h1 class="red-text">red</h1>
```

### id selector in style.css or internal stylesheet
```
#green-text{
  color: green;
}

<h1 id="green-text">red</h1>
```
id can be applied to only once in html and class can be used for multiple element

### Attribute selector in style.css or internal stylesheet
```
<h1 draggable="true">drag me</h1>
<h1 draggable="false">dont drag me</h1>
<h1 draggable="false">dont drag me</h1>

p[draggable="false"]{
  color:red;
}
```
