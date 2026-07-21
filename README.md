<svg width="1200" height="280" viewBox="0 0 1200 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgDark" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#070B14"/>
      <stop offset="100%" stop-color="#0A1628"/>
    </linearGradient>
    <radialGradient id="glowDark" cx="78%" cy="35%" r="55%">
      <stop offset="0%" stop-color="#0A66C2" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#0A66C2" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="cardStroke" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#3B82F6" stop-opacity="0.5"/>
      <stop offset="100%" stop-color="#3B82F6" stop-opacity="0.05"/>
    </linearGradient>
    <filter id="soften"><feGaussianBlur stdDeviation="0.4"/></filter>
  </defs>

  <rect width="1200" height="280" fill="url(#bgDark)"/>
  <rect width="1200" height="280" fill="url(#glowDark)"/>

  <!-- fine grid texture -->
  <g opacity="0.04" stroke="#8FB8E8" stroke-width="1">
    <path d="M0 70 H1200 M0 140 H1200 M0 210 H1200"/>
    <path d="M300 0 V280 M600 0 V280 M900 0 V280"/>
  </g>

  <!-- floating glass cards -->
  <g transform="translate(860,40) rotate(-8)">
    <rect width="150" height="90" rx="14" fill="#8FB8E8" fill-opacity="0.05" stroke="url(#cardStroke)" stroke-width="1.2"/>
    <rect x="16" y="18" width="70" height="8" rx="4" fill="#3B82F6" fill-opacity="0.55"/>
    <rect x="16" y="34" width="100" height="6" rx="3" fill="#8FB8E8" fill-opacity="0.3"/>
    <rect x="16" y="48" width="60" height="6" rx="3" fill="#8FB8E8" fill-opacity="0.2"/>
  </g>
  <g transform="translate(990,120) rotate(6)">
    <rect width="120" height="76" rx="12" fill="#8FB8E8" fill-opacity="0.05" stroke="url(#cardStroke)" stroke-width="1.2"/>
    <circle cx="24" cy="24" r="9" fill="#3B82F6" fill-opacity="0.55"/>
    <rect x="42" y="18" width="60" height="6" rx="3" fill="#8FB8E8" fill-opacity="0.35"/>
    <rect x="16" y="46" width="88" height="6" rx="3" fill="#8FB8E8" fill-opacity="0.2"/>
  </g>
  <g transform="translate(870,150) rotate(-3)">
    <rect width="100" height="64" rx="10" fill="#8FB8E8" fill-opacity="0.04" stroke="url(#cardStroke)" stroke-width="1"/>
    <rect x="14" y="14" width="40" height="40" rx="8" fill="#3B82F6" fill-opacity="0.4"/>
  </g>

  <!-- wordmark -->
  <text x="80" y="128" font-family="Helvetica, Arial, sans-serif" font-size="58" font-weight="700" fill="#F5F7FA" filter="url(#soften)">
    Ahmed<tspan fill="#3B82F6">Verse</tspan>
  </text>
  <text x="82" y="164" font-family="Helvetica, Arial, sans-serif" font-size="17" letter-spacing="2.5" fill="#8FB8E8" fill-opacity="0.8">
    FRONTEND DEVELOPER  ·  NEXT.JS  ·  PREMIUM UI / UX
  </text>

  <!-- thin accent rule -->
  <rect x="82" y="184" width="64" height="3" rx="1.5" fill="#3B82F6"/>
</svg>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg">
  <img alt="AhmedVerse banner" src="./assets/banner-dark.svg" width="100%">
</picture>

<br/>

<table>
<tr>
<td width="55%" valign="top">

### Frontend developer who cares more about the last 10% than the first 90%.

I build with Next.js and TypeScript, but the part I actually obsess over is
what happens after the feature "works" — the spacing that's a pixel off,
the transition that's 40ms too slow, the empty state nobody designed.
That gap is where I spend most of my time.

Right now I'm building **BlazeCart**, a full storefront with Stripe,
auth, wishlist, and a dark/light theme system I've broken and fixed more
times than I'd like to admit — which is exactly how you learn what
actually goes wrong in production UI.

**Studying:** Computer Science
**Building:** BlazeCart 🛒
**Learning:** Next.js 16, Prisma, system design

</td>
<td width="45%" valign="top" align="center">

<img src="./assets/terminal.svg" width="100%">

</td>
</tr>
</table>

---

### What I actually reach for

<details>
<summary><b>Frontend</b> — click to expand</summary>
<br>

React · Next.js · TypeScript · Tailwind CSS · Bootstrap

</details>

<details>
<summary><b>Backend</b> — click to expand</summary>
<br>

Node.js · Express.js · Firebase · Supabase

</details>

<details>
<summary><b>Data</b> — click to expand</summary>
<br>

MongoDB · PostgreSQL · Prisma

</details>

<details>
<summary><b>Tools</b> — click to expand</summary>
<br>

Git · GitHub · VS Code · Vercel · Figma · Postman

</details>

---

### Featured work

<table>
<tr>
<td width="33%" valign="top">

**🛒 BlazeCart**
*Premium ecommerce platform*

`role` full-stack build
`stack` Next.js · Stripe · Prisma
`shipped` Auth, wishlist, dark/light theme, advanced search & filtering

</td>
<td width="33%" valign="top">

**🤖 Helplytics AI**
*AI SaaS dashboard*

`role` frontend + integration
`stack` Next.js · TypeScript · OpenAI
`shipped` Auth, analytics dashboard, embedded AI chat

</td>
<td width="33%" valign="top">

**🌐 AhmedVerse**
*Personal portfolio*

`role` design + build
`stack` React · Framer Motion · Tailwind
`shipped` Glassmorphism UI, motion system, full responsiveness

</td>
</tr>
</table>

---

### The numbers, for what they're worth

<img src="https://github-readme-stats.vercel.app/api?username=ahmeddev812&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=0A66C2&icon_color=3B82F6&text_color=c9d1d9&hide_rank=true" height="150">

*(Green squares are a rough proxy for effort, not a substitute for it.)*

---

### Now → Later

| Now | Later |
|---|---|
| Shipping BlazeCart's checkout + theme fixes | Contributing to an open-source design system |
| Learning Prisma relations properly, not by trial-and-error | Going deeper on backend architecture |
| Cleaning up motion consistency across pages | Writing about the UI decisions, not just the code |

---

> If it looks simple, it probably wasn't. That's usually the point.

<br>

<div>

**Reach me:** [GitHub](https://github.com/ahmeddev812) · LinkedIn *(add your link)* · Email *(add yours)*

</div>
