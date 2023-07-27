# Email newsletter
This project has been built following Drew Ryan [tutorial](https://www.youtube.com/watch?v=RDfslONy404).

It is not optimized for all email clients, such as Outlook, as it doesn't include ghost tables and conditional statements.

### Live Site:

<!-- Check out the project Live Site -->

### Notes:
The following are personal notes for educational purposes only:
#### Line 29:
```
.wrapper {
			width: 100%;
			table-layout: fixed;
		}
```
- Setting table-layout: fixed; in the ".wrapper" class allows you to have a fixed layout for the table and ensures that the table's width follows the width of its cells, preventing the table from adjusting its size based on the content. 
- When you set table-layout: fixed;, it means that the browser will use the width specified in the table's <th> or <td> elements. The table will be displayed with these fixed column widths, and any extra content that does not fit within the column width will be truncated or wrapped based on the content overflow properties.