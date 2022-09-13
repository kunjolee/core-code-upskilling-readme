# core-code-upskilling-readme
## My solutions

### Tuesday 9/13/2022

#### 1. Ensure Question
```js
function ensureQuestion(s) { 
  return s.endsWith('?') 
    ? s 
    : s + '?'
}
```
  
#### 2. Reverse Sentence
```js
function reverseWords(str){  
  return str.split(" ").reverse().join(" ")
}
```
