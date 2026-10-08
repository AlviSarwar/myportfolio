# myportfolio

Personal portfolio website of **Md. Alvi Sarwar**, a Computer Science and Engineering undergraduate at the University of Asia Pacific and aspiring AI engineer.

**Live site:** <https://alvisarwar.github.io/myportfolio/>

## Sections

- **Home and About:** short introduction, social links and a downloadable resume
- **Skills:** programming languages, AI and prompt engineering, problem solving, creative skills
- **Projects:** Grameen Bank database system, Shopping Cart Management System (Java OOP), GaanHub music streaming platform
- **Problem Solving:** competitive programming highlights
- **Tools and Expertise:** IDEs, databases, dev tools, office and media tools
- **Certifications:** certificates with full-size previews
- **Education:** academic timeline
- **Contact:** message form (via Formspree), social links and a location map

## Tech

Plain HTML and CSS with a small inline script, no framework and no build step.

- Responsive layout with a slide-in mobile menu (pure CSS toggle)
- Font Awesome icons from a CDN
- Contact form handled by [Formspree](https://formspree.io/)
- Accessible by default: labelled controls and icons, visible keyboard focus, reduced-motion support

## Project structure

```
index.html   page markup
style.css    all styles, including responsive breakpoints
*.png / *.jpg / *.jpeg   profile photos, project screenshots and certificates
alvicv.pdf   downloadable resume
```

## Run locally

No installation needed. Either open `index.html` in a browser or serve the folder:

```bash
git clone https://github.com/AlviSarwar/myportfolio.git
cd myportfolio
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Customizing

- Replace the images in the repository root and update the matching `<img>` tags in `index.html`.
- Change the accent color by editing `#00aaff` in `style.css`.
- To receive form messages at your own address, replace the Formspree URL in the `<form action>` attribute with your own endpoint.

## Deployment

The site is served with GitHub Pages: **Settings -> Pages -> Deploy from a branch -> `main` / root**.
