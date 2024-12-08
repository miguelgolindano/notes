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