RAMAN PALLA PORTFOLIO — SEO UPDATE KIT

Is ZIP mein 3 files hain jo website ke root folder mein rakhni hain:
1. robots.txt
2. sitemap.xml
3. favicon.svg

STEP 1 — VS CODE
- Apna raman_palla_portfolio folder VS Code mein kholo.
- ZIP extract karo.
- robots.txt, sitemap.xml aur favicon.svg ko index.html ke saath same root folder mein copy karo.
- assets folder ke andar mat rakhna.

STEP 2 — index.html META TAGS
- index.html ke <head> section mein SEO-HEAD-SNIPPET.txt kholo.
- Wahan diye gaye naye description aur title se existing description aur title replace karo.
- Baaki tags ko bhi <head> ke andar, </head> se pehle paste karo.
- Dhyan: purana duplicate description/title mat chhodna.

STEP 3 — SAVE AND PUSH
VS Code terminal mein ye commands chalao:

git add .
git commit -m "Add portfolio SEO metadata and sitemap"
git push

STEP 4 — LIVE VERIFY
Deployment complete hone ke baad ye URLs kholo:
https://nikkasarmal.github.io/raman-palla-portfolio/robots.txt
https://nikkasarmal.github.io/raman-palla-portfolio/sitemap.xml
https://nikkasarmal.github.io/raman-palla-portfolio/favicon.svg

STEP 5 — GOOGLE SEARCH CONSOLE
- https://search.google.com/search-console/ kholo.
- Google account se sign in karo.
- URL-prefix property add karo:
  https://nikkasarmal.github.io/raman-palla-portfolio/
- Ownership verification ke liye Google jo HTML file ya meta tag de, use website mein add karke push karo.
- Verify hone ke baad Sitemaps section mein sitemap.xml submit karo.
- URL Inspection mein homepage URL paste karke Request Indexing select karo.

IMPORTANT
- SEO setup Google ranking ki guarantee nahi deta.
- Google ko crawl/index karne mein kuch din ya kabhi zyada waqt lag sakta hai.
- Sitemap mein abhi sirf homepage hai kyunki portfolio single-page website hai.
- Google Search Console verification abhi tumhare Google account se karni hogi; main account ke andar action nahi kar sakta.
