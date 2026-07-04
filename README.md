# LinkedIn Public Profile Auto Checker - Vercel Ready

Safe public profile accessibility checker.

## What it does

- Paste multiple LinkedIn public profile URLs.
- Click **Submit & Auto Check**.
- Shows Total, OK, Not OK / Possibly Ban, Unknown.
- Exports CSV.

## Safety

This project does **not** use LinkedIn email, password, cookie, token, or login.
It only checks public profile URL accessibility from the server.

## Important

`Not OK` does not mean 100% banned. It can also mean profile removed, unavailable, not found, or private.
`Unknown` usually means LinkedIn blocked/rate-limited the server request.

## Deploy to Vercel

1. Upload these files to a GitHub repo.
2. Go to Vercel.
3. Import the GitHub repo.
4. Click Deploy.
5. Open your Vercel URL.

The API route is:

```txt
/api/check
```

## Local run

If you have Vercel CLI:

```bash
npm install
npm run dev
```

Then open:

```txt
http://localhost:3000
```
