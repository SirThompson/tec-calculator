# TEC Services Calculator

React/Vite app wrapper for the Claude artifact calculator.

## Local setup

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

## Vercel settings

- Framework preset: Vite
- Build command: npm run build
- Output directory: dist

## Webflow embed

After deploying to Vercel, embed it in Webflow using an iframe:

```html
<iframe
  src="https://your-vercel-url.vercel.app"
  style="width:100%; min-height:900px; border:0; display:block;"
  loading="lazy"
></iframe>
```
