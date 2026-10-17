# Launch + AI-search (ChatGPT / Gemini) checklist – ร้านนภาพร

Honest note: nobody can guarantee ChatGPT or Gemini will recommend a shop. They pull from Google/Bing indexes, Google Business Profile, Maps reviews and third-party mentions. The site is only one input. Order below = impact first.

## 0. Before anything (blockers)
1. Real domain (e.g. naphaporn.com / .co.th) + hosting (Cloudflare Pages / Netlify / Vercel – free). The claude.ai artifact link is not a good public home: not your domain, hard to index.
2. Replace YOUR-DOMAIN in index.html (add <link rel="canonical">), robots.txt, sitemap.xml, llms.txt.
3. Confirm facts on page: price units (per tray/box/kg?), whether ปูม้า is size or filling, ทองม้วน details, holiday closures. AI answers repeat what the site says – wrong facts get repeated.

## 1. Google Business Profile (biggest lever for "ร้านขนมจีบเยาวราช")
- Claim/verify the profile; add website URL, correct hours, phone, categories (Chinese restaurant, Dim sum restaurant).
- Upload 20+ real photos (shopfront, kitchen, each dish), add menu + prices, post weekly.
- Ask happy customers for reviews (QR at counter); reply to every review. Gemini leans heavily on this.

## 2. Make the site readable by AI (done in the files)
- Restaurant + Menu + AggregateRating + FAQPage JSON-LD, plain-text FAQ, address/hours/prices in HTML text (not images).
- robots.txt allows GPTBot / OAI-SearchBot / Google-Extended; llms.txt summary.
- Submit sitemap in Google Search Console and Bing Webmaster Tools (ChatGPT search uses Bing-style index).

## 3. Third-party mentions (what AI actually cites)
- Wongnai, Facebook page, Instagram, TikTok, Pantip, Tripadvisor, Lemon8 reviews; get food bloggers/Yaowarat guides to mention "ร้านนภาพร ซอยเจริญกรุง 16".
- Keep Name / Address / Phone identical everywhere.

## 4. Content to add later (needs your real info)
- Shop history (year, generation, why หอยจ้อ is the signature), shopfront + kitchen photos, "how to get here from MRT Wat Mangkon / Sam Yan" page, a page per signature dish.
- Page in English too (tourists ask AI in English).

## 5. Measure
- After 2–4 weeks ask ChatGPT/Gemini: "ร้านขนมจีบอร่อยเยาวราช", "หอยจ้อเยาวราชร้านไหนดี" and log results monthly; track GA4 + the data-layer events already on the page (nav/call/copy clicks).
