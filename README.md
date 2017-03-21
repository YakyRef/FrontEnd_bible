# Front Ends resources and snippets  
A Common use Front Ends resources and snippets.    

## Resurses

### Blogs
- [css-tricks](https://css-tricks.com)

### Live editors:
- [codepen.io](http://codepen.io/)

### Insperation:
- [https://dribbble.com/](dribbble)
- [http://littlesnippets.net/](littlesnippets)

### UI Frameworks
- [http://materializecss.com/](materializecss)
- [http://www.material-ui.com/](material-ui)
- [http://getbootstrap.com/](getbootstrap)
- [https://react-bootstrap.github.io/](react-bootstrap)

### CSS:
- [https://daneden.github.io/animate.css/](animate.css)

### Tools and Generators:
- [https://jpillora.com/base64-encoder/](base64-encoder) 
- [http://www.cssmatic.com/gradient-generato](gradient-generator) 
- [http://www.cssmatic.com/box-shadow](box-shadow-generator)  

### The bible of Flex-Box:
- [https://css-tricks.com/snippets/css/a-guide-to-flexbox/](a-guide-to-flexbox)

### Fonts:
- [http://fontawesome.io/](fontawesome)
- [http://fontello.com/](fontello)


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

## Credits:
---
- https://developer.mozilla.org
