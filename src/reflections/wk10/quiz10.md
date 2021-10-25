# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace is the name of the application and on bringing muiltiple classes onto the same page application. But keeping it orginaized.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A struct is a class to create objects, or to set an element to a re-useable property.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
to add Abstract is to make it an instance, want it to return nothing it's void.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
You can access the START() function because it's public in an instance of Car because the car is abstract.
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
String in the exapmle is what it's returning.
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Preventing the user from seeing the avaliable private function in the abstracted version.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
To have a virtual can be benifitial, because it provides the needed details 
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public
private
internal
abtract
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
if something is private it too can only be accessed within the class.
```