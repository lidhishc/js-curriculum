# Array

Array is an ordered list of values. Each value is called an element specified by an index.

## **Challenges**

### Challenge 1

```
Create an array in 2 different ways.
```

<details>
<summary>Hint</summary>

```
let arr = new Array();
let arr = [];
```

</details>

### Challenge 2

```
Create an array consisting of element "Apple", "Orange", "Plum" using Array() constructor
```

<details>
<summary>Hint</summary>

```
let a = new Array("element1","element2"); // a = ["element1","element2"]
```

</details>

### Challenge 3

```
Find the 3rd element of fruits = ["Apple", "Orange", "Plum","Berry"];
```

<details>
<summary>Hint</summary>

```
array[index] = value of the indexed array element.
index starts with 0.
ex:
let array = ["element1","element2","element3","element4"];
array[2] // "element3"
array[0] // "element1"

```

</details>

### Challenge 4

```
Change fruits = ["Apple", "Orange", "Plum","Berry"] into fruits = ["Apple", "Mango", "Plum","Berry"]
```

<details>
<summary>Hint</summary>

```
let array = ["element1","element2","element3","element4"];
array[1]="elementNew" // array= ["element1","elementNew","element3","element4"]
```

</details>

### Challenge 5

```
Find the number of elements in array = ["Apple", "Orange",...., "Plum","Berry"];
```

<details>
<summary>Hint</summary>

```
let array = ["element1","element2","element3","element4"];
array.length // 4
```

</details>

### Challenge 6

```
Find the last element of array = ["Apple", "Orange",...., "Plum","Berry"];
```

<details>
<summary>Hint</summary>

```
let array = ["element1","element2",...,"elementN"];
array[array.length-1] //  "elementN"
```

</details>

### Challenge 7

```
Change the "Berry" to "Mango" of array = ["Apple", "Orange",...., "Plum","Berry"];
```

### Challenge 8

```
Convert array fruits = ["Banana", "Orange", "Apple", "Mango"] to 'Banana,Orange,Apple,Mango'
```

<details>
<summary>Hint</summary>

```
let array = ["element1","element2","element3","element4"];

Strategy 1
array.toString() // 'element1,element2,element3,element4'

Strategy 2
array.join() // 'element1,element2,element3,element4'

```

</details>

### Challenge 9

```
Remove the last element from fruits = ["Banana", "Orange", "Apple", "Mango"] and store it into a variable.
```

<details>
<summary>Hint</summary>

```
let array = ["element1","element2","element3","element4"];
let lastElement = array.pop(); //lastElement = "element4"
```

</details>

### Challenge 10

```
Remove the first element from fruits = ["Banana", "Orange", "Apple", "Mango"] and store it into a variable.
```

<details>
<summary>Hint</summary>

```
let array = ["element1","element2","element3","element4"];
let firstElement = array.shift(); //firstElement = "element1"
```

</details>

### Challenge 11

```
Add the a new element in the end of fruits = ["Banana", "Orange", "Apple", "Mango"].
```

<details>
<summary>Hint</summary>

```
let array = ["element1","element2","element3","element4"];
 array.push("element5");
```

</details>

### Challenge 12

```
Add the a new element in the beginning of fruits = ["Banana", "Orange", "Apple", "Mango"].
```

<details>
<summary>Hint</summary>

```
let array = ["element1","element2","element3","element4"];
 array.unshift("element0");
```

</details>

### Challenge 13

```
Console.log each elements in the array=["Banana", "Orange", "Apple", "Mango"],without finding the length of the array.
```

<details>
<summary>Hint</summary>

[Array.prototype.forEach()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)

</details>

### Challenge 14

```
Convert array=[1,2,[2,33,44],[33,334]] into single dimension array.
```

<details>
<summary>Hint</summary>

[Array.prototype.flat()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flat)

</details>

### Challenge 15

```
Find all the element which having length greater than 4 in words = [ability', 'able', 'about', 'above', 'accept', 'according', 'account', 'across', 'act', 'action', 'activity', 'actually', 'add'].
```

<details>
<summary>Hint</summary>

[Array.prototype.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

</details>
</details>

### Challenge 16

```
Find the first element which having length greater than 4 in words = [ability', 'able', 'about', 'above', 'accept', 'according', 'account', 'across', 'act', 'action', 'activity', 'actually', 'add'].
```

<details>
<summary>Hint</summary>

[Array.prototype.find()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)

</details>
</details>

### Challenge 17

```
Find the first element which having 't' as the last letter of the word in words = [ability', 'able', 'about', 'above', 'accept', 'according', 'account', 'across', 'act', 'action', 'activity', 'actually', 'add'].
```

<details>
<summary>Hint</summary>

[Array.prototype.findIndex()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex)

</details>
</details>

### Challenge 18

```
Add elements of fruits1 = ["Banana", "Orange", "Apple", "Mango"] into fruits2 = ["Pineapple", "Guava", "Fig", "Lemon"];
```

<details>
<summary>Hint</summary>

[Concat Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat)

</details>

### Challenge 19

```
Check weather some numbers in array=[1,2,33,45,111,28] is greater than 5?
(do not use map, forEach, filter, for )
```

<details>
<summary>Hint</summary>

[Array.prototype.some()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/some)

</details>

### Challenge 20

```
Replace the values of "Banana", "Orange" with "Apple", "Mango" in fruits = ["Banana", "Orange", "Apple", "Mango"]  without using another array or with out using any looping methods
```

<details>
<summary>Hint</summary>

[Array.prototype.copyWithin()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin)

</details>

### Challenge 21

```
Check weather all numbers in array=[1,2,33,45,111,28] is greater than 5?
(do not use map, forEach, filter, for )
```

<details>
<summary>Hint</summary>

[Array.prototype.every()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/every)

</details>

### Challenge 22

```
Check fruits = ["Banana", "Orange", "Apple", "Mango"] has element "Berry" ?
```

<details>
<summary>Hint</summary>

[Array.prototype.includes()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)

</details>

### Challenge 23

```
create a new array  which will have the square of each element in array = [1,2,3,4,5]?
```

<details>
<summary>Hint</summary>

[Array.prototype.map()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

</details>

### Challenge 24

```
Find the sum of elements in array = [1,2,3,4,5]?
```

<details>
<summary>Hint</summary>

[Array.prototype.reduce()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)

</details>

### Challenge 25

```
Reverse the order of element in the array=[1,2,3,4,5,6,7,8,9,10]?
```

<details>
<summary>Hint</summary>

[Array.prototype.reverse()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reverse)

</details>

### Challenge 26

```
Copy elements from index 2 to 5 from array=[1,2,3,4,5,6,7,8,9,10] into a new array?
```

<details>
<summary>Hint</summary>

[Array.prototype.slice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)

</details>

### Challenge 27

```
Remove the element 5 from the array=[1,2,3,4,5,6,7,8,9,10] without creating a new array?
```

<details>
<summary>Hint</summary>

[Array.prototype.splice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)

</details>

### Challenge 28

```
Add a new element "Berry" in the 3rd index of array=["Banana", "Orange", "Apple", "Mango"] without creating a new array?
```

<details>
<summary>Hint</summary>

[Array.prototype.splice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)

</details>

### Challenge 29

```
Sort the array=["Banana", "Orange", "Apple", "Mango"] in ascending order without creating a new array?
```

<details>
<summary>Hint</summary>

[Array.prototype.sort()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)

</details>
