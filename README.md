# Solved-Tasks
   ####I love you, a little , a lot, passionately ... not at all
   ```javascript
   function howMuchILoveYou(nbPetals) {
       const fl = ['I love you', 'a little', 'a lot', 'passionately', 'madly', 'not at all'];
       return fl[(nbPetals - 1) % 6]
   }
   ```
   ####Third Angle of a Triangle
   ```javascript
   function otherAngle(a, b) {
     let c = 180  - a - b;
     return c;
   }
   ```
  ####For Twins: 2. Math operations
   ```javascript
    function iceBrickVolume(radius, bottleLength, rimLength) {
      let h = bottleLength - rimLength;
      let a = Math.sqrt(2) * radius;
      let volume = a ** 2 * h;
      volume  = Math.floor(volume);
      return volume;
    }
   ```