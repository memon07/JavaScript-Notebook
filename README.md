<img height="150" width="150" src="http://2ality.com/2011/10/logo-js/js.jpg" alt="js logo"/><br/>
# JavaScript Notebook
A collection of JavaScript knowledge



* [What is JavaScript](what_is_js.md)
* [Let Vs Var](let%20vs%20var.md)

## Useful resources
[How browser works](https://lyamkin.com/blog/what-are-web-standards-and-how-does-web-browser-work/)<br/>
[JavaScript under the hood with v8](https://www.freecodecamp.org/news/javascript-under-the-hood-v8/)<br/>
[React Patterns](https://reactpatterns.com/)</br>


#### 1. Data Types in JS
```
Int
String
Boolean
Symbol
Null
Undefined
Object
```

```
Symbol
eg : const mySymb = Symbol()
Once you create a symbol, its value is kept private and for internal use.
You can access all the symbols assigned to an object using the Object.getOwnPropertySymbols() method.
```

#### 2. JavaScript is a case sensitive language.

#### 3. There are two scopes of variable in JavaScript – local and global

#### 4. 'this' keyword
```
In The JavaScript this keyword refers to the object it belongs to. 
This has different values depending on where it is used. In a method, 
this refers to the owner object and, in a function, 
this refers to the global object.
```

#### 5. Some built-in methods and the values returned by them

```
CharAt()      It returns the character at the specified index.
Concat()      It joins two or more strings.
forEach()     It calls a function for each element in the array.
indexOf()     It returns the index within the calling String object of the first occurrence of the 
              specified value.
length()      It returns the length of the string.
pop()         It removes the last element from an array and returns that element.
push()        It adds one or more elements to the end of an array and returns the new length of the array.
reverse()     It reverses the order of the elements of an array.
anchor()      Creates an HTML anchor to be used as a hypertext target
ceil()        returns the smallest integer that is greater than or equal to the given number
concat()      Combines two strings and returns the newer string
constructor() Returns the function that created the corresponding instance of the object
Date()        Returns the present date and time
Date.parse()  Parses a string representation of a date and time, and then returns the internal 
              millisecond representation for the same
exec()        Searches for a match in the string parameter
filter()      Creates a new array with all the elements of the array for which the filtering 
              function returns true
fontcolor()   Displays a string in the specified color
link()        Creates an HTML hypertext link that requests another URL
match()       Used for matching a regular expression against a string
reduce()      Applies a function simultaneously for two values of the array in order to reduce them 
              to a single value
round()       Rounds off the value of the given number to the nearest integer and returns the same
slice()       Extracts a certain section of a string and returns the remaining string
some()        returns true if at least one element of the array satisfies the provided testing function
sup()         Displays a string as a superscript
toSource()    Returns a string containing the source of the Boolean object
toUpperCase() Converts a text to uppercase
valueOf()     Returns the primitive value of the specified object
localeCompare()  Returns a number that indicates whether a reference string comes before, after, or 
                 is the same as the given string in the sort order
toLocaleString() Return a string value of the current number in a format that depends on the 
                 browser’s locale settings


```

#### 6. different types of Error Name values in JavaScript
```
Eval Error        Thrown when coming across an error in eval() (Newer JS releases don’t have it)
Range Error       Generated when a number outside the specified range is used
Reference Error   It comes into play when an undeclared variable is used
Syntax Error      When the incorrect syntax is used, we get this error
Type Error        This error is thrown when a value outside the range of data types is tried to be used
URI Error         Generated due to the use of illegal characters

```

#### 7. event bubbling in JavaScript
```
There are two ways for accomplishing event propagation and the order in which an event is 
received in the HTML DOM API.

These are Event Bubbling and Event Capturing. In the former, the event is directed towards 
its intended target, whereas the event goes down to the element in the latter.

Event Capturing – Also known as trickling, Event Capturing is rarely used. 
                  The process starts with the outermost element capturing the event and then propagating the 
                  same to the innermost element.

Event Bubbling –  In this process, the event gets handled by the innermost element first and 
                  then propagated to the outermost element.

Event bubbling is a way of event propagation in the HTML DOM API, when an event occurs in an element 
inside another element, and both elements have registered a handle for that event. With bubbling, the event 
is first captured and handled by the innermost element and then propagated to outer elements. The execution 
starts from that event and goes to its parent element. Then the execution passes to its parent element 
and so on till the body element.
```

#### 8. call() vs apply() function
```
Function.prototype.call()
Function.prototype.apply()
Function.prototype.bind()

the syntax of apply() function is almost identical to that of call(), the fundamental difference is that 
call() accepts an argument list, while apply() accepts a single array of arguments
```

#### 9. Bindings
```
Implicit binding
Explicit binding
new Binding
window binding

In implicit 'this' refers to the object that is left side of the dot
eg:
var obj = {
  name : 'shoyeb',
  getName : function(){
    console.log(this.name);
  }
}

obj.getName(); // shoyeb 
```

#### 10. React LifeCycle 16.4 above
```
mounting
-----------
constructor
render
dom&ref
componentDidMount


updating
--------------
getDerivedStatesFromProps
shouldComponentUpdate
render
getSnapShotbeforeUpdate
dom&ref
componentDidUpdate


unmount
-----------
componentWillUnmount
```

#### 11. React Hook list
```
Hooks
-------
useState()
useEffect()
useReducer()
useContext()
useCallback()
useMemo()
useRef()
useImperativeHandle()
useLayoutEffect()
useDebugValue()
```

#### 12. Five Important Rules for Hooks
```
* Never call Hooks from inside a loop, condition or nested function
* Hooks should sit at the top-level of your component
* Only call Hooks from React functional components
* Never call a Hook from a regular function
* Hooks can call other Hooks
```
