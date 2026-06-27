# Busan | Tourist destination

> **Language:** English · [Português (BR)](README.md)

Static tourism landing page about Busan, South Korea, built with HTML and CSS only.

## About the project

Static page showcasing Busan as a travel destination, highlighting three historical attractions. The layout is based on a Figma design and built without frameworks or JavaScript.

## Project structure

```
local-turistico/
├── assets/
│   ├── busan.png       # Hero section main image
│   ├── icone.png       # Footer icon
│   ├── parque.png      # Yongdusan Park image
│   ├── templo1.png     # Haedong Yonggungsa Temple image
│   └── templo2.png     # Beomeo-sa Temple image
├── index.html          # Page structure and content
├── styles.css          # Styles and layout
├── LICENSE
├── README.md           # Portuguese documentation
└── README.en.md        # English documentation
```

## How to run

Since the project consists only of static files, no dependencies need to be installed.

**Option 1 — Open directly in the browser**

Open the `index.html` file in your preferred browser (double-click or drag the file into the browser window).

**Option 2 — Local server with Python**

```bash
python -m http.server 8080
```

Visit [http://localhost:8080](http://localhost:8080) in your browser.

**Option 3 — Live Server extension (VS Code / Cursor)**

Install the **Live Server** extension, right-click on `index.html`, and select **Open with Live Server**.

## What was learned

- Semantic HTML structure with sections, heading hierarchy (`h1`–`h3`), and lists.
- Pure CSS styling: margin reset, `:root` variables, and typography with Google Fonts.
- Applying colors, spacing, and alignment from a Figma layout.
- CSS selectors such as pseudo-elements (`::marker`), pseudo-classes (`:nth-child`), and adjacent combinators (`.divider + p`).
- Styling images, dividers, and footer to compose a complete landing page.

## Figma design

👉 [View the original layout on Figma](https://www.figma.com/community/file/1384542229391733447/local-turistico)

## Technologies used

- HTML5
- CSS3
