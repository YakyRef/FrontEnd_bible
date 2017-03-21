# Front Ends resources and snippets  
A Common use Front Ends resources and snippets.    

## Resurses

### Blogs
- https://css-tricks.com

### Live editors:
- http://codepen.io/

### Insperation:
- https://dribbble.com/
- http://littlesnippets.net/

### UI Frameworks
- http://materializecss.com/
- http://www.material-ui.com/
- http://getbootstrap.com/
- https://react-bootstrap.github.io/

### CSS:
- https://daneden.github.io/animate.css/

### Tools and Generators:
- base64-encoder : https://jpillora.com/base64-encoder/
- gradient-generator : http://www.cssmatic.com/gradient-generato
- box-shadow-generator : http://www.cssmatic.com/box-shadow

### The bible of Flex-Box:
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/

### Fonts:
- http://fontawesome.io/
- http://fontello.com/


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
```javascript
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
```javascript
npm uninstall `ls -1 node_modules | tr '/\n' ' '`
```




## Credits:
---
- https://developer.mozilla.org
