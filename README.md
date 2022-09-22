# core-code-upskilling-readme | solutions
## Week 2
### Tuesday 9/19/2022

```js
  function well(x){
     
  const res = x.reduce( (acc, el)=> {        
    return (el === "good") 
      ? acc + 1     
      : acc + 0;          
  }, 0 )
  
  
  return res === 0
     ? 'Fail!'
     : (res > 0 && res < 3) 
       ? 'Publish!'
       : 'I smell a series!'      
  }

```

### Monday 9/19/2022

```js
function isPalindrome(line) {
  let allString = line.toString();    
  return allString.split('').reverse('').join('') === allString
  ;
}

## Week 1
```
### Friday 9/16/2022

```js
function oddOrEven(array) {          
  const sum = array.reduce((acc,el)=> acc + el  , 0);        
  return (sum % 2 === 0) ? 'even' : 'odd'
}
```

### Wednesday 9/14/2022

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

  
