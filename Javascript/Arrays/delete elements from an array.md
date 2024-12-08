```
const removeFromArray = function(array, ...toRemove) {
  let newArray = [];
  array.forEach((item) => {
    if (!toRemove.includes(item))
      newArray.push(item);
  })
  return newArray;
};
```

this work using an arrow function and a forEach loop iterating in every item of the array and checking if the ...args not are in the array with the `if (!toRemove.includes(item)` then if is indeen not in the array create a new array with push
