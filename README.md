# the_daily_privacy

Static privacy policy site for the_daily's WHOOP integration.

## Pages

| Route | File |
|-------|------|
| `/privacy` | `privacy/index.html` |

## Deploy to Vercel

### Option 1 — Vercel CLI

```bash
npm i -g vercel
vercel
```

Follow the prompts. On first deploy, Vercel will ask to link or create a project.
After the initial deploy, subsequent deploys run with just `vercel --prod`.

### Option 2 — Vercel Dashboard

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import the `the_daily_privacy` GitHub repo
3. Framework preset: **Other** (no build step needed)
4. Leave build command and output directory blank
5. Click **Deploy**

### Expected URL

```
https://the-daily-privacy.vercel.app/privacy
```

or your custom domain if configured.

## Making Changes

| What to change | File | Field |
|----------------|------|-------|
| Policy text | `privacy/index.html` | Any section body |
| Effective date | `privacy/index.html` | `<p class="meta">` and `<title>` if desired |
| Contact email | `privacy/index.html` | `<a href="mailto:...">` near the bottom |
| Page styles | `styles.css` | Any rule |

After editing, commit and push — Vercel will redeploy automatically if connected to GitHub.
