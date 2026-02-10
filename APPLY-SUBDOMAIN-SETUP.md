# apply.leadpop.io Subdomain Setup

The `apply-funnel` branch is created and ready. Complete these final Vercel configuration steps:

## What's Already Done

✓ Created `apply-funnel` branch in the GitHub repo  
✓ In that branch, `index.html` is the quiz funnel  
✓ CNAME configured in Namecheap (you already did this)  
✓ Domain added in Vercel (you already did this)  

## Final Step: Point the Domain to the Branch

1. Go to [vercel.com dashboard](https://vercel.com/dashboard)
2. Select your LeadPop project
3. Go to **Settings** → **Domains**
4. Find `apply.leadpop.io` in the list
5. Click on it or click the **Edit** button
6. Change **Git Branch** from `main` to `apply-funnel`
7. Save

## How It Works

- `leadpop.io` → serves from `main` branch → `index.html` (homepage)
- `apply.leadpop.io` → serves from `apply-funnel` branch → `index.html` (quiz funnel)

Same repo, same Vercel project, different branches per domain.

## Result

Visit **https://apply.leadpop.io** — it will load the quiz funnel at the root with a clean URL.
