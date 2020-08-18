# reverse-js-emoji

if a site uses [js-emoji](https://github.com/iamcal/js-emoji) you can pass the text into replaceEmoji() and get the text with the correct Unicode Emojis back

```javascript
var reverseJsEmoji = require("reverse-js-emoji");
console.log(reverseJsEmoji.replaceEmoji('Wow it works very well. <span class="emoji-outer emoji-sizer"><span class="emoji-inner emoji1f62f"></span></span>'));

"Wow it works very well. 😯"
```

because the library uses matchAll you need at least Nodejs V12
