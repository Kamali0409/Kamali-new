<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <h1>Heading 1</h1>
  <p>This is a paragraph.</p>
  <a href="https://www.example.com">Visit Example.com</a>
  <img src="image.jpg" alt="Image description">
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
  </ul>
  <table>
    <tr>
      <th>Column 1</th>
      <th>Column 2</th>
    </tr>
    <tr>
      <td>Cell 1</td>
      <td>Cell 2</td>
    </tr>
  </table>
</body>
</html>
```

CSS (in style.css file):

```
body {
  background-color: #f2f2f2;
  font-family: Arial, sans-serif;
}

h1 {
  color: #00698f;
}

p {
  color: #666666;
}

a {
  text-decoration: none;
  color: #00698f;
}

a:hover {
  color: #0097c5;
}

img {
  width: 100%;
  height: auto;
  margin: 20px 0;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

li {
  margin-bottom: 10px;
}

table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  border: 1px solid #ddd;
  padding: 10px;
  text-align: left;
}

th {
  background-color: #f0f0f0;
}
