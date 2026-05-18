# Local Development

## Prerequisites

- Node.js (`brew install node`)
- Vercel CLI (`npm i -g vercel`)
- `.env.local` in project root with:
  ```
  GOOGLE_API_KEY=your_key
  GROQ_API_KEY=your_key
  ```

## Start

```
cd ~/Desktop/app\ html/cuisineatrandom
vercel dev
```

Runs at **http://localhost:3000**

## Stop

Press `Ctrl+C` in the terminal running `vercel dev`.

## View

Open **http://localhost:3000** in your browser. This serves `index.html` with the `/api/*` serverless functions running locally using your `.env.local` keys.
