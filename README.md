# Former Js

Former Js - is a free and most modern framework developed to make developing forms as simple as possible. It is intended to make forms as responsive and good-looking as possible. Former JS is compatible with all platforms as well as modern browsers. Former is currently not available via CDN therefore must be downloaded and linked to projects in order for effective functioning.

# Getting Started
Former can be accessed via github
[Gitub Page](https://github.com/tonysaah/form-js/blob/master/)
Former JS is compatible with all platforms as well as modern browsers. Former is currently not available via CDN therefore must be downloaded and linked to projects in order for effective functioning.

## Linking Former JS
You can link either the main former file (former.js) or the minified version (former.min.js)

``` <script src='former-js/src/former.js'></script> ```

> Or the minified version

``` <script src='former-js/src/former.min.js'></script> ```

## Creating a One Page Form
Former JS can be used to create a form which occupies the entire width and height of a page to facilitate design.
1.First Create a container with class='former-page' .
```
<div class='former-page former-bg-red'>
  
</div>
```
You can add former utility classes to further customize your container - [Utility Classes](#utitlity-classes)

2. Create your form element with class='former-page'
```
  <div class='former-page former-bg-red'>
    <form class='former-form former-bg-white'>
    
    </form>
  </div>
```

Notice the `former-bg-red` and `former-bg-white` classes. Again, they are examples of utility classes for background colors. [View More Background Classes](#background-utility-classes)

# Utitlity Classes
Utility Classes on Former JS help with basic styling and responsiveness for your project. They include properties such as backgrounds, colors, border-radius, box-shadows, text-shadows and more.
### Background Color Classes

```
  .former-bg-dark
  .former-bg-yellow
  .former-bg-blue
  .former-bg-red
  .former-bg-green
  .former-bg-white
```

### Text Color Classes
```
  .former-text-dark
  .former-text-yellow
  .former-text-blue
  .former-text-red
  .former-text-green
  .former-text-white
```

### Box Shadow Classes
```
  .former-box-sm
  .former-box-md
  .former-box-lg
  .former-box-none
```
