# core-code-upskilling-readme | solutions

## Friday 9/16/2022

```js
function oddOrEven(array) {          
  const sum = array.reduce((acc,el)=> acc + el  , 0);        
  return (sum % 2 === 0) ? 'even' : 'odd'
}
```

## Wednesday 9/14/2022

### 1. Smallest Integer In Array
```js
class SmallestIntegerFinder {
  findSmallestInt(args) {        
    return Math.min(...args)
  }
}
```

## Tuesday 9/13/2022

### 1. Ensure Question
```js
function ensureQuestion(s) { 
  return s.endsWith('?') 
    ? s 
    : s + '?'
}
```
  
### 2. Reverse Sentence
```js
function reverseWords(str){  
  return str.split(" ").reverse().join(" ")
}
```

  
