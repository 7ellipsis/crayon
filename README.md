# crayonz


> ANSI based color and formatting for the console

## Why?
It loads and runs in a blink. It's super light, with no dependencies[experimental].

## Installation
```
$ npm install crayonz

```

## Usage

console.log(crayonz.blue("Hey!"));
With the help of chaining, different effects can be applied together.

```js
var crayonz = require('crayonz')

crayonz.red('Aha!')
crayonz.bgRed('Aha!')
crayonz.green('Aha!')
crayonz.bgGreen('Aha!')
crayonz.magenta('Aha!')
crayonz.cyan('Aha!')
crayonz.white('Aha!')
crayonz.gray('Aha!')
crayonz.inverse('Aha!')
crayonz.black('Aha!')
crayonz.strikethrough('Aha!')
crayonz.red('Ah!')
crayonz.bgRed('I\'m Blue')
crayonz.underline(crayonz.cyan('de da m a die'))
crayonz.dim('Sleepy!')
crayonz.bold('Writing README is boring.  zzzz`')

API=>           
**modifiers**
  italic        
  underline     
  inverse
  reset         
  bold          
  dim       
  hidden        
  strikethrough 
  
**text colors**  
  black         
  gray          
  yellow        
  blue          
  magenta       
  cyan          
  white               
  red           
  green         
     
  
**backgrounds**  
  bgblack       
  bggray                
  bgred         
  bggreen       
  bgyellow      
  bgblue        
  bgmagenta     
  bgcyan        
  bgwhite       
  



## License
[ISC](https://tldrlegal.com/license/ISC-license)
