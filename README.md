# The Online Books Page

A simple web project that demonstrates an online book search interface along with CSS combinator examples.

## Project Structure

```
The-online-Books/
├── index.html       # Main page – Online Books search interface
├── combinators.html # CSS Combinators demo page
├── stillar.css      # Styles for the main page (button styling)
├── style.css        # Styles for the combinators demo page
└── README.md
```

## Pages

### 1. Online Books Page (`index.html`)
The main landing page for the Online Books application. It features:
- Styled buttons using class (`.btn`) and ID (`#btn`) selectors
- A book search form (Author / Title fields with radio options) — currently in development
- Navigation links: Home, Search, New Listings, Authors, Title, Serials

### 2. CSS Combinators Demo (`combinators.html`)
A practice page that demonstrates the four CSS combinator selectors:

| Combinator | Syntax | Description |
|------------|--------|-------------|
| Descendant | `div p` | Selects all `<p>` elements inside a `<div>` |
| Child | `div > p` | Selects only direct child `<p>` elements of a `<div>` |
| Adjacent Sibling | `div + p` | Selects the first `<p>` immediately after a `<div>` |
| General Sibling | `div ~ p` | Selects all `<p>` siblings after a `<div>` |

## Getting Started

No build tools or dependencies are required. Simply open the HTML files in any modern web browser:

```bash
# Open the main page
open index.html

# Open the combinators demo
open combinators.html
```

Or serve locally with any static file server, for example:

```bash
npx serve .
```

## Technologies Used

- **HTML5** – Page structure and semantic markup
- **CSS3** – Styling, button design, and combinator demonstrations

## Author

Made by **Asilbek**
