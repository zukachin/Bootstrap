# Bootstrap
# Bootstrap Basics

## Container and Container Fluids

- `.container`: Sets the margin spacing. You can use `class="container well"` to display a box, or `class="container-fluid well"` to center and stretch across the page.

## Grid System

- `.row`: Creates a column-like space. Use `<div class="col-md-6">Box-2</div>` for responsive column sizing on webpages.

## Text Properties

- Default text colors: `text-primary/success/info/warning/danger`
- Background color for text: `bg-primary/success/info/warning/danger`
- `<i class="lead">`: Displays bigger and darker text
- `<i class="small">`: Displays smaller and less dark text
- Text alignment: `class="text-left/right/center/justify"`
- Text case: `class="text-uppercase/lowercase/capitalize"`
- Removing bullets: `class="list-unstyled"`
- Displaying list items horizontally: `class="list-inline"`

## Bootstrap Tables

```html
<table class="table">
    <thead>
        <tr>
            <th>Firstname</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>John</td>
        </tr>
    </tbody>
</table>
```

## Images in Bootstrap

Create a row and col div inside that create:
```html
<div class="row">
    <div class="col">
        <img class="img-responsive" src="" alt="">
    </div>
</div>
```

## Button in Bootstrap

Create a row and col div and use a button. The button type can be either "button" or "submit":

```html
<div class="row">
    <div class="col">
        <button type="button">Basic</button>
        <button type="button" class="btn btn-default">Basic</button> <!-- Colored button -->
    </div>
</div>
```
You can customize the button in the following ways:

- Change the size of the button by adding classes:
  - `btn-xs`: Extra small size
  - `btn-sm`: Small size
  - `btn-lg`: Large size

- To make the button occupy the entire space, use the `btn-block` class.

- Enable state: Add the `active` class to the button.

- Disable state: Add the `disabled` attribute to the button.

To create a button with a link, use the `<a>` tag with the `btn` and `btn-default` classes:

```html
<a href="#" class="btn btn-default">Button</a>


