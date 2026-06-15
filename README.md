# Modu
A lightweight JSON-driven PHP page builder that renders modular components into static HTML.

## Structure
data/ – JSON files used to build pages
export/ – generated HTML output
sections/ – PHP components used for rendering sections
## How it works
Edit JSON files in the data folder or use the editor UI to build pages
Add or modify components in sections if you understand PHP
Click Export to generate a static HTML page
## Tech stack
PHP
HTML
Tailwind CSS

### Notes
Built using ChatGPT and a traditional LAMP-style stack.

## Quick start

1. Clone repo
2. Place project in local PHP server (XAMPP / Laragon / PHP built-in server)
3. Open index.php
4. Edit JSON inside /data
5. Click Export to generate HTML

## Example JSON

{
  "title": "My Page",
  "sections": [
    {
      "type": "hero",
      "data": {
        "heading": "Hello Modu",
        "subheading": "JSON powered pages"
      }
    }
  ]
}
