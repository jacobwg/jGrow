# jGrow

[jGrow](http://plugins.jquery.com/project/jGrow) is a [jQuery](http://jquery.com) [plugin](http://plugins.jquery.com) that allows for auto-growing textareas that adjust size according to the length of the text.
        
It works smoothly with **jQuery 1.3+**. It was tested on IE6+, Firefox 2+, Opera 9.x+, Safari 3+, Google Chrome 2+ and no bugs have spotted yet.

## Installation

jGrow requires jQuery, so be sure that jQuery is installed on your webpage:

```html
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
```
        
Include the jGrow include tag *after* jQuery:

```html
<script src="jquery.jgrow.js"></script>
```
        
## Usage

Usage is simple:

```javascript
$('textarea').jGrow();
```
        
And jGrow is ready to use! If you want to specify a maximum height, use the following syntax:

```javascript
$('textarea').jGrow({
  max_height: '300px'
});
```
