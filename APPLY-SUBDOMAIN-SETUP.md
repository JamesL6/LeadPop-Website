# apply.leadpop.io Subdomain Setup

The `vercel.json` rewrite rule is already configured. Complete these steps to go live:

## Step 1: Add the custom domain in Vercel

1. Go to [vercel.com dashboard](https://vercel.com/dashboard)
2. Select your LeadPop project
3. Go to **Settings** → **Domains**
4. Click **Add**
5. Enter `apply.leadpop.io`
6. Vercel will show the CNAME target (usually `cname.vercel-dns.com`)

## Step 2: Add CNAME record in Namecheap

1. Log into [Namecheap](https://www.namecheap.com)
2. Domain List → **leadpop.io** → **Manage** → **Advanced DNS**
3. Click **Add New Record**
4. Set:
   - **Type:** CNAME
   - **Host:** `apply`
   - **Value:** `cname.vercel-dns.com.` (include the trailing dot)
   - **TTL:** Automatic
5. Save

## Step 3: Verify

- Back in Vercel Settings → Domains, the domain should show as **Valid** within 1–5 minutes
- SSL certificate is issued automatically
- Visit **https://apply.leadpop.io** — it will load the quiz funnel at the root
