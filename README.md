# my_flex_notes

### To display any text in flex
```html
display: flex; <!-- stacks all the text side-by-side i.e, places like a row -->
```

### To convert a row into a coloumn
```html
flex-direction: column;<!-- you may also use: coloumn-reverse or row-reverse in place of column-->
```

### To wrap the text onto multiple lines
```html
flex-wrap: wrap;
```

### To distribute the free space left after displaying flex
```html
justify-content: flex-start; <!-- you may also use: flex-end and center in place of flex-start-->
```

### Difining the order of arrival of content
```html
order: 1; <!-- Any integer can be placed here
defult value is 0
this property must be inside the flex items-->
```

### To adjust the size of flex items if there is more space than required
```html
flex-grow: 2<!-- Takes up 2 times of the orginal space required--> 
<!--  any integer is accepted. No negetive numbers-->
```

### To adjust the size of flex items if there is not enough space
```html
flex-shrink: 
