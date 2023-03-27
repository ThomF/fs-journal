# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
-Namespace is the scope of objects
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
-classes are reference types, structs are values
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
-string
return Ok(message)
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
virtual
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
the value type that is being returned 
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract is used for anything that isnt an object. Its used to show its a string .
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
the virtual is there to be stated as a method modifier that can be overridden.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
anything within the same class or struct.
```