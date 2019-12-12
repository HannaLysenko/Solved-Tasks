# Solved-Tasks
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
