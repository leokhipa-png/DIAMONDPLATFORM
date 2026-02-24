# 💎 LUMYN — The Diamond Industry Revolution

> **The world's first AI-powered marketplace connecting customers directly with verified diamond designers, dealers and manufacturers. No middlemen. No compromises. 100% authentic, GIA-certified natural diamonds.**

---

## 🌍 Live URLs (after Netlify deployment)

| Page | URL | File |
|------|-----|------|
| Landing Page | `yoursite.netlify.app/` | `diamond-platform.html` |
| Customer Portal | `yoursite.netlify.app/portal` | `lumyn-chatroom-ordering.html` |
| Community Feed | `yoursite.netlify.app/feed` | `lumyn-community-feed.html` |
| Order Flow | `yoursite.netlify.app/order` | `lumyn-chatroom-ordering.html` |
| Chat Rooms | `yoursite.netlify.app/chat` | `lumyn-chatroom-ordering.html` |
| Order Tracker | `yoursite.netlify.app/track` | `lumyn-chatroom-ordering.html` |

---

## 📁 Project File Structure

```
lumyn/
├── diamond-platform.html         ← Main landing page
├── lumyn-chatroom-ordering.html  ← Customer portal (chat + ordering + tracking)
├── lumyn-community-feed.html     ← Social community feed
├── netlify.toml                  ← Netlify deployment configuration
└── README.md                     ← This file (documentation)
```

---

## 🚀 How to Deploy (Netlify)

### Option A — Drag & Drop (Easiest, no coding needed)

1. Go to [netlify.com](https://netlify.com) and create a free account
2. On the dashboard, find the box that says **"Drag and drop your site folder here"**
3. Drag your entire `lumyn` folder into that box
4. Wait 10 seconds — your site is live
5. Netlify gives you a free URL like `lumyn-abc123.netlify.app`

### Option B — GitHub (Recommended for updates)

1. Go to [github.com](https://github.com) and create a free account
2. Create a new repository called `lumyn`
3. Upload all your files into that repository
4. Go to Netlify → **Add new site** → **Import from GitHub**
5. Select your `lumyn` repository
6. Click **Deploy** — done
7. Every time you update a file on GitHub, Netlify automatically redeploys

### Option C — Netlify CLI (For developers)

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to your Netlify account
netlify login

# Deploy from your project folder
cd lumyn
netlify deploy --prod
```

---

## 🔗 Custom Domain Setup

Once deployed, connect your own domain (e.g. `lumyn.com`):

1. Buy your domain from [Namecheap](https://namecheap.com) or [GoDaddy](https://godaddy.com)
2. In Netlify dashboard → **Domain settings** → **Add custom domain**
3. Type in your domain name and click **Verify**
4. Netlify will give you nameservers — copy them
5. Go to your domain registrar (Namecheap/GoDaddy) → paste the nameservers
6. Wait up to 24 hours for the domain to go live
7. Netlify provides a **free SSL certificate** (the padlock 🔒) automatically

---

## 💡 What Each Page Does

### 1. `diamond-platform.html` — Landing Page
The main marketing and introduction page for LUMYN. Includes:
- Hero section with AI design concept
- How the platform works (Customer → Designer → Dealer → Manufacturer → Delivery)
- What the new generation wants from the diamond industry
- Platform features (AI design, live chat, verified portfolios, escrow payments)
- Trust and verification checklist (business certificate, passport, GIA certs, address)
- Membership pricing (Customer free / Designer $49/month / Manufacturer $149/month)
- Order tracker preview
- Waitlist and sign-up call to action

### 2. `lumyn-chatroom-ordering.html` — Customer Portal
The full working customer experience. Includes:
- **AI Design Studio** — customer describes their jewellery in plain language, AI generates designs to choose from, designer recommendations appear with ratings and location
- **Live Chat Rooms** — private, recorded chat rooms between customer and designer, dealer, or LUMYN support. All conversations stored for security. File sharing (CAD drawings, GIA certificates) inside chat
- **4-Step Order Flow:**
  - Step 1: Jewellery type, design, metal, stone cut, ring size, special instructions
  - Step 2: Delivery address and shipping method (Standard / Express / White Glove)
  - Step 3: Payment — Card, Bank Transfer, Crypto, Mobile Pay, multi-currency, Escrow protection
  - Step 4: Order confirmation with production timeline
- **Order Tracker** — live timeline from payment to delivery, all documents stored (GIA cert, CAD design, invoice, shipping insurance)
- **Feedback & Rating** — 5-star rating and written review submitted after delivery

### 3. `lumyn-community-feed.html` — Community Feed
The LUMYN social network — like Facebook but exclusively for the diamond world. Includes:
- **Stories bar** — circular story highlights for designers, dealers and manufacturers
- **Create Post** — any verified member can post text, photos, videos, tag people
- **Post types:**
  - Designer Showcases — photo galleries of completed authentic pieces
  - Dealer Listings — natural GIA-certified stone cards with specs and enquiry button
  - Industry News — articles and market updates
  - Customer Reviews — verified purchase posts with unboxing photos
  - Manufacturer Updates — studio news and production capacity
- **Reactions** — 6 custom diamond-themed reactions (💎🔥😍💍✨👑)
- **Comments** — live threaded comments with like and reply
- **Share & Save** — share posts to followers, save to personal collection
- **Follow system** — follow designers, dealers and manufacturers
- **Live activity ticker** — real-time feed of what is happening on the platform
- **Trending hashtags** — discover content by tag
- **Community stats** — live member counts by category
- **Feed tabs** — filter by All / Designers / Dealers / Industry News / Customers
- **Filter chips** — New Designs / Stones for Sale / Industry News / Conflict-Free / Customer Reviews / Trending

---

## 🔒 Trust & Safety Features

Every professional on LUMYN must submit before listing:

| Document | Required |
|----------|----------|
| Business registration certificate | ✅ Mandatory |
| Passport or national ID | ✅ Mandatory |
| Physical workshop/studio address | ✅ Mandatory |
| GIA diamond certificate (per stone) | ✅ Mandatory |
| Portfolio authentication (designers) | ✅ Quarterly review |

- All chat conversations are **recorded and stored** for dispute resolution
- **Escrow payments** — funds held securely until customer confirms delivery and satisfaction
- **No anonymous sellers** — every person in the chain is verified and identifiable

---

## 💳 Business Model & Revenue

| Revenue Stream | Details |
|---------------|---------|
| Customer accounts | Free |
| Designer/Dealer monthly subscription | $49/month |
| Manufacturer monthly subscription | $149/month |
| Designer/Dealer joining fee | $199 one-time |
| Manufacturer joining fee | $499 one-time |
| Platform transaction fee | 3.5% per order |
| Express/White Glove shipping | $45 – $180 per order |

---

## 🌐 Who Is LUMYN For?

| User Type | What They Do on LUMYN |
|-----------|----------------------|
| **Customers** | Describe jewellery to AI, browse designs, chat with designers, place orders, track delivery, leave reviews, post on community feed |
| **Designers** | List verified portfolio, receive AI-matched commissions, chat with customers, manage orders, post showcases on feed |
| **Dealers** | List GIA-certified natural stones, supply designers and direct buyers, post new stone arrivals on feed |
| **Manufacturers** | Receive production orders from designers, manage cutting/polishing/casting capacity, post studio updates on feed |

---

## 🛠️ Future Development Roadmap

When you are ready to build the full backend, here is what needs to be developed:

### Phase 1 — Backend & Accounts
- User authentication (sign up, login, roles: customer / designer / dealer / manufacturer)
- Database for users, orders, messages, posts (recommended: PostgreSQL)
- File storage for GIA certificates, CAD files, portfolio images (recommended: AWS S3 or Cloudflare R2)

### Phase 2 — Real-Time Features
- Live chat using WebSockets (recommended: Socket.io or Pusher)
- Real-time order tracking updates
- Push notifications for messages, order updates, reactions

### Phase 3 — Payments
- International payments (recommended: Stripe)
- Local African payments (recommended: Flutterwave or Paystack for Botswana, SA, Nigeria)
- Escrow logic — hold funds, release on delivery confirmation
- Multi-currency support

### Phase 4 — AI Integration
- Connect real AI design generation (recommended: Anthropic Claude API or OpenAI)
- Image generation for jewellery designs (recommended: DALL-E or Midjourney API)
- AI-powered designer matching based on customer brief

### Phase 5 — Mobile App
- iOS and Android app (recommended: React Native)
- Push notifications
- In-app camera for uploading reference images

### Recommended Tech Stack

```
Frontend:     React.js or Next.js
Backend:      Node.js + Express or Python + FastAPI
Database:     PostgreSQL (orders, users) + Redis (real-time)
File Storage: AWS S3 or Cloudflare R2
Payments:     Stripe + Flutterwave
Real-time:    Socket.io
AI:           Anthropic Claude API
Hosting:      Vercel (frontend) + Render or Railway (backend)
Domain:       Cloudflare (DNS + SSL + CDN)
```

---

## 📞 Contact & Support

| Role | Contact |
|------|---------|
| Platform Owner | Add your email here |
| Developer | Add developer contact here |
| Trust & Safety | Add safety team email here |
| Press & Media | Add press contact here |

---

## 📜 Legal Notes

- All diamonds listed on LUMYN must be **natural and GIA-certified**. No exceptions.
- All professionals must submit valid identity documents before listing
- All transactions are protected by LUMYN escrow — funds only released on confirmed delivery
- All chat conversations are recorded and stored for a minimum of 3 years for dispute resolution
- LUMYN reserves the right to remove any listing, post or member that violates platform standards

---

*© 2025 LUMYN. All rights reserved. The Diamond Revolution.*

> **"Tell us what you desire."**
