# Solved-Tasks
   ####Breaking chocolate problem
```javascript
    function breakChocolate(n,m) {
     let bar = n * m - 1;
     if ( bar < 0) return 0;
     return bar;
   }
```
   ####Sum of angles
   ```javascript
   function angle(n) {
     if (n >= 3)
     return (n - 2) * 180;
   }
   ```
  ####Convert boolean values to strings 'Yes' or 'No'.
   ```javascript
    function boolToWord( bool ){
     if (bool === true) return "Yes";
     return "No"
    }
   ```