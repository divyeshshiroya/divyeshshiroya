<h1 align="center">Hi 👋, I'm Divyesh Shiroya</h1>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=F2B544&center=true&vCenter=true&width=700&lines=Backend+Engineer+%7C+Shopify+App+Developer;Node.js+%C2%B7+Express+%C2%B7+MongoDB;2+apps+live+on+the+Shopify+App+Store;Payments+confirmed+by+signed+webhooks%2C+not+buttons" />
    <img alt="Backend Engineer | Shopify App Developer" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=8A4F00&center=true&vCenter=true&width=700&lines=Backend+Engineer+%7C+Shopify+App+Developer;Node.js+%C2%B7+Express+%C2%B7+MongoDB;2+apps+live+on+the+Shopify+App+Store;Payments+confirmed+by+signed+webhooks%2C+not+buttons" />
  </picture>
</p>

<p align="center">
  <a href="https://YOUR-DOMAIN.com/"><img src="https://img.shields.io/badge/Portfolio-F2B544?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/divyesh-shiroya/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:shiroyadivyesh143@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://YOUR-DOMAIN.com/assets/Divyesh_Shiroya_Resume.pdf"><img src="https://img.shields.io/badge/Resume-PDF-333333?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume" /></a>
</p>

---

### `GET /about`

```http
GET /api/v1/engineer HTTP/1.1
Accept: application/json
```

```json
{
  "name": "Divyesh Shiroya",
  "role": "Backend Engineer | Shopify App Developer",
  "based_in": "Surat, India",
  "current": "Codetasker Technologies",
  "backend_since": 2022,
  "core": ["Node.js", "Express", "MongoDB"],
  "shopify": ["REST", "GraphQL", "Billing", "Polaris"],
  "now_building": "BrushPrint"
}
```

I build the server side of commerce: Node.js and Express services on MongoDB, custom Shopify apps on the REST, GraphQL and Billing APIs, and payment flows that trust a verified webhook, not a button.

- 🔭 **Backend Engineer | Shopify App Developer** at [Codetasker Technologies](https://codetasker.com/en-us) (since Aug 2024)
- 🛍️ Two apps live on the Shopify App Store: [**VideoVibe Shoppable Reels**](https://apps.shopify.com/videovibe) and [**CT Back in Stock | Preorder**](https://apps.shopify.com/backinstock-alerts)
- 🏗️ Currently building **BrushPrint**, a five-role order-to-delivery platform with Razorpay payments confirmed by signed webhooks
- 🌱 Learning **Serverless architecture, advanced AWS services and advanced Node.js**
- 💬 Ask me about **Node.js APIs, Shopify app development, auth & sessions, and payment webhooks**
- 📫 Reach me at **shiroyadivyesh143@gmail.com**
- 📍 Based in **Surat, India**

---

### `GET /experience`

| When | Role | Company |
| :-- | :-- | :-- |
| **Aug 2024 – Present** | Backend Engineer \| Shopify App Developer | [Codetasker Technologies](https://codetasker.com/en-us) |
| **Feb 2022 – Aug 2024** | Backend Developer | Crystal InfoTech |

---

### `GET /shopify/apps`

| App | What I built | Stack |
| :-- | :-- | :-- |
| [**VideoVibe Shoppable Reels**](https://apps.shopify.com/videovibe) | TikTok-style shoppable reels for storefronts. Uploads from device, Instagram, TikTok and Shopify, with video compression. Includes 5 customizable widgets with live preview, engagement tracking, and monthly/yearly plans on the Billing API. | MERN · Shopify Billing API |
| [**CT Back in Stock \| Preorder**](https://apps.shopify.com/backinstock-alerts) | Restock and price-drop alerts by email, SMS and push. Includes a "Notify Me" widget with demand analytics, preorders with partial payments, and low-stock alerts. | Node.js · Shopify Polaris |
| **Custom Shopify apps** | Custom apps at Codetasker on the REST and GraphQL APIs, covering inventory, orders, customers and shipping integrations. Optimized for lower API response times. | Node.js · Shopify REST & GraphQL |

---

### `GET /work/brushprint` · flagship, live in production

A role-based order-to-delivery platform for custom-printed products. It has five roles on one versioned API, and the server has the final word on every order.

- 👥 **Five role dashboards** (Sales Rep, Warehouse, Sales Admin, Finance, System Admin) share one versioned Express 5 API
- 🔐 **httpOnly cookie sessions with refresh-token rotation.** A burst of `401`s shares one renewal, so parallel requests never end a valid session.
- 🛡️ **Auditable sign-in:** every login records IP, device and location. Accounts can be locked (`423`), a location policy is enforced (`403`), and the audit log has no write route.
- 💳 **Razorpay QR codes and payment links.** An order moves forward only on an **HMAC-verified webhook**, and there is no "mark as paid" anywhere.
- 📦 **Order lifecycle state machine**, tiered pricing based on total quantity, server-side print-file generation, and a CSV/XLSX payment ledger and GST register

`Node.js` `Express 5` `MongoDB` `Mongoose 9` `Razorpay` `React`

---

### `GET /projects`

- **Management Information System (MIS):** task management where admins define dynamic task fields and review daily reports (`Pending → Approved | Resubmit`). *MERN*
- **KYC Management System:** an 80+ field KYC form with PDF and image uploads validated on the server, plus an admin verification queue. *MERN*

---

### `GET /skills`

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,js,mongodb,graphql,react,aws,azure,vercel,nginx,firebase,postman,git,github&perline=14" alt="Tech stack" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white" alt="Shopify" />
  <img src="https://img.shields.io/badge/Shopify_Polaris-008060?style=flat-square&logo=shopify&logoColor=white" alt="Shopify Polaris" />
  <img src="https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white" alt="Mongoose" />
  <img src="https://img.shields.io/badge/Razorpay-0C2451?style=flat-square&logo=razorpay&logoColor=white" alt="Razorpay" />
  <img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white" alt="DigitalOcean" />
</p>

| Layer | What I use |
| :-- | :-- |
| ⚙️ **Backend** | Node.js, Express.js, REST API design, versioned APIs, file uploads & validation, performance tuning |
| 🗄️ **Data** | MongoDB, Mongoose, ObjectId validation, CSV / XLSX exports |
| 🛍️ **Shopify** | App development, REST & GraphQL APIs, Billing API subscriptions, Polaris, storefront widgets, webhooks |
| 🔐 **Auth & security** | httpOnly cookie sessions, refresh-token rotation, account lockout, sign-in audit log, HMAC webhook verification |
| 💳 **Payments & alerts** | Razorpay QR codes, payment links & webhooks, email / SMS / push notifications |
| ☁️ **Deploy** | AWS EC2 & S3, Azure VM, DigitalOcean, Vercel, Git & GitHub |

---

### `GET /stats`

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=divyeshshiroya&show_icons=true&hide_border=true&theme=github_dark&title_color=F2B544&icon_color=F2B544" />
    <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=divyeshshiroya&show_icons=true&hide_border=true&title_color=8A4F00&icon_color=8A4F00" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=divyeshshiroya&hide_border=true&theme=dark&ring=F2B544&fire=F2B544&currStreakLabel=F2B544" />
    <img height="165" alt="GitHub streak" src="https://streak-stats.demolab.com?user=divyeshshiroya&hide_border=true&ring=8A4F00&fire=8A4F00&currStreakLabel=8A4F00" />
  </picture>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=divyeshshiroya&label=Profile%20views&color=F2B544&style=flat" alt="Profile views" />
</p>

<p align="center"><i>Backend first, Shopify fluent.</i></p>
