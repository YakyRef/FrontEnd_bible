# Front Ends resurses and snippets  
A Common use Front Ends resurses and snippets.    

## Resurses

### Blogs
- https://css-tricks.com

### Live editors:
- http://codepen.io/

### Insperation:
- https://dribbble.com/
- http://littlesnippets.net/

### CSS:
- https://daneden.github.io/animate.css/

### Tools and Generators:
- base64-encoder : https://jpillora.com/base64-encoder/
- gradient-generator : http://www.cssmatic.com/gradient-generato
- box-shadow-generator : http://www.cssmatic.com/box-shadow

### The bible of Flex-Box:
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/



## Snippets

### ES6:

#### arrays:
- map():
```javascript
var numbers = [1, 4, 9];
var doubles = numbers.map( (num)=> {
  return num * 2;
});
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
