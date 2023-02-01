# Hotel Website

You can run the website at : [https://inspiring-boba-f175ff.netlify.app/](https://inspiring-boba-f175ff.netlify.app/)

I used the Netlify to deploy the website and their service to handle the forms submissions. 

In this project I used HTML5 and CSS to create a hotel website.

In this whole project I didn’t work with the modern CSS (flexbox and grid) I used float to get the blocks in-line :

```css
.box {
  float: left;
  width: 33.333%; /*the 33.3 because I have 3 blocks*/
  padding: 50px;
  text-align: center;
}
```

I reset the margin and padding to 0 and the box-sizing to border-box in order to not add the default margin and padding to the width when I float the boxes:

```css
/* Reset */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
```

I used a script form [https://fontawesome.com/](https://fontawesome.com/) to get the icons used in this project : 

```html
<script src="https://kit.fontawesome.com/40cf33b90c.js" crossorigin="anonymous"></script>
```

```html
<i class="fa-solid fa-hotel fa-3x"></i>
```

You can find all images used in the folder img 

and the stylesheets in css folder

I used media queries to get the website responsive in the mobile devices, you can find the stylesheet in css folder :

```html
<link rel="stylesheet" media="screen and (max-width: 768px)" href="/css/mobile.css">
```
