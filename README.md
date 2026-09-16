# Positivus Landing Page

A responsive landing page for a digital marketing agency, built with HTML and SCSS based on the provided design.

The website presents the agency's services, case studies, working process, team members, customer reviews, contact form, newsletter subscription, and company information. The layout is adapted for desktop, tablet, and mobile screen sizes.

## Live Demo

View the live [DEMO](https://anastasiia-rem.github.io/positivus-landing/)

## Design

Figma design [DESIGN](https://www.figma.com/design/racHPrMNd7jO0XgXQPpE7w/Positivus-Landing-Page-Design--Community-?node-id=341-630&t=vWrn9NR3WAuaYc2t-1)

## Technologies Used

- HTML5
- SCSS
- CSS3
- BEM methodology
- Responsive Web Design
- CSS Grid
- Flexbox
- Native HTML `details` and `dialog` elements

## Features

- Responsive layout for desktop, tablet, and mobile screens
- Mobile navigation menu
- Hero section with partner logos
- Digital marketing services section
- Case studies section
- Expandable working process accordions
- Team members section
- Customer reviews
- Contact form
- Newsletter subscription form
- Responsive footer
- Hover and focus states
- Custom SCSS mixins and CSS variables
- Semantic HTML structure

## Project Structure

```text
.
├── index.html
├── images/
├── fonts/
└── styles/
    ├── styles.scss
    ├── styles.css
    ├── _variables.scss
    ├── _mixins.scss
    ├── _globals.scss
    └── blocks/
```

## Getting Started

To run the project locally:

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Go to the project directory:

```bash
cd positivus
```

3. Open `index.html` in your browser.

To compile SCSS manually:

```bash
sass styles/styles.scss styles/styles.css
```

The project also includes a VS Code task named **Compile SCSS to CSS**.
