# Pritesh Patil — Portfolio

Personal portfolio website built as a single-page static site, ready to deploy on GitHub Pages.

## Live Site

[priteshpatil.github.io](https://priteshpatil.github.io) *(update with your actual URL)*

## Structure

```
Profile/
├── index.html                  # Entire site — HTML, CSS, and JS in one file
├── ProfilePic-PriteshPatil.jpg # Profile photo
├── resume.pdf                  # (optional) Linked from the Contact section
└── README.md
```

## Sections

| Section | Description |
|---------|-------------|
| Hero | Name, tagline, profile photo, CTA buttons |
| About | Bio and stats (years of experience, projects, clients) |
| Skills | Technology cards |
| Projects | Featured project cards with GitHub and live demo links |
| Contact | Email CTA and social links |

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Set **Source** to `Deploy from branch`, branch `main`, folder `/ (root)`.
4. GitHub will publish the site — usually within 60 seconds.

For a user/org page, name the repo `<your-username>.github.io` and the site will be served at that domain directly.

## Customization

All content is in `index.html`. Search for the following placeholders and replace them:

- **Bio / About text** — paragraphs inside `<section id="about">`
- **Stats** — the four `.stat-card` blocks (years, projects, clients)
- **Skills** — the `.skill-card` blocks inside `<section id="skills">`
- **Projects** — the `.project-card` blocks; update titles, descriptions, tags, and `href` links
- **Email** — `mailto:pritesh@example.com` in the Contact section
- **Social links** — GitHub, LinkedIn, Twitter `href` values
- **Open to opportunities badge** — edit or remove the `.hero-badge` div in the Hero section

## Tech

Pure HTML, CSS, and vanilla JavaScript — no build step, no dependencies, no frameworks.
