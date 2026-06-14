# 🌿 Stefan's Website Business — Start Here

This folder contains a **finished demo website for a real business**:
**Mansfield Patios & Landscaping** (Mansfield, Nottinghamshire). They have a
strong reputation but **no website** — a perfect first prospect.

---

## 1. The real business this demo is built for

| Detail | Value |
|--------|-------|
| Business | **Mansfield Patios & Landscaping** (also listed on Google as "Mansfield landscaping and sheds") |
| Owner | **Mr Daniel Silcock** ("Dan") — sole trader |
| Phone | **07739 546829** |
| Area | Mansfield, Forest Town, Mansfield Woodhouse, Sutton, Kirkby + surrounding |
| Checkatrade | **9.33/10 from 88 reviews**, member since 2016, £1,000 guarantee |
| Website | **None yet** — this is the opportunity |

Everything on the site is **real**, pulled from their Checkatrade profile:
- The **reviews** are genuine customer reviews (Bruce V and verified customers).
- The **photos** are the business's own job photos (patios, turf, fencing).
- The **services** match what they actually offer.

> The photos load from Google's image servers (where Checkatrade hosts them).
> They work fine, but for a site you're selling it's best to ask Dan for the
> original photos and save them in this folder — then ask Claude to swap them in.

> Dan has **no public email**. The site uses his phone + a contact form. Once a
> domain is bought, add an email (there's a commented line ready in `index.html`).

---

## 2. How to see the website in your browser

### Option A — just double-click it
1. Open `Documents\business_website` in File Explorer.
2. Double-click **`index.html`** → it opens in your browser. 🎉
   *(Needs internet — fonts and photos load online.)*

### Option B — the Launch preview inside Claude Code
When Claude edits the site, a **Launch preview** panel appears in the app —
click it to see the site live next to the chat. After any change press **F5**.

---

## 3. The plan, step by step

1. **Build the demo** ✅ (done — this is it).
2. **Call Dan on 07739 546829**:
   *"Hi Dan, I noticed Mansfield Patios & Landscaping doesn't have a website, so
   I built you a free demo using your real reviews and photos — can I send you
   the link to look at? No obligation."*
3. **Send him the link** (host it first — see below). If he likes it → **charge
   him**.
4. **Sort his domain** (e.g. `mansfieldpatios.co.uk`):
   - Buy it for him (~£8–12/year on **Namecheap**, **GoDaddy**, **123 Reg**) and
     bill it back, **or** teach him to buy it himself.

### Putting it online
You deploy the **`dist`** folder (it contains only the website files).

**Netlify Drop (fastest):** go to https://app.netlify.com/drop and drag the
`dist` folder onto the page. To *update* a site you already made, sign in, open
that site → **Deploys** tab → drag `dist` there (keeps the same link).

**GitHub Pages (free, good for a custom domain) — no coding needed:**
1. Make a free account at **github.com** (skip if you have one).
2. Click **+ → New repository**. Name it e.g. `mansfield-patios`, set **Public**,
   click **Create repository**.
3. On the new repo page click **uploading an existing file**. Drag in the two
   files from `dist` (`index.html` and `styles.css`). Click **Commit changes**.
4. Go to **Settings → Pages** (left menu).
5. Under **Build and deployment → Source** choose **Deploy from a branch**,
   pick branch **main** and folder **/ (root)**, then **Save**.
6. Wait ~1 minute, refresh. Your live link appears at the top:
   `https://<your-username>.github.io/mansfield-patios/`
7. To update later: repeat step 3 (upload the changed file, commit).
8. Custom domain later: **Settings → Pages → Custom domain** — type the domain
   you bought and follow the DNS instructions (ask Claude to help).

---

## 4. Making changes (no coding needed)

Open this folder in Claude Code (**Code** tab) and just ask in plain English:

- *"Swap in these real photos Dan sent."* (then share the files)
- *"Add Dan's email dan@mansfieldpatios.co.uk to the contact section."*
- *"Add more of their services, like driveways and decking."*
- *"How do I put this website online with a domain?"*

### Editing by hand
Open `index.html` in **Notepad** — the `<!-- comments -->` show what to change.
Colours live at the top of `styles.css` (`--forest` and `--gold`).

---

## Files in this folder
| File | What it is |
|------|------------|
| `index.html` | The website content |
| `styles.css` | The premium design (fonts, colours, animations, photos) |
| `README-FOR-STEFAN.md` | This guide |

---

## Quick recap
- **See it:** double-click `index.html`.
- **Pitch it:** call Dan on 07739 546829, send the link.
- **Sell it:** charge for the site, sort the domain, host free on Netlify/Cloudflare.

Good luck Stefan! 🚀
