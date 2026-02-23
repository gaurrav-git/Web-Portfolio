# 🌐 My First Portfolio Website

Hey! This is my very first portfolio website, built using **HTML and CSS** as part of my Vineyard course assignment.

## About Me

**Gaurav Arora**
MCA Student @ GGSIPU '27 | Aspiring Software Developer | Delhi, India

- LinkedIn: [linkedin.com/in/a-rav](https://www.linkedin.com/in/a-rav/)
- GitHub: [github.com/a-rav](https://github.com/gaurrav-git)


## Project Structure

This project has just **2 files**. That's it

```
portfolio-website/
│
├── index.html       ← The structure of the website (all the content)
└── style.css        ← The styling (colors, fonts, layout)
```

## What's Inside the Website

The website has these sections, each with its own `id` so the nav links can jump to them:

| Section | What it shows |
|---|---|
| **Header** | My name and tagline |
| **Navigation Bar** | Links to jump to each section (sticky — stays on top when you scroll!) |
| **Home** | A welcome hero banner + my hobby (Cinematography 🎬) with a numbered list |
| **About** | My bio, skills, education (MCA + BBA), and certifications (IBM + IIT Kharagpur) |
| **Projects** | 3 project cards with descriptions and links |
| **Contact** | A form with Name, Email, Message, and a Submit button |
| **Footer** | My LinkedIn and GitHub links |


## What I Used to Build This

| Tool | Why I used it |
|---|---|
| **HTML5** | To write the structure and content of the page |
| **CSS3** | To style everything — colors, fonts, layout, spacing |
| **Google Fonts** | For nicer-looking fonts (Playfair Display + Lato) |
| **CSS Flexbox** | To put items side-by-side (used in the About and Nav sections) |
| **CSS Grid** | To lay out the project cards in a grid (used in the Projects section) |
| **Media Queries** | To make the site work on mobile phones and tablets too |

## ✨ Features

-  Clean, readable code with comments explaining every section
-  Sticky navigation bar (stays visible as you scroll)
-  Smooth scrolling when you click nav links
-  Hover animations on buttons and project cards
-  Responsive design — looks good on desktop, tablet, and mobile

## 🚀 How to Run It

You don't need to install anything. Seriously — just follow these 3 steps:

**Step 1:** Download or clone this repository
```bash
git clone https://github.com/a-rav/portfolio-website.git
```

**Step 2:** Make sure both files are in the **same folder**
```
portfolio-website/
├── index.html
└── style.css
```

**Step 3:** Open `index.html` in your browser
- Just double-click the file, OR
- Right-click → "Open with" → choose your browser (Chrome, Firefox, Edge, etc.)

## Sections Explained (For Beginners)

### Why two files?
In web development, we keep structure (HTML) and styling (CSS) in **separate files**. This makes the code easier to read, update, and maintain. If I want to change the color scheme, I only touch `style.css`. If I want to add a new section, I only touch `index.html`.

### What is an `id`?
Each section has an `id` like `id="about"` or `id="projects"`. This lets the nav links jump directly to that section using `href="#about"`. It's like giving each room in a house a name so people can find it easily.

### What is Flexbox?
Flexbox is a CSS tool that puts elements side-by-side in a row (or stacks them). I used it for the nav bar links and the About section (profile pic beside the bio text).

### What is CSS Grid?
CSS Grid is another layout tool, better for 2D layouts (rows AND columns). I used it for the Projects section so the cards automatically arrange themselves into a neat grid.

### What are Media Queries?
Media queries are CSS rules that only activate on certain screen sizes. For example:
```css
@media (max-width: 768px) {
  /* This code only runs on screens 768px wide or smaller (tablets/phones) */
}
```
This is what makes the site "responsive" — it adjusts the layout based on the device.

## Color Palette Used

| Name | Hex Code | Used For |
|---|---|---|
| Deep Navy | `#1a1a2e` | Header, headings, dark text |
| Dark Blue | `#0f3460` | Nav bar, links, borders |
| Red-Pink | `#e94560` | Buttons, highlights, underlines |
| Warm White | `#f5f3ee` | Page background |
| Gold | `#f0a500` | Achievement badge, certification cards |


## Fonts Used

- **Playfair Display** (700, 900 weight) — Used for all headings. Elegant and bold.
- **Lato** (300, 400, 700 weight) — Used for body text. Clean and easy to read.

## Assignment Requirements Met

This project was built as an HTML & CSS assignment. Here's how every requirement is covered:

**HTML Structure:**
- [x] 1.1 Header with name and tagline
- [x] 1.2 Navigation bar with Home, About, Projects, Contact links
- [x] 1.3 About section with bio
- [x] 1.4 Projects section with 3 project cards (title, description, links)
- [x] 1.5 Contact form with Name, Email, Message, Submit button
- [x] 1.6 Home section with hobby h2, paragraph, and ordered list (`<ol>`)
- [x] 1.7 Footer with LinkedIn and GitHub links

**CSS Styling:**
- [x] 2.1 Background color set for the webpage
- [x] 2.1 Google Fonts used for headings and body text
- [x] 2.1 Max-width set and content centered with `margin: 0 auto`
- [x] 2.2 Header, nav bar, home section, and footer all styled
- [x] 2.2 CSS Grid used for the Projects section layout
- [x] 2.2 Contact form styled with clear spacing and focus states
- [x] 2.3 Responsive design with media queries for tablet (768px) and mobile (480px)


## What I Learned Building This

- How HTML tags give structure to a webpage
- How CSS selectors and properties work
- The difference between `id` and `class`
- How `display: flex` and `display: grid` control layouts
- What `position: sticky` does (the nav bar sticks when scrolling!)
- How `@media` queries make a site look good on all screen sizes
- How CSS variables (`:root`) make it easy to manage colors across a whole project
- How `transition` creates smooth hover animations
- How `box-shadow` and `border-radius` make cards look modern and clean

## What I Want to Add in the Future

- [ ] A real photo instead of the "GA" initials circle
- [ ] JavaScript to make the contact form actually send emails (using Formspree)
- [ ] A dark mode toggle button
- [ ] Animations when sections appear as you scroll (using JavaScript IntersectionObserver)
- [ ] More real projects as I build them during my MCA

## Acknowledgements

- [Google Fonts](https://fonts.google.com) — for the free beautiful fonts
- Vineyard by Grapecity
