# Solved-Tasks
   ####Multiple of index
   ```javascript
   function multipleOfIndex(array) {
     return array.filter((num, i) => num % i === 0);
   }
   ```
   ####Generate range of integers
   ```javascript
   function generateRange(min, max, step){
     const arr = [];
     for (let i = min; i <= max; i += step){
     arr.push(i)
     }
     return arr;
   }
   ```