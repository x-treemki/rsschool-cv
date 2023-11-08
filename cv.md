## Aliaksandr Plitsin
## Contacts:
- adtreem@gmail.com
- +37063294335


## About me:
Started web developer career in 2010, creating simple one-page websites. But plans soon changed and I returned to the code only in 2023. Now I’m actively studying the front end and taking RS school courses.

## Skills:
- HTML, CSS (basic))
- VScode, Photoshop

## Code example:
- Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.

  function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    } 
  }
  return -1;
} 