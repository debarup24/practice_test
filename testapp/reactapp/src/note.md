1. box-sizing: border-box;

--> it means : fit everything inside the given width.

```div {
  width: 200px;
  padding: 20px;
  border: 5px solid;
}
// Actual width becomes: 200 + 20 + 20 + 5 + 5 = 250px (without border-box)
// With border-box : Total width = content + padding + border (all inside 200px)
```
