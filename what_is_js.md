### What is Javascript
JavaScript (JS) is a lightweight interpreted or just-in-time compiled programming language with first-class functions. 
<br/>
JavaScript is a prototype-based, multi-paradigm, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

#### first class functions
A function is treated like a variable.

```javascript
const foo = function() {
   console.log("foobar");
}
// Invoke it using the variable
foo();
```

#### Prototype-based programming
Prototype-based programming is a style of object-oriented programming in which classes are not explicitly defined, but rather derived by adding properties and methods to an instance of another class.
<br/>

[[Prototype]]<br/>

<img src="https://javascript.info/article/prototype-inheritance/object-prototype-empty.png" alt="prototypr"/><br/>

In JavaScript, objects have a special hidden property [[Prototype]] (as named in the specification), that is either null or references another object. That object is called “a prototype”:<br/>
One way of using it by ```__proto__```.

```javascript
let animal = {
  eats: true
};
let rabbit = {
  jumps: true
};

rabbit.__proto__ = animal;
```

### A simple javascript program
```html
<html>
<head>
	<title>My First JavaScript code!!!</title>
	<script type="text/javascript">
		alert("Hello World!");
	</script>
</head>
	<body>
	</body>
</html>
```

### What we can do with javascript
Well you can pretty do anything with javascript nowadays.
serverside programming, client side programming , Robotics and Iot, Machine Learning, Video games, desktop app
