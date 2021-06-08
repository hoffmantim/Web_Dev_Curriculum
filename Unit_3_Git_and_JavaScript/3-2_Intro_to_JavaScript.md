# 3.2: Introduction to JavaScript

JavaScript is really the backbone of the modern web. JavaScript is run by the browser or on a backend server. If we want our websites and apps to have any kind of funcionality or interactivity, we'll need to use JavaScript.

### JavaScript vs. Python

Since we know a lot of programming basics in Python, picking up Javascript shouldn't be too tricky. We'll use the same things like variables, lists, functions, loops, etc. However, much of the __syntax__ will be different.

##### Variables

| Python    |   JavaScript  |
|----------- |---------------|
| `num = 42`  | `var num = 42;`   |
| `name = 'John`  |` var name = 'John';`|

<br/>  
##### Printing / Logging to the Console

| Python    |   JavaScript  |
|----------- |---------------|
| `print('this is a string')` | `console.log('this is a string');`|
| `print('Hello' + name)`     | `console.log('Hello' + name);`|

<br/> 
##### Lists (arrays)

| Python    |   JavaScript  |
|----------- |---------------|
|`fruits = ['apple', 'orange', 'banana']` | `var fruits = ['apple', 'orange', 'banana'];`|
| `fruits[1]` | `fruits[1]` |
| `fruits.length()` | `fruits.length` |
| `for fruit in fruits:` | `for (var i = 0; i < fruits.length; i++):` |

In JavaScript, we can still use a lot of list (usually called __arrays__ in JavaScript) functions like `push()` which is similar to `append()`.

<br/> 
##### Booleans and Conditionals

<table>
<tr>
<th>Python</th><th>JavaScript</th>
</tr>
<tr>
<td>

``` 
if x > 0:
    print('positive')
elif x == 0:
    print('zero')
else:
    print('negative')
```
    
</td>
<td>

```
if (x > 0) {
    console.log('positive');
} elif (x === 0) {
    console.log('zero');
} else {
    console.log('negative');
};
```

</td>
</tr>
</table>

<br/> 
##### Loops

<table>
<tr><th>Python</th><th>JavaScript</th></tr>
<tr>
<td>

```
for fruit in fruits:
    print(fruit)

i = 0

while i < 10:
    print(f'The number is {i}')
    i++
```

</td>
<td>

```
for (var i = 0; i < fruits.length; i++) {
    console.log(fruits[i]);
};

var i = 0

while (i < 10) {
    console.log("The number is" + i);
    i++;
};
```
</td>
</tr>


</table>