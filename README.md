# Vantinti Bojanam

Homestyle Andhra cloud kitchen website — single-page scroll story. Pure vegetarian meals delivered across Uppal, Habsiguda, Tarnaka, and Secunderabad in 30 minutes.

- **WhatsApp orders:** https://wa.me/917396960227
- **Phone:** +91 73969 60227
- **Address:** CH54+VM, Prashanth Nagar, Uppal, Hyderabad, Telangana 500039

## Stack
Static HTML + CSS + vanilla JS (with GSAP + Lenis via CDN). No build step. Deployed on Vercel.

## Local preview
Open `index.html` directly in a browser, or serve with any static server:
```bash
npx serve .
```

## Deploy
```bash
# First time only:
rm -rf .vercel
vercel link --yes --project vantinti-bojanam
cat .vercel/project.json  # verify projectName === "vantinti-bojanam"

# Every deploy after:
vercel --prod
```

Built by [PageStitches](https://stitchwebsite.com).
