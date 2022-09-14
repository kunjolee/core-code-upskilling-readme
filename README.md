# core-code-upskilling-readme | solutions

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

  
