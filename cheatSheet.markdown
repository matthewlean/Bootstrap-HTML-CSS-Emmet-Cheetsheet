# Bootstrap, HTML, CSS & Emmet Cheetsheet
Bootstrap Docs : [https://getbootstrap.com/docs/4.3/getting-started/introduction/](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

Emmet Docs: [https://docs.emmet.io/cheat-sheet/](https://docs.emmet.io/cheat-sheet/).

A quick guide on emmet useage with the bootstrap grid

## Bootstrap 4 
One Column Centered Grid
```
.row.justify-content-center>.col-md-6

<div class="row justify-content-center">
    <div class="col-md-6"></div>
</div>
```

Two Column Grid
```
.row>.col-md-6*2

<div class="row">
    <div class="col-md-6"></div>
    <div class="col-md-6"></div>
</div>
```

Three Column Grid
```
.row>.col-md-6*2

<div class="row">
    <div class="col-md-6"></div>
    <div class="col-md-6"></div>
</div>
```

Image in first column
```
.row>.col-md-6>img

<div class="row">
    <div class="col-md-6">
        <img src="/link-to-image" alt="alt tag">
    </div>
    <div class="col-md-6">
        <!-- content -->
    </div>
</div>
```

Table

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

Buttons

