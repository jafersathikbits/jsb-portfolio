# Jafer Sathik B — Portfolio

A responsive personal portfolio showcasing full-stack software development, AI/ML projects, client work, technical skills, and achievements.

## Overview

This portfolio is a single-page website for presenting my experience as a software developer and Information Technology student at PSG College of Technology.

It highlights selected projects, client work, technical skills, education, achievements, and contact information in one place. The site is built with HTML, CSS, and vanilla JavaScript, without requiring a frontend framework or build process.

## Features

- Responsive design for mobile, tablet, and desktop.
- Light and dark themes with the selected theme remembered in the browser.
- Mobile navigation and active-section highlighting.
- Project category filters for browsing selected work.
- Accessibility features, including a skip link, keyboard focus styles, labelled controls, and reduced-motion support.
- Contact information with copy-to-clipboard controls.
- Downloadable PDF resume and print-friendly styling.
- Open Graph metadata for link previews.
- Schema.org structured data for profile information.

## Tech Stack

- **Structure:** HTML5
- **Styling:** CSS, custom properties, Grid, Flexbox, and media queries
- **Interactivity:** Vanilla JavaScript
- **Typography:** Bricolage Grotesque, Figtree, and JetBrains Mono
- **Fonts:** Google Fonts
- **Hosting:** GitHub Pages or another static hosting provider

## Portfolio Highlights

The portfolio presents selected work across several areas:

- **Full-stack development:** Web applications, database integration, authentication, and role-based access.
- **Client projects:** Inventory management and event management platforms.
- **AI/ML:** Privacy-preserving retrieval-augmented generation and predictive vehicle maintenance.
- **Workflow automation:** Government plot compliance, milestone tracking, and reporting.
- **Professional development:** Education, technical skills, achievements, and leadership experience.

For implementation details, technologies, and project-specific limitations, refer to the individual project repositories.

## Project Structure

```text
jsb-portfolio/
├── index.html
├── assets/
│   ├── Jafer-Sathik-B-Resume.pdf
│   └── jafer.jpg
├── .gitignore
└── README.md
```

- `index.html` contains the page markup, styles, and JavaScript.
- `assets/Jafer-Sathik-B-Resume.pdf` is the downloadable resume.
- `assets/jafer.jpg` is the profile photograph.
- `.gitignore` excludes common operating-system, editor, and temporary files.

## Prerequisites

- A modern web browser.
- Python 3, optional for running a local HTTP server.

No frontend framework, package manager, or build tool is required.

## Installation and Setup

Clone the repository:

```bash
git clone <your-repository-url>
cd jsb-portfolio
```

No dependency installation is necessary.

## Environment Variables

Not applicable. The portfolio is a static front-end website and does not require environment variables or application secrets.

## Usage

### Open locally

Open `index.html` directly in a browser.

Alternatively, start a local HTTP server from the project directory:

```bash
python3 -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000).

### Customize the portfolio

- **Content and projects:** Edit the relevant sections in `index.html`.
- **Colors and typography:** Update the CSS custom properties and styles in `index.html`.
- **Resume:** Replace `assets/Jafer-Sathik-B-Resume.pdf`, keeping the filename unchanged unless you also update its references.
- **Profile photograph:** Replace `assets/jafer.jpg` and adjust the image crop if needed.
- **Social links and metadata:** Update the relevant links, canonical URL, Open Graph metadata, and structured data when changing the public portfolio address.

### Testing

No automated test suite is included. Before publishing changes, check the page at desktop and mobile widths, verify theme switching and project filters, test contact links, and confirm that the resume download works.

## Deployment

This is a static website and does not require a backend server.

### GitHub Pages

1. Push the project files to the root of the GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait for GitHub Pages to publish the site.

### Other static hosting providers

The site can also be hosted on Netlify, Vercel, Cloudflare Pages, or another static web host.

No build command is required; use the repository root as the publish directory.

The current canonical URL and social preview metadata point to `https://jafersathikb-india.github.io/portfolio/`. Update these values in `index.html` if the site is published at a different address.

## Future Improvements

- Add live links to each published project repository and demonstration.
- Add project-specific screenshots or demonstrations where appropriate.
- Improve automated accessibility and cross-browser checks.
- Track broken external links and verify downloadable assets.
- Continue refining mobile layouts and page performance as new projects are added.

## Contributing

This is a personal portfolio. For corrections or suggestions, open an issue or contact me through the links provided on the website.

## License

This project is licensed under the MIT License.
See the [LICENSE](LICENSE) file for details.
