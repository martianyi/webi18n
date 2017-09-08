# webi18n

webi18n is forked from [fabi1cazenave/webL10n](https://github.com/fabi1cazenave/webL10n), with following modifications,
 - Use umd wrapper
 - Disables language initialization on page loading
 - Removes consoleWarn and consoleLog and use console.log/warn directly
 - Removes window._ assignment
 - Removes compatibility code for old IE
 
## Install with npm
`npm install webi18n --save`
 
## ES6 module
```
import webi18n from 'webi18n'
webi18n.ready(()=>{
     document.documentElement.lang = webi18n.getLanguage();
     document.documentElement.dir = webi18n.getDirection();
})
```
 
Refer to [fabi1cazenave/webL10n/wiki](https://github.com/fabi1cazenave/webL10n/wiki) for usage.
 