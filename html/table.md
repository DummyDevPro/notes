# `<table>` Element
| Element | Usage       | Detail |
| ------- | ----------- | ------ |
| tr      | table row   | - |
| th      | table cell head | `th`'s content align center and text-bold |
| td      | table cell data | `td`'s content align left/start |
| thead   | table head  | `thead` defines its content will be table header role |
| tbody   | table body  | `tbody` defines its content will be table body role |
| tfooter   | table footer  | `tfooter` defines its content will be table footer role | 
| caption   | table caption  | - | 

## Simple HTML Table
```html
<body>
    <table border="1px" cellspacing="0">
        <caption>Student List</caption>
        <tr>
            <th>Name</th>
            <th>Country</th>
        </tr>
        <tr>
            <td>KUMAR</td>
            <td>Nepal</td>
        </tr>
        <tr>
            <td>ANGEL</td>
            <td>Puerto Rico</td>
        </tr>
        <tr>
            <td>PARIK</td>
            <td>Nepal</td>
        </tr>
    </table>
</body>
```
### Output
<body>
    <table border="1px" cellspacing="0">
        <caption>Student List</caption>
        <tr>
            <th>Name</th>
            <th>Country</th>
        </tr>
        <tr>
            <td>KUMAR</td>
            <td>Nepal</td>
        </tr>
        <tr>
            <td>ANGEL</td>
            <td>Puerto Rico</td>
        </tr>
        <tr>
            <td>PARIK</td>
            <td>Nepal</td>
        </tr>
    </table>
</body>

## Row merging & Column merging

```html
<body>
    <table border="1px" cellspacing="0">
        <tr>
            <th colspan="4">1</th>
        </tr>
        <tr>
            <th rowspan="2">2</th>
            <th rowspan="2">3</th>
            <th colspan="2">4</th>
        </tr>
        <tr>
            <th>5</th>
            <th>6</th>
        </tr>
        <tr>
            <th colspan="4">7</th>
        </tr>
    </table>
</body>
```
### Output
<body>
    <table border="1px" cellspacing="0">
        <tr>
            <th colspan="4">1</th>
        </tr>
        <tr>
            <th rowspan="2">2</th>
            <th rowspan="2">3</th>
            <th colspan="2">4</th>
        </tr>
        <tr>
            <th>5</th>
            <th>6</th>
        </tr>
        <tr>
            <th colspan="4">7</th>
        </tr>
    </table>
</body>

