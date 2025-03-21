# Task Name - Create Responsive Grid Layout

- Create Grid Layout using a Grid element and make it reponsive based on device type.

# Task Performed

- Create a gallery type image displaying container at 3x3 matrix and added a set of images. Then in desktop view 3 items per row is displayed and in mobile view 1 item per row is displayed.

# Elements Used

- `display:grid` - To display the container elements in rows and columns format based on website layout.
- `grid-direction:row` - To display the container elements in row format.
- `grid-direction:column` - To display the container elements in column format.
- `grid-template-columns:repeat(3,1fr)` - To display the container elements as 3 items per row.
- `gap` - To add a gap between the container elements.

# Grid Layout CSS Code

```
.grid-layout {
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    justify-content: center; 
    gap: 10px;
    margin: 10px;
}
```