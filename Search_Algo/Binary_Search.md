#### Binary Search

```
function binarySearch(arr, target) {
  let i = 0;
  let j = arr.length - 1;

  while (i <= j) {
    let mid = Math.floor((i + j) / 2);
    if (arr[mid] < target) {
      i = mid + 1;
    } else if (arr[mid] > target) {
      j = mid - 1;
    } else {
      return mid;
    }
  }

  return -1;
}

const arr = [1, 3, 5, 7, 9, 11, 13, 15];
const target = 7;

console.log(binarySearch(arr, target));
```
