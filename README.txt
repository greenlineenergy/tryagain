# GreenLine Website (Next.js + Tailwind) — No GitHub Needed

## Quick Deploy (Vercel)
1) Go to https://vercel.com/new (sign in with Google)
2) Click **Import Project** → **Upload** → drag this folder (or the ZIP)
3) Click **Deploy** — you’ll get a live link like https://greenline.vercel.app
4) In Vercel → Project → **Settings → Domains** → Add your real domain
5) Paste the 2 DNS records at your registrar (A @ 76.76.21.21, CNAME www cname.vercel-dns.com)

## Local Dev (optional)
```bash
npm i
npm run dev
```

## Email (2 addresses)
- Full Gmail inbox: Google Workspace → create hello@ and quotes@
- Free forwarding: Cloudflare Email Routing → forward to your personal Gmail
