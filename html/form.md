# HMTL Form
We normally used HTML Form for website's registration, login, sign up, and so on.  
**Form actions** (e.g. Login Action, Signup Action) are connected to **server side** processing.  
**Handle user input information.**

<!-- ## Form Sample
![Instagram](/images/LoginInstagram.png) -->

## Form Element
```html
<body>
    <form>
        <!-- Form inside elements -->
    </form>
</body>
```

## Form's member elements
- [`<input>`](#input-type)
- [`<label>`](#label-element)
- [`<select> <option>`](#dropdown-selection)
- [`<textarea>`](#textarea-element)
- etc.

### Input Type
- [text](#text-field-element)
- [password](#password-text-field-element)
- [date](#date-element)
- [radio](#radio-element)
- [checkbox](#checkbox-element)
- [submit](#submit-button-element)

#### Text Field Element
```html
<body>
    <form>
        <lable for="idUserName">User Name</lable>
        <input type="text" id="idUserName" name="userName" placeholder="Enter your user name">
    </form>
</body>
```

#### Password Text Field Element
```html
<body>
    <form>
        <lable for="idPassword">Password</lable>
        <input type="password" id="idPassword" name="password" placeholder="Enter your password">
    </form>
</body>
```

#### Date Element
```html
<body>
    <form>
        <lable for="idDOB">Date Of Birth</lable>
        <input type="date" id="idDOB" name="DOB">
    </form>
</body>
```

#### Radio Element
```html
<body>
    <form>
        <p>Gender:</p>
        <lable for="rdoMale">Male</lable>
        <input type="radio" id="rdoMale" name="gender">
        
        <lable for="rdoFemale">Female</lable>
        <input type="radio" id="rdoFemale" name="gender">
    </form>
</body>
```

#### CheckBox Element
```html
<body>
    <form>
        <p>Languages:</p>
        <lable for="chkHtml">HTML</lable>
        <input type="checkbox" id="chkHtml" name="langaugeOne">
        
        <lable for="chkCss">CSS</lable>
        <input type="checkbox" id="chkCss" name="languageTwo">
    </form>
</body>
```

#### Submit Button Element
```html
<body>
    <form action="" method="">
        ....
        ....
        <!-- submit button make form action -->
        <input type="submit" value="Login">
    </form>
</body>
```

### Label Element
The **`<label>`** HTML element represents a caption for an item in a user interface.

### Dropdown Selection
Default select option will show first option.  
If you'd like to change default selection add **selected** attribute on option.
```html
<body>
    <form action="" method="">
        
        <label for="idSelectCountry">Select Country</label>
        <select name="selectCountry" id="idSelectCountry">
            <option>Puerto Rico</option>
            <option>Nepal</option>
            <option>Vietnem</option>
            <option>Myanmar</option>
        </select>
        
    </form>
</body>
```

### TextArea Element
```html
<body>
    <form>
        <p>Write something</p>
        <textarea name="comment" rows="10" cols="60" placeholder="e.g. My hobby is driving."></textarea>
    </form>
</body>
```
