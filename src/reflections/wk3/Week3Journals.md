**What problem does using exports solve?**

Any function can be accessed from the terminal, and values can be set too. By using imports and exports. you can choose what functions and processes you want ran outside of file location. So the user can only do action in game, like intended for.

**How does export differ from export default?**

When you export you have access to functions and element from the export. But if you export default, you can use an alias name for the imported information. Which then can be used as an element itself with the functions and elements as properties.

**What is a benefit of using the Module System?**

Limmiting the amount of power, and control the user has over the webpage. You can make it to where the user is only able to click the use the buttons and functions given to them, instead of base values like currency in game manipulation.

**Mondays Challenge Link:**



**What is the purpose of Encapsulation?**

When you make/ 'let' a variable in a function you are encapsulating the variable and decresing its scope range.
When you encapsulate an variable, it is uniquie to the function and can be reused only in the function.
When you Encapsulate a function in class, and you export that class. You are limiting what the user and do with the class you give them.
When you add properties to an object, you are encapsulating the properties to the object. 

**What were some of the problems with closures and the underscore prefix?**

When you try to call a function that is not in the closure, it pull an error and says you dont have access to the function. Than normally the function also has an underscore pre-fix to it, as an indicator. You'd have the call a function in the closure, than from the closure call the underscore prefix function there, in order to run said function properly. 

**How do we create private variables in a ES6 Class? Why would you do this?**

  you can set private variables with special symbols like #, then these can be set outside  a constructor so you can manipulate a variable without having it be changed by the user.

**Tuesday Challenge Link:**


**What are the two common operations that we will set in the handler?**

get funcitons in order to load templates in html and proccess code from one controller to a service if needed. Then an constructor is another operation that we can have within a handler. this runs needed Proxy state changes and draw functions, while also loading certain code the moment the page runs if needed.

**What do you have to make sure you are doing with every Get to insure the value does not become undefined?**

Everytime you run a get function, you'd need to return a value. When you return a value, the get function actually receives the data then and can use it.


**What are some of the benefits of the proxy object that we are using in our structure for applications?**

When you call an proxy object, get functions have diferent logic when it runs. Instead of accessing the property of the object, you can check if a property is being changed or set. 

**Wednesday Challenge Link:**



**What problems does the Observer Pattern seek to solve?**

Observer pattern moderates over it's own array, also it can run functions which manipulate or change the value of its array.

**What are the three mechanisms of the observer pattern?**

There is Subscribe, then Unsubscribe, and lastly Broadcast. 

**Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.**

I am not sure how to answer this quesiton. I beleive that an observer and iderate over a set of data and add it to it's array. Where it then can add, remove, or change the neeeded values in the array. But with having things in a proxy state of being. obervers may not be able to acess certain inforation, or for instance change information. So we have an observer that uses proxystate and checks where a user is trying to acess any object, and change a said property. and if that is so, throw an 'custom' or made error instead of allowing action to take place. 


**Thursday Challenge Link:**

