# Home-Work 8

## Goal:

Flex box and Grid

## Technologies used:

- html
- css

## Open the website

To open the website, open the link [https://kvolchkov.github.io/full-stack-course/](https://kvolchkov.github.io/full-stack-course/)

## Details

### 1. Semantics

Semantic tags like `header`, `nav`, `main`, and `footer` are added to all pages

### 2. BEM-naming

The BEM-naming is added only to the `index.html` page. For example:

```html
<header class="header header--fixed"></header>
```

or

```html
<nav class="nav">
  <div class="container">
    <menu class="menu">
      <li class="nav__menu-item">
        <a class="nav__menu-link--disabled" target="_self" href="#">Home</a>
      </li>
    </menu>
  </div>
</nav>
```

### 3. Flex box:

The `flex` property is added to the `.menu` class with gaps between menu items.

```css
.menu {
  display: flex;
  flex-flow: row wrap;
  gap: 30px;
  min-width: 0;
  overflow-wrap: anywhere;
}
```

### 4. Grid items:

I added 9 grid items to the `index.html` page. Grid-items are displayed in 3 rows and 3 columns (9 elements in total). The style is applied to this element:

```css
.grid {
  display: grid;
  grid-template-columns: repeat(3, 2fr);
  gap: 5px;
}

.grid__cell {
  width: 100px;
  height: 100px;
  border: 1px solid #000;
  background-color: orange;
  box-sizing: border-box;
}
```

## Testing

Testing was done in 2 browsers:

- Chrome
- Safari

The testing shows that:

- Flex item is displayed correctly
- Grid is displayed correctly
- Styles are applied to both elements
