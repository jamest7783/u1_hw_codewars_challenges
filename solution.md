## Return Negative
```
function makeNegative(num) {
  return num > 0 ? -num : num 
}

```

## Sum of Positive
```
function positiveSum(arr) {
  let total = 0
  for ( let i = 0; i < arr.length; i++ ) {
    arr[i] > 0 ? total += arr[i] : total += 0 
  }
  return total
}
```

## Function 2
```
const square = ( num ) => {
  return num*num
}
```

## Sum Arrays
```
function sum (numbers) {
    let total = 0
    for ( let i = 0; i < numbers.length; i++ ) {
        total += numbers[i]
    }
    return total
};
```

## Reversed Strings

```
function solution( str ){
  let newStr = ''
  for ( let i = str.length-1; i >= 0; i-- ) {
    newStr = newStr.concat( str[i] )
  }
  return newStr
}
```
