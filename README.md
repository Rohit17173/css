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
## font properties

## box Margin properties
height
width
border=10px solid black;
border-top=0px;
border-width= 10px 2px 20px 30px
padding=20px;
margin=10px;

## cascading specificity inheritence
position
```
li{
color: red;
color:blue;
}
```
specificity
```
<li id="first-id" class="first-class" draggable>
li{color:"blue}
.first-class{color=:red"}
li[draggable]{color:"purple"}
#first-id{color:"orange"}
```
type
```
<link href="">
<style></style>
<h1 style:"color:red">
```
importance
```
color:red
color:red !important
