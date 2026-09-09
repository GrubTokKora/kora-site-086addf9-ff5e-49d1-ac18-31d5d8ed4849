# Site index · format 2
Structure and the names of what each page offers. Values that change often — prices, hours, phone,
address — and body copy are deliberately not recorded here; read the page itself for those.

## index.html → /
title: Delicias Peruvian Kitchen | White Plains, NY
purpose: Showcase Delicias Peruvian Kitchen's authentic Peruvian cuisine, menu, sauces, catering, and location information.
sections:
- Announcement banner with location, phone number, and online ordering link: Order Now
- Navigation menu and branding links: Menu, Featured Favorites, Pollo a la Brasa, Saltados, Chaufas, Location, Catering, Our Sauces, Order Now
- `#page-home` "Bold Flavors from the Heart of Peru" — Hero introductory content and call to action: Order Online Now, View Full Menu, Pollo a la Brasa
- Business statistics band
- "Delicias Peruvian Kitchen" — About the restaurant and history: Order Now!
- "Featured Favorites" — Highlighted popular menu items: Lomo Saltado, Pollo a la Brasa Combo, Jalea Pa' Picar, View All
- Newsletter signup form: Subscribe Now
- `#page-menu` "Our Menu" — Complete categorized food menu with tabs: 🍗 Pollo a la Brasa, 🥩 Saltados, 🍚 Chaufas, Whole Chicken, Half Chicken, Quarter Chicken Mata Hambre, The Delicioso, Lomo Saltado, Pollo Saltado, Shrimp Saltado, Saltado Mixto, Vegetable Saltado, Chaufa de Pollo, Chaufa de Carne, Chaufa de Shrimp, Chaufa Mixto, Chaufa de Mariscos, Order Online Now
- "Featured Favorites" — Expanded list of top-loved dishes: Lomo Saltado, Pollo a la Brasa Combo, Salchipapa La Pituca, Chaufa de Pollo, Jalea Pa' Picar, Order Now
- `#page-sauces` "Our Sauces" — House-made sauce showcase images
- `#page-location` "White Plains, NY" — Location contact details and map embed: Address, Call Us, Opening hours
- `#page-catering` "Catering Services" — Catering services and event offerings description: Your Event, Our Flavors, Call to Book Catering
- `#page-privacy` "Privacy Policy" — Website privacy policy legal text
- `#page-terms` "Terms & Conditions" — Website terms and conditions legal text
- Site footer with brand links, hours, visit info, and legal links: Menu, Catering, Location, Our Sauces, Get Directions, Call Restaurant, Order Now, Privacy Policy, Terms & Conditions
also: The restaurant's business name appears in the meta description and the structured data block.
also: The page uses a single-page application (SPA) structure with multiple views (.page) managed by JavaScript rather than distinct HTML files.

## support files
Files that are not pages. A line marked [content] holds words or data a visitor reads, so a
change to the site's content can land there; the rest only make the site work or look right.
- `robots.txt` — 112 bytes — too small to hold content
- `sitemap.xml` — Search engine sitemap listing the site's URLs

## shared (every page)
The header, navigation, mobile menu and footer are propagated from index.html to every other page by
`shell_propagation`. A change to any of them is made on index.html alone and copied automatically.
