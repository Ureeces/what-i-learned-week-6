# What I Learned Week 6
 
## Arrays
Arrays in Javascript are objects that store a set of elements, which can be accessed using their index #.

**Syntax**:
`const myArray = [obj1, obj2, ...];`

### Methods:
* `.push(element)` - stores element into the end of an array
* `unshift()` - adds element(s) to an array and return the new length of the array
* `.slice()` - returns a copy of the array, starting/ending from the given parameters. It does not modify the original array.
* `.splice()` - replaces/removes elements of an array. It modifies the original array.
* `.join(arr)` - combines two arrays into a new array containing all elements of both arrays
* `.concat(arr)` - combines all elements of an array into one string
* `.reverse()` - reverses the order of the array


## Loops
### While 
A while loop is a condition controlled loop that continuously runs a block of code until the condition is no longer met. 

**Syntax:** 
`while (condition) {`
`// code here`
`}`

### Uses:
* Very useful for flags
* Most useful if you know that a block of code's runtime is tied to a condition, and don't know the exact number of repeats
* Servers (`while(true)`)
---

### For
A for loop is a count controlled loop that continuously runs a block a code for a finite amount of times, and stops when it has run a specified amount of times.

**Syntax:** 
`for(let i = start; i < end; i++) {`
`// code here`
`}`

*You may also count backwards, can go by different increments, and cycle through elements of an array or string.

#### Uses:
* Very useful for cycling through elements of objects, arrays, and strings
* Most useful if you know how many times you need to run a block of code


