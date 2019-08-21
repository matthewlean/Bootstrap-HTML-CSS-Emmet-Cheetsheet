# Bootstrap, HTML, CSS & Emmet Cheatsheet
Bootstrap Docs : [https://getbootstrap.com/docs/4.3/getting-started/introduction/](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

Emmet Docs: [https://docs.emmet.io/cheat-sheet/](https://docs.emmet.io/cheat-sheet/).

A quick guide on emmet useage with the bootstrap grid

## Bootstrap 4 

### One Column Centered Grid
```
.row.justify-content-center>.col-md-6

<div class="row justify-content-center">
    <div class="col-md-6">
        <!-- Content Here -->
    </div>
</div>
```

### Two Column Grid
```
.row>.col-md-6*2

<div class="row">
    <div class="col-md-6">
        <!-- Content Here -->
    </div>
    <div class="col-md-6">
        <!-- Content Here -->
    </div>
</div>
```

### Three Column Grid
```
.row>.col-md-4*3

<div class="row">
    <div class="col-md-4">
        <!-- Content Here -->
    </div>
    <div class="col-md-4">
        <!-- Content Here -->
    </div>
    <div class="col-md-4">
        <!-- Content Here -->
    </div>
</div>
```

### Image in first column
```
.row>.col-md-6>img

<div class="row">
    <div class="col-md-6">
        <img src="/link-to-image" alt="alt tag">
    </div>
    <div class="col-md-6">
        <!-- Content Here -->
    </div>
</div>
```
---

### Media Queries

Breakpoints

Extra small < 544px

Small ≥ 544px

Medium ≥ 768px

Large ≥ 992px

Extra large ≥ 1200px

---

### Typography


Left aligned text
```
.text-left 
```
Center aligned text
```
.text-center
```
Right aligned text
```
.text-right
```
Lowercase text
```
.text-lowercause 
```
Uppercase text
```
.text-uppercase 
```
Capitalized text
```
.text-capitalize 
```
---

### Table

|Name|Favourite Color|
| - |:--:|
| Bob | Yellow |
| Michelle | Purple |

```
table>(tr>th+th)*3 

<table>
    <tr>
        <th>Name</th>
        <th>Favorite Color</th>
    </tr>
    <tr>
        <td>Bob</td>
        <td>Yellow</td>
    </tr>
    <tr>
        <td>Michelle</td>
        <td>Purple</td>
    </tr>
</table>
```
---

### Buttons

.btn needs to be added to all links because it adds padding and margin
```
a.btn 

<a href="" class="btn"></a>
```
```
a.btn.primary-btn

<a href="" class="btn primary-btn"></a>
```

---

## CSS

### Margin and Padding
#### Margin
```
margin:10px 8px 6px 4px;
```
Is the same as
```
margin-top:10px;
margin-right: 8px;
margin-bottom: 6px;
margin-left: 4px;
```

#### Padding
```
padding:10px 8px 6px 4px;
```
Is the same as
```
padding-top:10px;
padding-right: 8px;
padding-bottom: 6px;
padding-left: 4px;
```
---
### Hover 
You have a class and you want to add a hover effect to it... you use :hover
ie: we have a ahref with the class of .btn-custom
we want to add an effect to change it to background-colour: #000 ( black ) on hover
we use the following css..
The button will display normally as white (#fff) but when the mouse hovers over it black (#000)

```
.btn-custom{
    background-color: #fff;
}

.btn-custom:hover{
    background-color: #000;
}
```
---

### Border
3px solid white border
```
border: 3px solid #fff;
```

---

