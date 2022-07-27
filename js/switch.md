# Switch

**Switch** uses *param* to compare strict equality(===) with each *case*.  
If matches one of these *case*, **executes** inside *case*.  
If there is no matches, **executes** *default* case.

Example:
```javascript
let a = 1;
switch(a) { // a means switch's param
    case 1:
        console.log('Number One');
        break;
    case 2:
        console.log('Number Two');
        break;
}
```
The above program will output `Number One`.

## Switch checks strict equality (===)

Example:
```javascript
let a = 1;
switch(a) {
    case '1':
        console.log('String Type : value One');
        break;
    case 1:
        console.log('Number Type : value One');
        break;
}
```
The above program will output `Number Type : value One`.
Beacause **switch** checks strict equality (===).

## Switch Param Type

- Number
- String
- Boolean

### Number

Example: Integer Value
```javascript
let integerVar = 5;
switch(integerVar) {
    case 5:
        console.log('first case');
        break;
    case 10:
        console.log('second case');
        break;
}
```
The above program will output `first case`.  

Example: Float Value 
```javascript
let floatVar = 5.5;
switch(floatVar) {
    case 5:
        console.log('first case');
        break;
    case 5.5:
        console.log('second case');
        break;
    case 10:
        console.log('third case');
        break;
}
```
The above program will output `second case`.  

Example: Minus Value 
```javascript
let minusVar = -5.5;
switch(minusVar) {
    case 5:
        console.log('first case');
        break;
    case 5.5:
        console.log('second case');
        break;
    case -5.5:
        console.log('third case');
        break;
}
```
The above program will output `second case`.  

### String

Example:
```javascript
let strVar = 'Mon';
switch(strVar) {
    case 'Mon':
        console.log('Monday');
        break;
    case 'Tue':
        console.log('Tuesday');
        break;
    case 'Wed':
        console.log('Wednesday');
        break;
    case 'Thu':
        console.log('Thursday');
        break;
    case 'Fri':
        console.log('Friday');
        break;
}
```
The above program will output `Monday`.

### Boolean

Example:
```javascript
let booleanVar = true;

let numOne = 10;
let numTwo = '10';
switch(booleanVar) {
    case (numOne > numTwo):
        console.log('Num One is greater than Num Two');
        break;
    case (numOne < numTwo):
        console.log('Num One is less than Num Two');
        break;
    case (numOne === numTwo):
        console.log('Num One is equal(strict) to Num Two');
        break;
    case (numOne == numTwo):
        console.log('Num One is equal to Num Two');
        break;
}
```
The above program will output `Num One is equal to Num Two`.  

## Switch (default)

**default** case works when there is no matched case.
```javascript
let booleanVar = true;

let numOne = 10;
let numTwo = '10';
switch(booleanVar) {
    case (numOne > numTwo):
        console.log('Num One is greater than Num Two');
        break;
    case (numOne < numTwo):
        console.log('Num One is less than Num Two');
        break;
    case (numOne === numTwo):
        console.log('Num One is equal(strict) to Num Two');
        break;
    default:
        console.log('There is no matched case.');
        break;
}
```
The above program will output `There is no matched case.`.  
