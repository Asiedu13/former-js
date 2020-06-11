# Former Js

Former Js - is a free and most modern framework developed to make developing forms as simple as possible. It is intended to make forms as responsive and good-looking as possible. Former JS is compatible with all platforms as well as modern browsers. Former is currently not available via CDN therefore must be downloaded and linked to projects in order for effective functioning.

# Getting Started
Former can be accessed via github
[Gitub Page](https://github.com/tonysaah/form-js/blob/master/)
Former JS is compatible with all platforms as well as modern browsers. Former is currently not available via CDN therefore must be downloaded and linked to projects in order for effective functioning.

## Linking Former JS
You can link either the main former file (former.js) or the minified version (former.min.js)

```html
<script src='former-js/src/former.js'></script>
```

> Or the minified version

```html
<script src='former-js/src/former.min.js'></script>
```

## The Css
In order to former to fully operate you need to also need to link the stylesheets provided

```html
<link rel='stylesheet' href='former-js/src/css/former.css'>
```
> Or the minified version

```html <link rel='stylesheet' href='former-js/src/css/former.min.css'> ```

## Creating a One Page Form
Former JS can be used to create a form which occupies the entire width and height of a page to facilitate design.
1.First Create a container with class='former-page' .
```html
<div class='former-page former-bg-red'>
  
</div>
```
You can add former utility classes to further customize your container - [Utility Classes](#utitlity-classes)

2. Create your form element with class='former-page'
```html
  <div class='former-page former-bg-red'>
    <form class='former-form former-bg-white'>
      <p class='former-title'>Login Form</p>
      <p class='former-subtitile>Connect to your Account</p>
    </form>
  </div>
```


Notice the `former-bg-red` and `former-bg-white` classes. Again, they are examples of utility classes for background colors. [View More Background Classes](#background-utility-classes)

3. Title and Subtitle ( <b>Optional</b> )
```html
  <div class='former-page former-bg-red'>
    <form class='former-form former-bg-white'>
      
    </form>
  </div>
```

# Utitlity Classes
Utility Classes on Former JS help with basic styling and responsiveness for your project. They include properties such as backgrounds, colors, border-radius, box-shadows, text-shadows and more.
### Background Color Classes

```css
  .former-bg-dark
  .former-bg-yellow
  .former-bg-blue
  .former-bg-red
  .former-bg-green
  .former-bg-white
```

### Text Color Classes
```css
  .former-text-dark
  .former-text-yellow
  .former-text-blue
  .former-text-red
  .former-text-green
  .former-text-white
```

### Box Shadow Classes
```css
  .former-box-sm
  .former-box-md
  .former-box-lg
  .former-box-none
```
