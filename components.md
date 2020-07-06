# Components
## Navigation
```html
<nav class="navbar navbar-dark navbar-expand-sm bg-primary fixed-top">
    <div class="container">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#Navbar">
            <span class="navbar-toggler-icon"></span>
        </button>
        <a class="navbar-brand mr-auto" href="#">Ristorante con Fusion</a>
        <div class="collapse navbar-collapse" id="Navbar">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active"><a class="nav-link" href="#">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="./aboutus.html">About</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Menu</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
            </ul>
        </div>
    </div>
</nav>
```
1. Collapse on small size screen
```html
<nav class="navbar navbar-expand-sm">
```

2. Fix navigation bar on the top when scrolling
```html
<nav class="navbar fixed-top">
`
3. Display the logo/name of the website
```html
<a class="navbar-brand" href="#">
```
4. Push item in the navigation bar to the left
```html
<ul class="navbar-nav mr-auto">
```
5. Display items (pages) horizontally
```html
<li class="nav-item">
```
6. Highlight specific page
```html
<li class="nav-item active">
```
7. Toggler - collapse for shorter screens
```html
<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#Navbar">
    <span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="Navbar">
    <ul>
    ...
    </ul>
</div>
```
8. Add breamcrumb
```html
<ol class="col-12 breadcrumb">
    <li class="breadcrumb-item"><a href="./index.html">Home</a></li>
    <li class="breadcrumb-item active">About Us</li>
</ol>
```
