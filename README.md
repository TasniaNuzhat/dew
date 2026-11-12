# Due Diligence Prep Bootcamp

Next.js 14 App Router / TypeScript / Tailwind. Every page section has its own file in `components/all-components/`; the composed page component is `components/ui/due-diligence-bootcamp.tsx`.

## Local setup

Open THIS folder (the one containing `package.json`) in VS Code.

```bash
npm install
npm run dev
```

Open http://localhost:3000. For a production check:

```bash
npm run build
npm run start
```

## Sharing

Commit the project files to GitHub, excluding `node_modules` and `.next`. Import the repository into AI Studio. A working local build does not itself guarantee that AI Studio will publish the project: use AI Studio's Publish/Share flow and test the published link in a private browser window.

## Assets

All local photos are imported from `src/assets/images`. No asset is loaded from a public folder.
