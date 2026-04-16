# Tool Learning Log

## Tool: **Materialize**

---

### 3/16/26:
* https://materializecss.com/
* https://youtu.be/gCZ3y6mQpW0?si=lglszeGlIHVGxA4B
* https://youtu.be/ZpduVPHZ5Aw?si=WEuVCMTk7d0Xs6Sc
* https://materializeweb.com/
* basic code setup:
  
```html
  <!DOCTYPE html>
  <html>
    <head>
      <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
      <title>Materialize sandbox</title>
    </head>
    <body>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    </body>
  </html>
```
* turn image into a circle shape
```html
  <img src=https://www.thepublicdiscourse.com/wp-content/uploads/2021/02/AdobeStock_57390451.jpeg" class= "responsive-img circle">
```
* text colors
```html
  <p class="red-text text-darken-4">This text is red darken.</p>
<div class="purple lighten-5">
    <span class="blue-text text-darken-2">This span has purple lighten text.</span>
</div>
```
* next loyo: explore colors
### 3/23/26:
* to apply background color (has lighten and darken class)
```html
<div class="card-panel teal lighten-2">This is a card panel with a teal lighten-2 class</div>
```
* to apply text color
```html
  <div class="card-panel">
    <span class="blue-text text-darken-2">This is a card panel with dark blue text</span>
  </div>
```
* using css for color change
```css
  .ilike-blue-container {
    @extend .blue, .lighten-4;
  }
```
* applying both of color background and text change
```html
  <!DOCTYPE html>
  <html>
    <head>
      <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
      <title>Materialize sandbox</title>
    </head>
    <body>
<div class="card-panel pink lighten-2 green-text text-lighten-2">This is a card panel with a teal lighten-2 class</div>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    </body>
  </html>
```
* can you use more than one hex color in the same class?
* shadow effect by adding a class="z-depth-2"
```html
   <div class="col s12 m2">
      <p class="z-depth-1">z-depth-1</p>
    </div>
    <div class="col s12 m2">
      <p class="z-depth-2">z-depth-2</p>
    </div>
    <div class="col s12 m2">
      <p class="z-depth-3">z-depth-3</p>
    </div>
    <div class="col s12 m2">
      <p class="z-depth-4">z-depth-4</p>
    </div>
    <div class="col s12 m2">
      <p class="z-depth-5">z-depth-5</p>
    </div>
```
* https://youtu.be/leZx_3l5_Iw?si=hn3Kk6YmQf-QyQCg 
* next yolo: collections component

### 3/30/26
* https://youtu.be/izCYfmJww-s?si=uHOFUsuLHDkQVPCW\
* https://youtu.be/4S1zHXVH7Dk?si=iS5qHbjaVe9d-ngA
* collection is a component allows for group to list objects together
* collection is a class
```html
    <!DOCTYPE html>
  <html>
    <head>
      <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
      <title>Materialize sandbox</title>
    </head>
    <body>
      <div class="collection">
        <a href="#!" class="collection-item">Mueller</a>
        <a href="#!" class="collection-item active">Muoller</a>
        <a href="#!" class="collection-item">Muller</a>
        <a href="#!" class="collection-item">Muellerr</a>
      </div>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    </body>
  </html>
```
* with-header with collections class to add header
```html

  <ul class="collection">
    <li class="collection-item avatar">
      <img src="images/yuna.jpg" alt="" class="circle">
      <span class="title">Title</span>
      <p>First Line <br>
         Second Line
      </p>
      <a href="#!" class="secondary-content"><i class="material-icons">grade</i></a>
    </li>
    <li class="collection-item avatar">
      <i class="material-icons circle">folder</i>
      <span class="title">Title</span>
      <p>First Line <br>
         Second Line
      </p>
      <a href="#!" class="secondary-content"><i class="material-icons">grade</i></a>
    </li>
    <li class="collection-item avatar">
      <i class="material-icons circle green">insert_chart</i>
      <span class="title">Title</span>
      <p>First Line <br>
         Second Line
      </p>
      <a href="#!" class="secondary-content"><i class="material-icons">grade</i></a>
    </li>
    <li class="collection-item avatar">
      <i class="material-icons circle red">play_arrow</i>
      <span class="title">Title</span>
      <p>First Line <br>
         Second Line
      </p>
      <a href="#!" class="secondary-content"><i class="material-icons">grade</i></a>
    </li>
  </ul>
```
* you can put collections classes within collections classes!!
* animated (indeterminate) preloader
```html
 <div class="progress">
      <div class="indeterminate"></div>
  </div>
```
* Next yolo: explore more of the preloader in materialize

### 4/15/2026
* Day 1: Explore the CSS component of transitions that materialize has to offer to use in my freedom project to have a smoother transition and add animation. Testing it out by watching youtube tutorials and work it in JSbin.
* Day 2: Learn about cards in materialize to make it easier for me to organize small ideas in my freedom project using those cards. Use the tutorial and explanation from materialize.
* Day 3: Learn icons in materialize to showcase the different websites and their icon that was researched about and can reference to in the freedom project. Using youtube to help me navigate.

* scale transition:
```css

  <!-- Scaled in -->
  <a id="scale-demo" href="#!" class="btn-floating btn-large scale-transition">
    <i class="material-icons">add</i>
  </a>

  <!-- Scaled out -->
  <a id="scale-demo" href="#!" class="btn-floating btn-large scale-transition scale-out">
    <i class="material-icons">add</i>
  </a>
```
* button fades in and out 

### 4/16/2026
* simple card example with links
```css
  <div class="row">
    <div class="col s12 m6">
      <div class="card blue-grey darken-1">
        <div class="card-content white-text">
          <span class="card-title">Card Title</span>
          <p>I am a very simple card. I am good at containing small bits of information.
          I am convenient because I require little markup to use effectively.</p>
        </div>
        <div class="card-action">
          <a href="#">This is a link</a>
          <a href="#">This is a link</a>
        </div>
      </div>
    </div>
  </div>
```

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
