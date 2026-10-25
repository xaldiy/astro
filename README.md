# Aldi.js.org

Personal developer landing page for **Aldi Setiadi Putra**, featuring my projects, website, and the technologies I use.

## 🌐 Website

- **Main Website:** [aldi.my.id](https://aldi.my.id)
- **Developer Landing Page:** [aldi.js.org](https://aldi.js.org)
- **Astro Source Repository:** [xaldiy.github.io/astro](https://github.com/xaldiy/astro)

## 🚀 What Is Astro?

**[Astro](https://astro.build/)** is an open-source web framework in the JavaScript ecosystem designed for building fast, content-focused websites.

Astro supports JavaScript and TypeScript, and uses its own `.astro` component format. Astro components allow developers to combine HTML-like markup, JavaScript expressions, and scoped CSS in a single file.

Key features include:

- **JavaScript ecosystem:** Astro works with JavaScript and TypeScript, alongside tools and packages from the broader JavaScript ecosystem.
- **Component-based architecture:** Build reusable UI components using `.astro` files.
- **HTML-first rendering:** Astro renders pages to HTML by default and sends client-side JavaScript only when needed.
- **File-based routing:** Files inside `src/pages/` automatically define website routes.
- **Performance-focused:** Designed to deliver fast websites with minimal unnecessary JavaScript in the browser.

Astro makes it possible to build modern websites while keeping the delivered pages lightweight and efficient.

Learn more:
- [Astro Official Website](https://astro.build/)
- [Astro Documentation](https://docs.astro.build/)

## 📂 Project Structure

The Astro project uses a structured source directory:

```text
src/
├── components/
│   ├── ChatWidget.astro
│   ├── Footer.astro
│   └── Navbar.astro
├── layouts/
│   └── Layout.astro
├── lib/
│   └── firebase.js
├── pages/
│   ├── api/
│   ├── about.astro
│   ├── contact.astro
│   ├── galeri.astro
│   ├── music.astro
│   ├── tools.astro
│   └── ...
├── styles/
├── utils/
├── middleware.ts
└── ...
```

This structure separates reusable components, page layouts, routes, libraries, styles, and utility functions.

## 🛠️ Technologies

- **Astro** — Web framework
- **JavaScript** — Client-side logic and application functionality
- **TypeScript** — Typed JavaScript for selected modules
- **HTML5** — Page structure
- **CSS3** — Styling and responsive layouts
- **Firebase** — Backend services used by selected features
- **GitHub Pages** — Hosting for the developer landing page

## 📦 Deployment

The standalone developer landing page uses HTML, CSS, and a small amount of JavaScript. The main website, [aldi.my.id](https://aldi.my.id), is built with Astro.

To deploy the landing page using GitHub Pages:

1. Push `index.html` and `README.md` to the repository.
2. Open the repository's **Settings → Pages**.
3. Select the appropriate branch and root directory as the deployment source.
4. Save the settings and wait for GitHub Pages to publish the website.

### Custom Domain

To use `aldi.js.org`, configure the domain's DNS settings to point to the GitHub Pages deployment, then add `aldi.js.org` in the repository's **Settings → Pages → Custom domain**.

Domain availability and approval depend on the domain provider's current policies.

## 📄 License

This project is a personal developer landing page. Please contact the owner before reusing any original branding or personal content.
