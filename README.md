# README

## Fluid layout and media queries
Fluid layout uses CSS Grid and relative units. Header is Grid and nav items are `inline-block`.

## Viewports
Separate CSS files per viewport as per below specifications:
- **mobile.css** (max-width: 599px): single-column grids with compact padding
- **tablet.css** (600px-1023px): two-column grids
- **laptop.css** (min-width: 1024): three-column grids and wider container

I used 599px as it is a common upper bound for phones. For tablets, 600–1023px is a generous range for many tablets. And for laptops/desktops, 1024px and greater is a practical size. This helps maintain website readability and ease of navigation on various screen sizes.

## Gradients
Angled linear gradient on `.hero` sections: `linear-gradient(135deg, rgba(34,211,238,.10), transparent 65%)`

Standard linear gradient on footer bar: `linear-gradient(to right, rgba(59,130,246,0.15), rgba(34,211,238,0.10))`

## Colour scheme
I used an analagous blue-cyan colour scheme for a calm yet professional base with amber focus for a slight warm accent to keep visibility on outlines. Kept contrast with muted text and dark backgrounds.