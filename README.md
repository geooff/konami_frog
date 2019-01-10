# konami_frog
JS/HTML block of hidden gif activated by Konami code (Up, Up, Down, Down, Left, Right, Left, Right, B, A, Enter)

## To run: 
Open meme.html with any modern browser

## To add to your project:
Copy and paste the contents of meme.html into your project

## To edit:
Within the ```.datboy``` css style change the content referenced by the content field, along with this the dimensions referenced in the width and height fields
```javascript
.datboy { 
  content:url("<Your Link Here>"); 
  position:fixed; 
  width: <Your Images Width Here>; 
  height: <Your Images Height Here>; 
  left:50%; 
  bottom:30px; 
  background-position:0px -178px; 
  z-index:1000; 
  visibility: hidden;
} 
```
