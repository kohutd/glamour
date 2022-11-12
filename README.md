# Glamour

A glamour CSS naming technique.

## Elements

Syntax:

```css
.prefix-element {}
```

Examples:

```css
.ui-button {}

.ui-card {}
.ui-card-title {}
```

## Modifiers

Syntax:

```css
.prefix-element.modifier {}
```

Examples:

```
.ui-button.red {}
.ui-button.outline {}
```

## Example

Button:

```css
.ui-button {}
.ui-button.red {}
.ui-button.outline {}
```

```html
<button class"ui-button">
  Save
</button>

<button class"ui-button outline">
  Disable
</button>

<button class"ui-button red">
  Delete
</button>

<button class"ui-button red outline">
  Remove
</button>
```
