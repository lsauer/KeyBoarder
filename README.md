<img src="http://lsauer.github.com/KeyBoarder/gh-pages/res/img/keyboard_grey.png" style="border:0px; margin:10px; margin-right:30px; float:left; zoom:0.5;">

KeyBoarder.JS
=============
    /*--------------------------README-------- EMDAER------------------------------*/
##### `    `*interactive Keyboard shortcut rendering for blogs and docs*



**author**: Lo Sauer (c)2011; www.lsauer.com  
**website**: https://lsauer.github.com/KeyBoarder  
**license**: MIT or BSD - dual licensed  
**description:**  KeyBoarder is a small, fast javascript library for dynamically rendering appealing, navigatable keyboard shortcuts  
**note:** Please contribute if you like the project. New CSS Styles are always welcome. <br>


#### Features:
 - Avoid cluttering your documents with HTML tags
 - Event binding: allow users to navigate to the shortcut-description in your document, simply by pressing the given key-combination
 - Apealing design
 - visual feedback of the currently pressed key(s)
 - Configurable: KeyBoarder can be constrained to certain HTML tags
 - compartmentalized instance. Different instances of KeyBoarder can process different parts of a site differently
 - KeyBoarder can be turned off at any time through the method: `mykeyBoardInstance.restore(status)`, where `status` is an integer between 0-2
 - Specificity: Individual styles and events can be set at the level of single keys
 - Ideal for blogs, application documentations, or any other documents that describe the use of shortcut combinations
 - Works in FireFox, Opera and WebKit (Chrome, Safari,...)

#### Project Links
- https://github.com/lsauer/KeyBoarder
- http://code.google.com/p/keyboarder/

#### Getting started
- Include the following css:  
```html
	<link rel="stylesheet" type="text/css"  href="https://github.com/lsauer/keyboarder/raw/master/keyboarder.css">
```

- Include the following javascript:  
```html
    <script type="text/javascript" src="https://github.com/lsauer/keyboarder/raw/master/keyboarder.js" charset="utf-8"></script>
```