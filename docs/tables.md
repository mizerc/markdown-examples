# TABLES

## Markdown table

### Example 1

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

```
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |
```

### Example 2

| Command      | Description                                        |
| ------------ | -------------------------------------------------- |
| `git status` | List all _new or modified_ files                   |
| `git diff`   | Show file differences that **haven't been** staged |

```
| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |
```

### Example 3

| Name     | Character |
| -------- | --------- |
| Backtick | `         |
| Pipe     | \|        |

```
| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |
```

## HTML table

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

### rowspan

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

### colspan

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