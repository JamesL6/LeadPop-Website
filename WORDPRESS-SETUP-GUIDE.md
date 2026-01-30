# WordPress Setup Guide - LeadPop Website

## Quick Overview
You'll be pasting HTML content into WordPress pages and adding CSS globally. This takes about 1-2 hours total.

## Simplified Approach (Recommended)
✅ **Use WordPress built-in "Additional CSS"** (no plugins needed for CSS!)
✅ **Paste clean HTML** (body content only) into Gutenberg Code Editor or Elementor HTML widget
✅ **Add CSS once globally** - all pages use it automatically
✅ **No CSS duplication** - faster, cleaner, easier to maintain

**You DON'T need:**
- ❌ Custom CSS plugins (WordPress has it built-in)
- ❌ CSS duplicated on every page
- ❌ Complex setup

---

## STEP 1: WordPress Basic Setup (10 minutes)

### A. Install WordPress Theme
1. Go to **Appearance → Themes → Add New**
2. Search for **"Astra"** (free, lightweight, works great with custom HTML)
3. Install and Activate
4. Go to **Appearance → Customize**
5. Navigate to **Header Builder** → Delete all header elements
6. Navigate to **Footer Builder** → Delete all footer elements
7. **Publish** changes

### B. Install Required Plugins (Optional)
Go to **Plugins → Add New** and install:
- **Rank Math** (for SEO - required)
- **Insert Headers and Footers** (optional - makes adding header/footer easier)

**Note:** You DON'T need CSS/JS plugins - WordPress has built-in Additional CSS!

---

## STEP 2: Add Global CSS (5 minutes)

**Using Built-in WordPress Feature (No Plugin Needed!):**

1. Go to **Appearance → Customize → Additional CSS**
2. Open file: `WORDPRESS-GLOBAL-CSS.css` (I'll create this for you)
3. Copy ALL the CSS
4. Paste into Additional CSS box
5. Click **Publish**

**This adds CSS globally to ALL pages - no duplication needed!**

---

## STEP 3: Add Global Header & Footer (15 minutes)

### A. Add Header
1. Go to **Settings → Insert Headers and Footers**
2. In the **"Scripts in Header"** section
3. Open file: `WORDPRESS-HEADER.html` (I'll create this)
4. Paste the header HTML
5. Save

### B. Add Footer
1. In same page, scroll to **"Scripts in Footer"** section
2. Open file: `WORDPRESS-FOOTER.html` (I'll create this)
3. Paste the footer HTML
4. Save

### C. Add JavaScript
1. Scroll to **"Scripts in Footer"** section (below footer HTML)
2. Wrap the JavaScript in `<script>` tags
3. Open file: `WORDPRESS-SCRIPTS.js` (I'll create this)
4. Paste inside `<script></script>` tags
5. Save

---

## STEP 4: Create Pages (40 minutes)

### For EACH page (Home, About, How It Works, Book Call, Privacy, Terms):

**Using Gutenberg (Default Editor):**
1. Go to **Pages → Add New**
2. Add page title (e.g., "Home")
3. Click **⋮ (three dots)** in top right → **Code Editor**
4. Open the corresponding file: `WORDPRESS-PAGE-[name].html`
5. Copy the HTML content (body only, NO `<style>` tags)
6. Paste into WordPress code editor
7. **Save Draft** (don't publish yet)

**Using Elementor (If Installed):**
1. Create new page
2. Edit with Elementor
3. Add **HTML widget**
4. Paste the HTML content
5. Save

**Note:** Since you added CSS globally in Step 2, you only paste the HTML body content - no CSS duplication!

**Files I'll create:**
- `WORDPRESS-PAGE-HOME.html`
- `WORDPRESS-PAGE-ABOUT.html`
- `WORDPRESS-PAGE-HOW-IT-WORKS.html`
- `WORDPRESS-PAGE-BOOK-CALL.html`
- `WORDPRESS-PAGE-PRIVACY.html`
- `WORDPRESS-PAGE-TERMS.html`

---

## STEP 5: Upload Images (10 minutes)

1. Go to **Media → Add New**
2. Upload ALL images from your `Photos/` folder
3. Upload all favicons and logo files
4. Note: Image paths in HTML already use relative paths, so they should work

**Upload these files:**
- james-headshot-hq.png
- isaac-.jpeg
- dylan-purcell.png
- All favicon files (favicon.ico, etc.)
- leadpop-logo-180x180.png
- leadpop-social-share-1200x630.png

---

## STEP 6: Configure Homepage & Settings (5 minutes)

### A. Set Homepage
1. Go to **Settings → Reading**
2. Select **"A static page"**
3. Choose **"Home"** as Homepage
4. Save changes

### B. Set Permalinks
1. Go to **Settings → Permalinks**
2. Select **"Post name"**
3. Save changes

### C. Create Menu
1. Go to **Appearance → Menus**
2. Create new menu: "Main Navigation"
3. Add pages: Home, About, How It Works, Book a Call
4. Check **"Primary Menu"** location
5. Save menu

---

## STEP 7: Update Internal Links (10 minutes)

In each page, update links to use WordPress permalinks:

**Find and replace in ALL pages:**
- `index.html` → `/` or `<?php echo home_url(); ?>`
- `about.html` → `/about/`
- `how-it-works.html` → `/how-it-works/`
- `book-call.html` → `/book-call/`
- `privacy-policy.html` → `/privacy-policy/`
- `terms-of-service.html` → `/terms-of-service/`

**OR** just use relative paths:
- `index.html` → leave as `/`
- `about.html` → `/about`
- etc.

---

## STEP 8: Final Checks & Launch (10 minutes)

### A. Test Navigation
- [ ] Click through all menu links
- [ ] Test mobile menu
- [ ] Verify all CTAs go to Book Call page

### B. Test Forms/Calendar
- [ ] Book Call page calendar loads correctly
- [ ] Test booking flow

### C. Mobile Test
- [ ] View on mobile device or browser DevTools
- [ ] Test all interactions

### D. SEO Setup (RankMath/Yoast)
- [ ] Set homepage title & description
- [ ] Set each page meta title & description
- [ ] Upload logo for Google (leadpop-logo-180x180.png)
- [ ] Upload social share image (leadpop-social-share-1200x630.png)

### E. Publish
- [ ] Publish all pages
- [ ] Test live site
- [ ] Share URL

---

## Troubleshooting

**CSS not working?**
- Make sure you published the Additional CSS
- Clear browser cache (Cmd+Shift+R)
- Check for CSS conflicts with theme

**Header/Footer not showing?**
- Make sure you disabled Astra's default header/footer
- Check Insert Headers and Footers plugin is active

**Images not loading?**
- Upload images to Media Library
- Update paths to WordPress media URLs
- Or use relative paths from wp-content/uploads

**Links broken?**
- Update all .html links to WordPress permalinks
- Use `/about/` not `/about.html`

---

## Next Steps

Once I create the WordPress-ready files, you'll just:
1. Copy/paste CSS once (global)
2. Copy/paste header/footer once (global)
3. Copy/paste each page content (6 pages)
4. Upload images
5. Configure settings
6. Launch!

**Ready for me to create all the WordPress-ready files?**
