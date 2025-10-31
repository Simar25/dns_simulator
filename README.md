# DNS Simulator (Full)

This is a full DNS Resolution Simulator (Next.js) designed for demo and learning purposes.
It simulates DNS resolution including local cache with TTL, recursive resolver steps, and authoritative servers.
The app supports query types: A, AAAA, CNAME, MX.

## Features
- Simulated in-memory cache with TTL (seconds)
- Step-by-step resolution log
- Supports A / AAAA / CNAME / MX query types
- Simple UI and API route (Next.js) ready for Vercel deployment

## Run locally
```
npm install
npm run dev
```

## Deploy to Vercel
1. Push this repo to GitHub.
2. Import the repo at https://vercel.com/new and deploy. Vercel detects Next.js automatically.

Note: The demo uses an in-memory cache inside the serverless function. On Vercel serverless, memory does not persist across cold starts. For persistent caching, use Redis, Supabase, or another database.
