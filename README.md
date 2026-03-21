# Muskan Portfolio

Professional portfolio built with React + Vite.

## Local Setup

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deploy

### Vercel (Recommended)
- Import the repository
- Framework: Vite
- Build Command: `npm run build`
- Output Directory: `dist`

The `api/leetcode/[username].js` serverless function works automatically on Vercel.

### Netlify
- Build Command: `npm run build`
- Publish Directory: `dist`

If you want the LeetCode proxy on Netlify, add a Netlify Function (not included yet).

## Folder Structure

```
src/            # React components
public/         # Static assets (resume, images)
api/            # Serverless proxy (Vercel)
```
