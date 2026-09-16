# Mhlongo Dzonga Fresh Bakery Website 
A responsive bakery website for a local bakery in Tzaneen, Limpopo. Baked fresh daily since 5AM everyday. This is a student project for WEB DEV module. 
## Features 
- 5 Fully Linked Pages: Home, About, Menu, Services, Contact 
- 6 Different Products on Menu page using 5 different images (no repeats) 
- Buyer Order Form on Menu page - captures Name, Product, Quantity 
- Order Now buttons auto-fill the order form 
- Fully Responsive - works on Desktop, Tablet and Mobile 
- Uses CSS Grid and Flexbox 
- Media queries, breakpoints, relative units, hover/focus/active effects 
- Images resize appropriately and do not overflow the page 
## Pages Structure 

- `index.html` - Home page with hero and 3 best sellers 
- `about.html` - Story of the bakery 
- `menu.html` - 6 products + Buyer Order Form (Name, What they want, How many) 
- `services.html` - Catering and baking services 
- `contact.html` - Location and contact details 
- `style.css` - All styling, grid, flexbox, responsive 
- `images/` - bread.jpg, biscuits.jpg, mango.jpg, about.jpg, bg.jpg + screenshots 
## Technologies Used 
- HTML5 
- CSS3 
- **Desktop Layout Requirements:** 
    - Flexbox (for nav and header) 
    - CSS Grid (for.menu-grid - 3 columns on desktop) 
    - Appropriate margins and padding (20px gap, section padding) 
    - Hover, focus and active effects (buttons scale and change colour on hover/active) 
    - Suitable typography (Arial, sans-serif) and colour combinations (brown #3e2723, orange #ff8c00) 
## Responsive Design Implementation  

My website works properly on different screen sizes. 
**What I  implemented:** 
- Relative units: `%`, `fr`, `rem` used (width:100%, grid-template-columns: 1fr) 
- Images: `width:100%; max-width:100%; height:220px; object-fit:cover;` so they resize and never overflow 
- Media queries and breakpoints: 
```css 
/* Desktop - default: 3 columns */ 
.menu-grid { grid-template-columns: repeat(3, 1fr); } 
/* Tablet: 2 columns */ 
@media (max-width: 900px) { 
 .menu-grid { grid-template-columns: repeat(2, 1fr); } 
} 
/* Mobile: 1 column */ 
@media (max-width: 600px) { 
 .menu-grid { grid-template-columns: 1fr; } 
  nav { flex-direction: column; } 
}

## References - Whole Code Sources 
This website was built using the following references and documentation: 
### HTML & CSS Structure 

- W3Schools. (2026). HTML Responsive Web Design. https://www.w3schools.com/html/html_responsive.asp 

- W3Schools. (2026). CSS Grid Layout. https://www.w3schools.com/css/css_grid.asp 

- MDN Web Docs. (2026). CSS Flexible Box Layout. https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout 

 

### Responsive Design (Section 4 Requirements) 

- MDN Web Docs. (2026). CSS Media Queries. https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries 

- CSS-Tricks. (2026). A Complete Guide to Grid. https://css-tricks.com/snippets/css/complete-guide-grid/ 

- W3Schools. (2026). CSS object-fit Property - for image resizing. https://www.w3schools.com/css/css3_object-fit.asp 

 

### Layout Requirements (Section 3) 

- MDN Web Docs. (2026). CSS Hover, Focus, Active pseudo-classes. https://developer.mozilla.org/en-US/docs/Web/CSS/:hover 

- W3Schools. (2026). CSS Transitions and Transform. https://www.w3schools.com/css/css3_transitions.asp 

 

### Order Form & JavaScript 

- W3Schools. (2026). HTML Forms and JavaScript Form Validation. https://www.w3schools.com/js/js_validation.asp 

- MDN Web Docs. (2026). HTML select element. https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select 

 

### Testing Evidence (Section 5) 

- Google Chrome Developers. (2026). Chrome DevTools Device Mode. https://developer.chrome.com/docs/devtools/device-mode/ 

 

### Images Used 

- All bakery product images (bread.jpg, biscuits.jpg, mango.jpg, about.jpg, bg.jpg) - Original images from Mhlongo Dzonga Bakery, Tzaneen 

- Screenshots (desktop.png, tablet.png, mobile.png) - Taken by student using Chrome DevTools responsive mode as per Section 5 testing evidence 

 

### Code Files Referenced in this Project 

- `index.html` - Home page structure based on HTML5 semantic structure [W3Schools HTML5] 

- `about.html` - About page layout 

- `menu.html` - Contains 6 products grid + Buyer Order Form (Name, Product, Quantity) - Custom code 

- `services.html` - Services page 

- `contact.html` - Contact page 

- `style.css` - Main stylesheet containing Flexbox, Grid, media queries (max-width: 900px, 600px), relative units (%, fr, rem), hover/active effects 

- `CHANGELOG.md` - Version history as per Keep a Changelog format [https://keepachangelog.com/] 

- `README.md` - This documentation file 
