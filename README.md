# Solved-Tasks
   #### Discover The Original Price
```javascript
function discoverOriginalPrice(discountedPrice, salePercentage){
  return +(discountedPrice * 100 / (100 - salePercentage)).toFixed(2);
}
```
  #### Formatting decimal places #0
 ```javascript
function twoDecimalPlaces(n) {
  return +n.toFixed(2);
}
```
  #### Area of a Square
 ```javascript
function squareArea(A){
  const cir = 4 * A;
  const r = cir / (2 * Math.PI);
  return +Math.pow (r, 2).toFixed(2);
}
```