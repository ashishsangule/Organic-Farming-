# Organic Farming System

Mobile-first Next.js + Supabase app for managing farms, fields, crops, activities, tasks, harvests and expenses.

## Setup
1. `cp .env.example .env.local` and fill in your Supabase URL and publishable key.
2. `npm install`
3. `npm run dev` then open http://localhost:3000

## Deploy on Vercel
Add `NEXT_PUBLIC_SUPABASE_URL` and `NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY` under Project > Settings > Environment Variables, then deploy.
