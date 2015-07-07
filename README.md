## Skeleton Font Awesome Buttons

Nice looking Font Awesome icon buttons for use with Skeleton. [Demo](http://nathancahill.github.io/skeleton-fontawesome-buttons/)

![](http://i.imgur.com/3jBJmB0.png)

### Usage

Include `skeleton-fontawesome-buttons.css` in your HTML:

```
<link rel="stylesheet" href="skeleton-fontawesome-buttons.css">
```

Add the `.button-icon` class to your buttons:

```
<a class="button button-icon">
    <i class="fa fa-cog"></i>
</a>
```

### Usage in a Table

Table cells are smaller than buttons, so there's a special case for using the `.button-icon` class in table cells:

```
<td>
    <a class="button button-icon">
        <i class="fa fa-cog"></i>
    </a>
</td>
```