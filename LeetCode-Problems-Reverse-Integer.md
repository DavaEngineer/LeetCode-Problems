```javascript
var reverseInt = function (x) {
  var reversedNumber = parseInt(x.toString().split('').reverse().join('')) * Math.sign(x)
  if (Math.abs(reversedNumber) > Math.pow(2, 31) || x === 0) return 0
  return reversedNumber
}
```
