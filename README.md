# STI ग्रामीण सहायक (STI Gramin Sahayak)

A Hindi/English, mobile-first, low-data website for rural communities near IIT Jodhpur, based on the
STI Hub annual reports (2023-24, 2024-25). DC project by Sunny Meena and Aaryan Dahiya.

Features: bilingual toggle, "listen" (voice) buttons for low-literacy users, district/village finder,
plain-language service guides (rope and crafts, G-filter, SSPV, dung-mud hut), Artisan Card path,
sales channels, join form (email/WhatsApp/copy), installable and works offline after first visit.

Privacy: the reports contain beneficiary names and phone numbers. They are deliberately NOT included.

## Before publishing
1. Confirm villages and contact details with the STI Hub team (stih@cetsd.iitj.ac.in).
2. Set `CONFIG.whatsapp` in `index.html` if the team has a WhatsApp number.

## Deploy on GitHub Pages
```
git init && git add . && git commit -m "STI Gramin Sahayak website"
git branch -M main
git remote add origin https://github.com/<your-username>/sti-gramin-sahayak.git
git push -u origin main
```
Then: repo Settings > Pages > Source: `main` / root. Site: `https://<your-username>.github.io/sti-gramin-sahayak/`
