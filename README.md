# Simple CSS content placeholder
## Introduction
This is a dead simple content placeholder loader inspired by [this article](https://cloudcannon.com/deconstructions/2014/11/15/facebook-content-placeholder-deconstruction.html).
## Demo
[https://linways.github.io/simple-content-placeholder/](https://linways.github.io/simple-content-placeholder/)

## Usage
Just download and include `content-placeholder.min.css` inside `<head>` tag of your HTML page. You can even copy and paste the content inside a `<style></style>` tag for faster loading. (Its really light weight, ~30 lines of css unminified).

To add the placeholder, just insert this span tag wherever you require.

```html
<span class="content-placeholder" style="width:50px;">&nbsp;</span>
```
Don't forget to change the width as required.  
You can also use the class `content-placeholder` on any element to add the cool loading animation.
```html
<div class="col-md-4 content-placeholder"></div>
```
## Credits
Author of [this article](https://cloudcannon.com/deconstructions/2014/11/15/facebook-content-placeholder-deconstruction.html).
