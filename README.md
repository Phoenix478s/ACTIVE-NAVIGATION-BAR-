# Seth-Designs

This is a simple responsive navigation bar project created using HTML, CSS, and JavaScript. The navigation bar has a toggle button that shows and hides the menu items when clicked. It also highlights the active menu item when selected.

## How to Use

1. Clone the repository or download the zip file.
2. Open `index.html` in your preferred web browser.
3. Click on the toggle button to show or hide the menu items.
4. Click on any menu item to highlight it as the active item.

## Dependencies

This project uses Ionicons for the toggle and social icons. The required CSS and JS files are loaded from the following URLs:

```html
<script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>
```

## Customization

You can customize the navigation bar by modifying the CSS variables in the `style.css` file. Here are some of the variables you can change:

```css
:root {
    /* colors */
    --first-color: #3664F4; /* Change this to your desired color */
    --dark-color: #070D1F;
    --dark-color-alt: #282B3A;
    --white-color: #E6E7E9;

    /* font and typography */
    --body-font: 'Poppins', sans-serif;
    --normal-font-size: .938rem;
    --small-font-size: .813rem;

    /* index */
    --z-fixed: 100;
}
```

You can also modify the menu items and their links by editing the HTML in `index.html`.

```html
<ul class="nav_list">
    <li class="nav_item"><a href="#" class="nav_link active">Home</a></li>
    <li class="nav_item"><a href="#" class="nav_link">About</a></li>
    <li class="nav_item"><a href="#" class="nav_link">Experience</a></li>
    <li class="nav_item"><a href="#" class="nav_link">About Dev</a></li>
    <li class="nav_item"><a href="#" class="nav_link">Contact Dev</a></li>
</ul>
```

Feel free to modify and customize the project according to your needs.

## Author

This project was created by PHOENIX (Daleni Seth)
