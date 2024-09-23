## Return Negative

```js
function makeNegative(num) {
  if (num < 0) {
    return(num)
  } else if (num > 0) {
    return(-num) 
  } else if (num = 0) {
    return(0)
  }
}
```

## Sum of Positive

```js
function positiveSum(arr) {
    let sum = 0
    for (let i = 0; i < arr.length; i++) {
        if (arr[i] > 0) {
            (sum += arr[i])
        }
    }
    return(sum)
}
```

## Function 2

```js
function square(num) {
  return num*num
}
```

## Sum Arrays

```js
function sum (numbers) {
    let num = 0
     for (let i = 0; i < numbers.length; i++) {(num += numbers[i])}
      return num
 }
```

## Reversed Strings

```js
function solution(str){
    let reversed = ""
    for (let i = str.length-1; i >= 0; i--) {
      reversed += str[i]
    }
      return reversed
  }
```
