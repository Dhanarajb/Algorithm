#### Linear Search

```
let arr = [-5, 2, 10, 4, 6];
let target = 10;

function linearSearch(arr) {
  for (let item of arr) {
    if (item === target) {
      return true;
    }
  }
}
console.log(linearSearch(arr));

```
