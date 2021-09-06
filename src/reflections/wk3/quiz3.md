# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
There are four Pillars when it comes to Object Oriented Programming.
First there is Abstraction, Then there is Excapsulation, Next there is Inheritance, Lastly there is Polymorphism.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
either : staff.name
or : console.log(staff.name)
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
When you add properties to an object, you are encapsulating the properties to the object. 
Putting unquie properties or functions that can only be use within it's container or object.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility principle.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
An exported class can be accessed and used functions with set input if allowed or needed. But for an instance of an class, it can only be refrenced. Therefore only calling the functions that are within in and not being able to controle the data going into the functions.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
Proxy is like a comunicator between a user and the object itself. So a proxy object would be an instance of the object that may be usable to a certain degree by the user.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
This pattern is used to limit the amount of control the user has over the given applications. By using the MVC pattern, it fulfils the purpose of limited user control, with intentful and purposful usage of application.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller is the inputs you allow the user to access and 'press' on the controller. Normally these controls call the service to finish their job for them. But here it can draw the screen and show the user that they are 'moving' in or using the app. 
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
The service is called by the controller so the user doesn't have access to it. Here the service changes and manipluates he values that are needed for it given property. Often refrences the ProxyState to change values and add object to arrays.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Model soul purpose is to be a blueprint to refence too, and use an template on the blueprint specifically with forEach() functions. This is to keep display simular and work simplistic having reusable code. Here models can be used to create new instances of objects with set properties. And properties not given will be undefined.
```

