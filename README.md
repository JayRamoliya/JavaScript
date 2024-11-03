# JavaScript
JavaScript Beginner To End ✔

## JavaScript Crash Course_ Master the Basics in One Video_ Ignite Your Front-End Mastery Series


1. Basic ✅

* word (name,any char or word) vs keyword (new,array,let,const...)
* variable (store any some data) and constants (store any not changeble data)
* var const let

```javascript
var name="jay ramoliya"
console.log(name);

const PI = 3.14 // not change
console.log(PI);

let age=18
console.log(age);
```


2. Hoisting ✅

* (variable and function are hoisted which means there declaration is moved on the top of code)
* undefined and not-undefined

```javascript
console.log(first); // not a error show undefined
var first="pela use kari sakay"
console.log(first);
```


3. Type in JS ✅

* primitive -> num,str,null,bool,undefined
* reference -> (),{},[]
* aisi koi bhi value jisko copy karne par real copy nahi hota, balki us main value ka reference pass hojaata hai, use hum reference value kahte hai, aur jiska copy karne par real copy ho jaaye wo value primitive type value hoti hai


4. Conditionals (if else else-if) ✅

```javascript
if(1==1){
    // code
}
else if(1==1){
    // code
}
else{
    // code
}
```


5. Loops (for,while) ✅

```javascript
for(var i=0;i<4;i++){
    console.log(i);
}

while(age<20){
    console.log(age);
    age++;
}
```


6. Functions ✅ (after some time code run,reuse code, repeat code)

```javascript
function fname(){
    console.log('my name is jay');
}
function village(){
    console.log('my village name is rajkot');
}
fname()
village()
```


7. Params (parameter), Arguments (value) ✅

```javascript
function sum(a,b){
    console.log(a+b);
}
sum(2,3)
```


8. Arrays ✅

* push pop shift unshift

```javascript
var a=[1,2,3,4,5,'jay','manav',false]

a.push('push')
console.log(a);

a.pop()
console.log(a);

a.unshift('start')
console.log(a);

a.shift()
console.log(a);

a.splice(2,2)
console.log(a);
```


9. Objects ✅

```javascript
var obj = {} //blank obj
var obj = {
    age:23,
    name:'jay',
    fun:function fun(){console.log('fun');}
} 
console.log(obj.age);
```

10. Props v/s Methods ✅

```javascript
var obj = {} //blank obj
var obj = {
    age:23,
    name:'jay',
    fun:function fun(){console.log('fun');}
} 
console.log(obj.age);
console.log(obj.fun);

// updating object props
obj.age=133
console.log(obj);
```


## JavaScript Advance Crash Course_ Level Up Your Coding Skills_ Accelerate Your Front-End Mastery_

1. The Difference ✅

* ES5 (var)
```javascript
a='ramoliya' ;   
console.log('ES5',typeof a,'value:',a );
// output: ES5 string value: ramoliya
```

* ES6 (let, const)
```javascript
// ES6 (let/const)
{
    let b ='ramoliya';
}   
console.log("ES6", typeof b," value:",b ) // b is not defined
// output: ES6 undefined value: undefined
```

* ES6 (let, const) both are use ES5 AND ES6
* var is function scoped while let & const are block scoped
* var adds itself to the window object
* window search in console
* let const does not add to the window

2. execution context (is a container where the function's code is executed and it's created whenever a function is called, it contains 3 things, variables, functions and environment.)

3. lexical environment (hota hai ek chart jisme ye likha hota hai ke apka particular function ki cheejo ko access kar sakta hai and kinko nahi, matlab ki it holds it's scope chain)

```javascript
function abcd(){
    var a=12;
    // b not use outside use def() 
    function def(){
        var b=13;
    }
}
```

4. How to Copy Reference Values ✅

* ... this is sprad operator

```javascript
console.log('sprad opetator');
var obj = {a: 4};
var copyobj={...obj}
copyobj.a=7890;
console.log(obj);
console.log(copyobj);

var a=[1,2,3,4,5]
var b=[...a]
b.pop()
console.log(a);
console.log(b);
```

5. Truthy v/s Falsy (convert value) ✅

* falsy value : false,null,undefiend,NaN (not a number),"", document.all
* truthy value : true," ",[],{}