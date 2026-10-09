# Next.js Portfolio — Legacy

An earlier version of my personal portfolio, built with Next.js 13, React 18 and Material UI. Retained as a record of the implementation and design work.

**My current portfolio is [tuanlima.netlify.app](https://tuanlima.netlify.app/), with source in [portfolio](https://github.com/TuanCLima/portfolio).** The résumé and work history checked into this older repository are historical.

## Implementation

- Profile, professional experience and education sections.
- Reusable React components and data modules.
- A canvas-based animated background.
- CSS Modules, Material UI and Font Awesome assets.

## Run locally

```bash
git clone https://github.com/TuanCLima/nextjs-portfolio-legacy.git
cd nextjs-portfolio-legacy
npm ci
npm run dev
```

Open [localhost:3000](http://localhost:3000). Use Node.js 18 for the original toolchain in an isolated environment. This historical version has not been migrated to a current Next.js release.

## Available commands

```bash
npm run lint
npm run build
npm start
```

`npm start` serves a completed production build. There is no automated application-test suite.

## Code map

- `src/app/components/`: portfolio sections and canvas background.
- `src/app/data/`: experience and education entries.
- `src/app/page.jsx`: page composition.
- `public/`: images, historical résumé and third-party icon assets.

## License

No project-wide open-source license is declared. Font Awesome has its own [license](public/fontawesome/LICENSE.txt).
