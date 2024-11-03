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