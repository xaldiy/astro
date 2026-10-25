
# Aldi — JavaScript Projects & Astro

A developer landing page introducing two projects in the JavaScript ecosystem: an Astro-powered personal website and an interactive 3D farming simulation backed by Node.js.

## Projects

### [aldi.my.id](https://aldi.my.id/) — Astro-powered personal website

`aldi.my.id` is a personal website built with [Astro](https://astro.build/), an open-source web framework in the JavaScript ecosystem.

Its source structure uses Astro components, file-based routes, layouts, JavaScript modules, TypeScript utilities, stylesheets, and integrations.

Astro supports JavaScript and TypeScript alongside its `.astro` component format, HTML, and CSS. It follows an HTML-first approach: pages are rendered to HTML by default, with client-side JavaScript added where interactive features need it.

Learn more:
- [Astro official website](https://astro.build/)
- [Astro documentation](https://docs.astro.build/)

### [egg.my.id](https://egg.my.id/) — Interactive 3D farming simulation

`egg.my.id` is a browser-based 3D incubation and farming simulation. It demonstrates JavaScript as application logic, not merely as a language used to add a small effect to a page.

Based on the project source, its main technologies and features include:

- **JavaScript in the browser:** Handles simulation logic, game state, controls, and user interactions.
- **Three.js:** Renders the 3D scene in the browser.
- **Socket.IO client and server:** Supports real-time communication between the browser and backend, including login, state synchronization, and updates.
- **Node.js and Express:** Provide the JavaScript backend server.
- **JSON persistence:** Game and player data are read from and written to JSON files by the server.
- **Interactive simulation systems:** Incubation, eggs, chickens and ducks, animal care, plants, a garden, daily gifts, and quizzes.

The frontend imports Three.js and Socket.IO in the browser. The backend uses Node.js packages including Express, Socket.IO, CORS, and dotenv.

This makes `egg.my.id` a practical example of a full-stack JavaScript project with a real-time client-server architecture.

## Why These Projects Are Relevant to the JavaScript Community

Together, these projects show different ways to use the JavaScript ecosystem:

- **Astro** demonstrates a component-based, file-routed approach to building a content-focused website with JavaScript and TypeScript.
- **egg.my.id** demonstrates browser-side JavaScript, 3D rendering with Three.js, real-time event-driven communication with Socket.IO, and a Node.js backend.

The goal of this landing page is to share practical project context and help other developers explore the technologies and architecture behind the work.

## Landing Page Implementation

This particular landing page is a standalone HTML document using CSS for styling and a small JavaScript snippet to update the footer year.

It does not require an Astro build step or npm dependencies to be published. The projects described above use their own respective technology stacks.

## Publish on GitHub Pages

1. Put `index.html` in the root of the `xaldiy/astro` repository.
2. Open **Settings → Pages** in GitHub.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the branch you publish from (usually `main`) and the `/ (root)` folder.
5. Save and wait for GitHub Pages to publish the page.

If the repository is named `astro` and Pages is configured to publish from the repository root, the project page should be available at:

`https://xaldiy.github.io/astro/`

## Configure `aldi.js.org`

Configure the DNS records required by the current GitHub Pages custom-domain instructions, then add `aldi.js.org` under **Settings → Pages → Custom domain**.

Follow the DNS records GitHub shows for your configuration and wait for DNS propagation before enabling HTTPS.

## Links

- Personal website: <https://aldi.my.id/>
- JavaScript simulation: <https://egg.my.id/>
- Astro: <https://astro.build/>
- Astro documentation: <https://docs.astro.build/>
- Landing page repository: <https://github.com/xaldiy/astro>
