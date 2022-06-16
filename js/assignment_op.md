# JavaScript

**JavaScript** is a programming language that can manipulate HTML document dynamically.  
It can also communicate with server-side.

## JS Assignment Operators

| Operator | Description  |
| :----: | :-----------:  |
|  =   | Equal Assign |

### Example
Assign value `10` to variable `x`.
```javascript
<script>
    let x = 10;
<script>
```

| Operator | Description  |
| :----: | :-----------:  |
|  +=  | **right-side value** makes addition to **left-side variable** and the result re-asigns to **left-side variable** |

### Example
Assign value `10` to variable `x`.  
And, add `5` to variable `x`.
```javascript
<script>
    let x = 10;
    x += 5;
    
    /** --- Thinking ---
    * x += 5 (same as) x = x + 5
    *
    * x = x + 5
    *   = 10 + 5
    *   = 15
    */
    
    // The outout will be 15.
    console.log(x);
<script>
```

| Operator | Description  |
| :----: | :-----------:  |
|  -=  | **right-side value** makes subtraction to **left-side variable** and the result re-asigns to **left-side variable** |

### Example
Assign value `25` to variable `y`.  
And, subtract `5` to variable `y`.
```javascript
<script>
    let y = 25;
    y -= 5;
    
    /** --- Thinking ---
    * y -= 5 (same as) y = y - 5
    *
    * y = y - 5
    *   = 25 - 5
    *   = 20
    */
    
    // The outout will be 20.
    console.log(y);
<script>
```

| Operator | Description  |
| :----: | :-----------:  |
|  \*=  | **right-side value** makes multiplication to **left-side variable** and the result re-asigns to **left-side variable** |

### Example
Assign value `20` to variable `y`.  
And, multiply `4` to variable `y`.
```javascript
<script>
    let y = 20;
    y *= 4;
    
    /** --- Thinking ---
    * y *= 4 (same as) y = y * 4
    *
    * y = y * 5
    *   = 20 * 4
    *   = 80
    */
    
    // The outout will be 80.
    console.log(y);
<script>
```

| Operator | Description  |
| :----: | :-----------:  |
|  \/=  | **right-side value** makes division to **left-side variable** and the result re-asigns to **left-side variable** |

### Example
Assign value `25` to variable `y`.  
And, divide `5` to variable `y`.
```javascript
<script>
    let y = 25;
    y /= 5;
    
    /** --- Thinking ---
    * y /= 5 (same as) y = y / 5
    *
    * y = y / 5
    *   = 25 / 5
    *   = 5
    */
    
    // The outout will be 5.
    console.log(y);
<script>
```

| Operator | Description  |
| :----: | :-----------:  |
|  \%=  | **right-side value** makes division to **left-side variable** and get the **remainder** that is re-asigned to **left-side variable** |

### Example
Assign value `10` to variable `y`.  
And, divide `3` to variable `y`.  
And then the remainder 1 will get.
```javascript
<script>
    let y = 10;
    y %= 3;
    
    /** --- Thinking ---
    * y %= 3 (same as) y = y % 3
    *
    * y = y % 3
    *   = 10 % 3
    *   = 1
    */
    
    // The outout will be 1.
    console.log(y);
<script>
```
