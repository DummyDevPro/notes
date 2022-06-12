# <table> Element

## Simple HTML Table
```html
<body>
    <table border="1px" cellspacing="0">
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

