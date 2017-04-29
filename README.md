# Front Ends resources and snippets  
A Common use Front Ends resources and snippets.    

## Resurses

### Blogs
- [Css-tricks](https://css-tricks.com)
- [Hackernoon](https://hackernoon.com)
- [Smashingmagazine](https://www.smashingmagazine.com)
- [Sitepoint](http://www.sitepoint.com)
- [Codrops](http://tympanus.net/codrops)

### Live editors:
- [Codepen](http://codepen.io/)
- [React live editor - Codesandbox](https://codesandbox.io)
- [Plnkr](http://plnkr.co)
- [Jsfiddle](https://jsfiddle.net)
- [Jsbin](https://jsbin.com) 
- [Cloud 9](https://c9.io)
- [Feditor](http://feditor.tech/)

### Insperation:
- [https://dribbble.com/](dribbble)
- [http://littlesnippets.net/](littlesnippets)

### UI Frameworks
- [materializecss](http://materializecss.com/)
- [material-ui](http://www.material-ui.com/)
- [getbootstrap](http://getbootstrap.com/)
- [react-bootstrap](https://react-bootstrap.github.io/)
- [Foundation for Sites](http://foundation.zurb.com/sites/docs/)
- [Foundation for Emails](http://foundation.zurb.com/emails/docs/)

### CSS:
- [https://daneden.github.io/animate.css/](animate.css)

### Tools and Generators:
- [https://jpillora.com/base64-encoder/](base64-encoder) 
- [http://www.cssmatic.com/gradient-generato](gradient-generator) 
- [http://www.cssmatic.com/box-shadow](box-shadow-generator)  

### The bible of Flex-Box:
- [https://css-tricks.com/snippets/css/a-guide-to-flexbox/](a-guide-to-flexbox)

### Fonts:
- [Font Awesome](http://fontawesome.io/)
- [Fontello](http://fontello.com/)
- [IcoMoon](https://icomoon.io/app/)

### CLI Tools:
- [Bower](https://bower.io/)
- [npm](https://docs.npmjs.com/)
- [AKA](https://www.npmjs.com/package/as-known-as)
- [jq](https://stedolan.github.io/jq/)

### Chrome Extensions:
- [D2](https://chrome.google.com/webstore/detail/d2-developer-documentatio/pcndaioeajanljljbjglanbmnmhgdjln)
- [EditThisCookie](http://www.editthiscookie.com/)
- [Allow-Control-Allow-Origin: *](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi)

## Snippets

### ES6:

#### arrays:
- map():

```
var numbers = [1, 4, 9];
var doubles = numbers.map( (num)=> {
  return num * 2;
});

// doubles = [2, 8, 18]
// https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Global_Objects/Array/map
```

- reduce():

```
var names = ['Alice', 'Bob', 'Tiff', 'Bruce', 'Alice'];
var countedNames = names.reduce((allNames, name) => { 
  if (name in allNames) {
    allNames[name]++;
  }
  else {
    allNames[name] = 1;
  }
  return allNames;
}, {});

// Object {Alice: 2, Bob: 1, Tiff: 1, Bruce: 1}
// credit : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce
```

### NPM: 

- delete all 'node_modules' packages :

``` npm uninstall `ls -1 node_modules | tr '/\n' ' '` ```




### React.Js:

#### Redux:

- mapDispatchToProps shortcut:
``` 
import * as actionCreators from './actionCreators'

export default connect(null, actionCreators)(TodoApp)
```

## Credits:
---
- https://developer.mozilla.org
