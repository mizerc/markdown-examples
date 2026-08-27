# Tables

## Markdown table

### Example 1

Result:

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

Syntax:

```
| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |
```

### Example 2

Result:

| Command      | Description                                        |
| ------------ | -------------------------------------------------- |
| `git status` | List all _new or modified_ files                   |
| `git diff`   | Show file differences that **haven't been** staged |

Syntax:

```
| Command      | Description                                        |
| ------------ | -------------------------------------------------- |
| `git status` | List all _new or modified_ files                   |
| `git diff`   | Show file differences that **haven't been** staged |
```

### Example 3

Result:

| Name     | Character |
| -------- | --------- |
| Backtick | `         |
| Pipe     | \|        |

Syntax:

```
| Name     | Character |
| -------- | --------- |
| Backtick | `         |
| Pipe     | \|        |
```

## HTML table

Result:

<table>
  <tr>
    <th>col 1</th>
    <th>col 2</th>
    <th>col 3</th>
  </tr>
  <tr>
    <td>row 1 - col 1</td>
    <td>row 1 - col 2</td>
    <td>row 1 - col 3</td>
  </tr>
</table>

Syntax:

```html
<table>
  <tr>
    <th>col 1</th>
    <th>col 2</th>
    <th>col 3</th>
  </tr>
  <tr>
    <td>row 1 - col 1</td>
    <td>row 1 - col 2</td>
    <td>row 1 - col 3</td>
  </tr>
</table>
```

### HTML Table Rowspan

<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td>row 1 - column 2</td>
    <td rowspan="2" align="center">row 1 & 2 - column 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
  </tr>
</table>

### HTML Table Colspan

<table>
  <tr>
    <th>column 1</th>
    <th>column 2</th>
    <th>column 3</th>
  </tr>
  <tr>
    <td>row 1 - column 1</td>
    <td colspan="2" align="center">row 1 - column 2 & 3</td>
  </tr>
  <tr>
    <td>row 2 - column 1</td>
    <td>row 2 - column 2</td>
    <td>row 2 - column 3</td>
  </tr>
</table>
