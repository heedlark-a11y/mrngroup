# MRN Group — Official Company Profile
Official static company profile website for **MRN Group**.
This project is built using pure:
- HTML5
- CSS3
- Vanilla JavaScript
No framework, database, backend, or build system is required.
---
## About MRN Group
MRN Group is a growing business and technology ecosystem focused on building digital products, software, ecommerce platforms, WordPress solutions, and technology-driven business services.
This website serves as a central public profile for:
- MRN Group
- Brands
- Products
- Projects
- Team
- Company information
- Gallery
- Business contact information
---
## Technology
| Technology | Usage |
|---|---|
| HTML5 | Website structure |
| CSS3 | Design and responsive layout |
| JavaScript | Navigation and interactions |
| GitHub | Source code management |
| GitHub Pages / Hostinger | Deployment |
---
## Project Structure
```text
mrn-group/
│
├── index.html
│
├── css/
│   └── style.css
│
├── js/
│   └── main.js
│
├── images/
│   │
│   ├── logo/
│   │   └── mrn-group-logo.png
│   │
│   ├── hero/
│   │   └── hero.jpg
│   │
│   ├── about/
│   │   └── about.jpg
│   │
│   ├── brands/
│   │   ├── mrn-theme.png
│   │   ├── mrn-bd-courier.png
│   │   ├── mrn-books.png
│   │   └── mrn-marketplace.png
│   │
│   ├── projects/
│   │   ├── project-01.jpg
│   │   ├── project-02.jpg
│   │   └── project-03.jpg
│   │
│   ├── team/
│   │   ├── member-01.jpg
│   │   └── member-02.jpg
│   │
│   └── gallery/
│       ├── photo-01.jpg
│       ├── photo-02.jpg
│       └── photo-03.jpg
│
└── README.md

⸻

Editing the Website

The website is intentionally simple to edit.

No coding framework is required.

Change Company Name

Open:

index.html

Find:

MRN Group

Replace it with the required company name.

⸻

Change Logo

Place the official logo inside:

images/logo/

Recommended filename:

mrn-group-logo.png

The HTML already references:

images/logo/mrn-group-logo.png

If you use another filename, update the image path in index.html.

⸻

Hero Image

Place the main company image inside:

images/hero/

Recommended filename:

hero.jpg

HTML:

<img
    src="images/hero/hero.jpg"
    alt="MRN Group"
>

⸻

About Image

Place the company/about image inside:

images/about/

Recommended filename:

about.jpg

⸻

Brand Images

All brand logos/images should be placed inside:

images/brands/

Example:

mrn-theme.png
mrn-bd-courier.png
mrn-books.png
mrn-marketplace.png

To add another brand, copy an existing brand card in index.html.

Example:

<article class="brand-card">
    <img
        src="images/brands/new-brand.png"
        alt="New Brand"
    >
    <div class="brand-card-content">
        <span>Category</span>
        <h3>
            New Brand
        </h3>
        <p>
            Short description of the brand.
        </p>
        <a href="#" class="text-link">
            Visit Website →
        </a>
    </div>
</article>

⸻

Projects

Project images belong in:

images/projects/

Example:

project-01.jpg
project-02.jpg
project-03.jpg

Each project can contain:

* Project name
* Category
* Description
* Screenshot
* Website link

⸻

Team

Team member photos belong in:

images/team/

Example:

member-01.jpg
member-02.jpg
member-03.jpg

Update the person’s:

* Name
* Position
* Photo

inside index.html.

⸻

Gallery

Company and project photos belong in:

images/gallery/

Example:

photo-01.jpg
photo-02.jpg
photo-03.jpg
photo-04.jpg

To add more gallery images, copy an existing image element:

<img
    src="images/gallery/photo-04.jpg"
    alt="MRN Group"
>

⸻

Contact Information

Open:

index.html

Find the Contact section and replace the placeholder information.

Update:

* Official email
* Official website
* GitHub
* Office/location
* Social media links

Do not leave placeholder contact information on the live website.

⸻

Website Links

Brand and project links should use the actual official website.

Example:

<a
    href="https://example.com"
    class="text-link"
    target="_blank"
    rel="noopener noreferrer"
>
    Visit Website →
</a>

Replace https://example.com with the correct website.

⸻

Responsive Design

The website is designed to work across:

* Mobile
* Tablet
* Laptop
* Desktop

The responsive styles are located in:

css/style.css

⸻

JavaScript

JavaScript is intentionally lightweight.

The current JavaScript handles:

* Mobile navigation
* Escape-key navigation closing
* Accessibility attributes
* Dynamic copyright year

File:

js/main.js

No external JavaScript library is required.

⸻

Images

Recommended formats:

* .webp
* .jpg
* .jpeg
* .png

For photographs, WebP or optimized JPG is recommended.

For logos with transparency, PNG or WebP is recommended.

Avoid uploading unnecessarily large images.

⸻

Local Preview

You can preview the website without installing a framework.

Simply open:

index.html

in a browser.

For development, you can also use VS Code with a local static server.

⸻

GitHub Pages

This project can be deployed using GitHub Pages.

Basic process:

1. Create a GitHub repository.
2. Upload the complete project.
3. Make sure index.html is in the repository root.
4. Open repository Settings.
5. Open Pages.
6. Select the deployment branch.
7. Save.
8. GitHub will provide the public website URL.

⸻

Hostinger Deployment

The website can also be hosted on Hostinger.

Upload:

index.html
css/
js/
images/

to:

public_html/

The final structure should be:

public_html/
│
├── index.html
├── css/
├── js/
└── images/

⸻

Browser Support

The website is designed for modern browsers including:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari
* Mobile Safari
* Android browsers

⸻

Accessibility

The website includes basic accessibility practices such as:

* Semantic HTML
* Image alt text
* Keyboard focus states
* Accessible mobile navigation
* aria-expanded
* Escape-key navigation handling
* Responsive layouts

When adding new images, always provide meaningful alt text.

⸻

Performance

The project intentionally avoids:

* Large JavaScript frameworks
* jQuery
* External font dependencies
* Unnecessary libraries
* Heavy frontend dependencies

Keep images optimized when adding new content.

⸻

SEO

The website includes basic HTML metadata.

Before publishing, update:

<title>

and:

<meta name="description">

with the final official company information.

Additional SEO improvements can be added later.

⸻

Security

This is a static website and does not contain:

* Database
* User accounts
* Server-side PHP
* Payment processing
* Admin login
* User data collection

External links should use:

target="_blank"
rel="noopener noreferrer"

when appropriate.

⸻

Important

Do not publish placeholder information as official MRN Group information.

Before going live, verify:

* Company description
* Brand names
* Project names
* Statistics
* Team information
* Email address
* Website URLs
* Social media URLs
* Office/location information
* Images

⸻

Future Development

Possible future additions may include:

* Dedicated About page
* Individual brand pages
* Individual project pages
* News / announcements
* Careers page
* Contact form
* Social media integration
* Multi-language support
* CMS/backend
* Advanced company profile management

These should be implemented only when required.

⸻

License

Copyright © MRN Group.

All rights reserved unless otherwise specified.

The source code, branding, logos, images, product names, and other MRN Group materials may not be redistributed, resold, or reused without appropriate permission.

⸻

Maintained By

MRN Group

Official Theme:

https://wordpress.org/themes/mrntheme/