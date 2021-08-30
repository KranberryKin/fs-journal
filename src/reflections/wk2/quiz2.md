# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Var : is the default and base value setter.
let : is simular but can be used to update other values.
Const : is a perminit declared value that can't be changed.

```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->

```
A function is an object that can be called to run a set amount of code, or a proccess and sequence of code.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S - Single Responsibility
O - Open Close Principle
L - Liskov's Substitution Principle
I - Interface Segregation
D - Dependency inverion

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Arrays start at 0 and go up. So knowing that apples is 0, banana is 1, and pinapple is 2. So at fruit[2] will be pinapple.

```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
them.push(you[friends])
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
If you want to run a boleen test, you can run ? (<-for if) its true then output 'value' : (<- is or) 'value' then output false. The condition run both if its true and false.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
This is called the increment part of the for() loop. Increased by the set value you want it to or ++ defaults += 1 to access every part of the object. 
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
D - Document
O - Object
M - Model
The HTML is the main webpage and first access the the Document Object Model.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
1 - Undefined
2 - Null
3 - Boolean
4 - String
5 - Number
6 - Object
7 - Primitives
8 - Array
9 - NAN
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Argument is a value, and a parameter is the requirement of an Argument to run a function. A function doesn't need to parameter to use an argument. 
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primatives are Set Values and Data Types.
While Refrences are Objects liek Arrays and Dictionaries, which contain primatives.
```