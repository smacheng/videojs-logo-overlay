#videojs-logo-overlay


## Usage

### Include the plugin JS/CSS:

```html
<link rel="stylesheet" href="c/path/to/videojs-logo-overlay.css">
<script src="/path/to/videojs-logo-overlay.js"></script>
```

### Enable the plugin
Add videojs-logo-overlay plugin to your Videojs ready function.
Check the [Options](#options) section below for the available options and their meaning.

```js
videojs('vidId').ready(function() {
  this.logoOverlay({
    src: 'PATH/logo.png',
    link: 'PATH/linkURL'
  });
});
```

## Options

####src 

`(string)` Logo image's URL

####link 

`(string)` A HTML tag's href attribute value. Default target is set to _blank.  (default: `#`)


####margin 

`(number)` Logo image's margin from video container's corner. (default: `0`)

####userActive 

`(boolean)` Enables show/hide logo image when videojs user-active is change. (default: `false`)

####position 

`(string)` Logo image's position value. **TL** : Top-Left, **TR** : Top-Right, **BL** : Bottom-Left, **BR** : Bottom-Right (default: `TL`)

####width 
`(number)` Logo image's width px. (default `null`)

####height
`(number)` Logo image's height px. (default `null`)
