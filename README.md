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