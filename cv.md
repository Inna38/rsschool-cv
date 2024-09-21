# Inna Didenko

## Contacts
* +38-097-876-17-97
* innadidenko29@gmail.com

## About Me
 I am a switcher and I am changing my life and field of activity to
 web development. This work brings me personal satisfaction. I like
 to work and see the results of my work. I would like
 to work in a large company and be part of a big project.

## Skils
* Figma
* Git
* HTML
* CSS 
* Sass
* JavaScript 
* React

## Code example:
### Count strings in objects
* Create a function strCount (takes an object as argument) that will count all string values inside an object.

```

function strCount(obj){
let sum = 0
for(let keys in obj){
if( typeof obj[keys] === 'string') {
  sum += 1
  }
  if ( typeof obj[keys] === 'object'){
    sum += strCount(obj[keys])
  }
} return sum
}

```