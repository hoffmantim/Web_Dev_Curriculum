# 1.4 Building our Personal Site: Tables and Lists

### HTML Tables

HTML tables consist of rows and columns like any other data table.

| Name       | Grade   | ID#     |
| ---------- | ------- | ------- |
| John Smith | 11      | A1B2    |
| Jane done  | 12      | D3F4    |


### Building a Table

A table is defined with the `<table>` tag. Each __row__ is defined with the `<tr>` tag. Each __cell_ is defined with the `<td>` tag.

You can specify the first row of elements as a __header__ (to be formatted differently) by using the `<th>` tag for each cell instead of `<td>`.

```
  <table>
    <tr>
      <th>Name</th>
      <th>Grade</th>
      <th>ID#</th>
    </tr>
    <tr>
      <td>John Smith</td>
      <td>11</td>
      <td>A1B2</td>
    </tr>
    <tr>
      <td>Jane Doe</td>
      <td>12</td>
      <td>D3F4</td>
    </tr>
  </table>
```

### HTML Lists

There are two kinds of lists we can use: __ordered__ and __unordered__.

* Ordered lists are numbered
* Unordered lists use bullets

#### Unordered Lists

Unordered lists are defined by the `<ul>` tag. Ordered lists are defined by the `<ol>` tag. Each item in the list must be wrapped in an `<li>` tag.

```
  <ul>
    <li>First Item</li>
    <li>Second Item</li>
  </ul>
```
### Level Up Your Page

1. Reorganize the top elements on your site using a table.
2. Your table will have only one row, with two cells:
  * The first cell will contain your image
  * The second cell will contain your other header elements (title, position, etc.)
3. Change those header items from `<p>` tags to an __unordered list__.
4. Change your Employment History section into a table with a column for dates, position, and employer and a row for each job you list.
5. In your Skills section, replace the `<p>` elements with an __ordered list__.
