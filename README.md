## JavaScript Notes

### Array Properties & Methods

```
An array is a special variable, which can hold more than one value at a time.
example: [ 1, 2, {a: 1, b: 2}, "three"]
```

#### Properties

- length

> Reflects the number of elements in an array.

- prototype

> A symbol containing property names to exclude from a with binding scope. Instance methods

#### Methods

- concat()

- Returns a new array that is this array joined with other array(s) and/or value(s).

copyWithin()

- Copies a sequence of array elements within the array.

entries()

- Returns a new Array Iterator object that contains the key/value pairs for each index in the array.

every()

- Returns true if every element in this array satisfies the testing function.

fill()

- Fills all the elements of an array from a start index to an end index with a static value.

filter()

- Returns a new array containing all elements of the calling array for which the provided filtering function returns true.

find()

- Returns the found element in the array, if some element in the array satisfies the testing function, or undefined if not found.

findIndex()

- Returns the found index in the array, if an element in the array satisfies the testing function, or -1 if not found.

forEach()

- Calls a function for each element in the array.

includes()

- Determines whether the array contains a value, returning true or false as appropriate.

indexOf()

- Returns the first (least) index of an element within the array equal to an element, or -1 if none is found.

join()

- Joins all elements of an array into a string.

keys()

- Returns a new Array Iterator that contains the keys for each index in the array.

lastIndexOf()

- Returns the last (greatest) index of an element within the array equal to an element, or -1 if none is found.

map()

- Returns a new array containing the results of calling a function on every element in this array.

pop()

- Removes the last element from an array and returns that element.

push()

- Adds one or more elements to the end of an array, and returns the new length of the array.

reduce()

- Apply a function against an accumulator and each value of the array (from left-to-right) as to reduce it to a single value.

reduceRight()

- Apply a funciton against an accumulator> and each value of the array (from right-to-left) as to reduce it to a single value.

reverse()

- Reverses the order of the elements of an array in place. (First becomes the last, last becomes first.)

shift()

- Removes the first element from an array and returns that element.

slice()

- Extracts a section of the calling array and returns a new array.

some()

- Returns true if at least one element in this array satisfies the provided testing function.

sort()
-Sorts the elements of an array in place and returns the array.

splice()

- Adds and/or removes elements from an array.

toLocaleString()

- Returns a localized string representing the array and its elements. Overrides the Object.prototype.toLocaleString() method.

toString()
-Returns a string representing the array and its elements. Overrides the Object.prototype.toString() method.

unshift()

- Adds one or more elements to the front of an array, and returns the new length of the array.

values()

- Returns a new Array Iterator object that contains the values for each index in the array.
