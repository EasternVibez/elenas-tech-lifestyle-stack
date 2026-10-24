# Site Strategy — Elena's Tech & Lifestyle Stack

## Brand Positioning
A clean, trusted resource where Elena recommends the exact tools and gear she actually uses — split into two focused engines so visitors self-select into the right category instantly.

---

## Engine 1: Workspace & AI Automation 🧠
**Audience:** Freelancers, small business owners, creators, solopreneurs automating their workflow.

**Commission Model:** Recurring SaaS (monthly/annual subscription commissions — often 20-50% recurring).

### Anchor Tools (Affiliate Programs)
| Tool | Category | Why It Converts |
|------|----------|----------------|
| Make.com | Automation | Visual no-code automation, generous free tier → upgrade path |
| Notion AI | Productivity | Viral team adoption, annual plan upsells |
| ConvertKit / Kit | Email Marketing | Creator-focused, high lifetime value |
| Jasper AI | AI Writing | High ticket, strong recurring |
| Descript | Podcast/Video editing AI | Creator niche, recurring |
| Loom | Async Video | Free → Team plan conversion |
| Surfer SEO | SEO + AI | Monthly recurring, strong niche |

**Content Hooks:**
- "My exact automation stack that saves me 10 hrs/week"
- "The 3 AI tools I pay for every single month"
- "Free → Paid upgrade path for solopreneurs"

---

## Engine 2: Lifestyle & Wellness Tech 💚
**Audience:** Health-conscious consumers, biohackers, remote workers wanting a better home environment.

**Commission Model:** One-time product commissions (Amazon Associates, ShareASale, brand direct) — 4-15%.

### Anchor Products (Affiliate Programs)
| Product | Category | Platform |
|---------|----------|----------|
| Oura Ring | Sleep/Recovery tracking | Direct affiliate |
| Hatch Restore | Smart alarm / sleep light | Amazon + Direct |
| Theragun / Therabody | Recovery tech | Direct / ShareASale |
| Eight Sleep Pod | Smart mattress | Direct affiliate (high ticket) |
| WHOOP | Fitness wearable | Direct affiliate |
| Ember Mug | Smart mug | Amazon Associates |
| Keurig / Breville Smart | Smart coffee | Amazon Associates |

**Content Hooks:**
- "Gadgets that actually changed my morning routine"
- "The sleep tech that fixed my recovery"
- "App-controlled gear worth the splurge"

---

## Monetization Priority
1. **Recurring SaaS commissions** — highest LTV, build first.
2. **High-ticket wellness** (Eight Sleep, Oura) — one sale = big payout.
3. **Amazon volume plays** — lower % but high-trust brand halo.

---

## Tracking & Link Strategy
- All affiliate URLs stored in `/public/links.json`.
- All outbound links cloaked via `/go/*` redirect rules in `/_redirects`.
- UTM parameters appended where affiliate programs allow.
- Never expose raw affiliate URLs on-page.

---

## Platform Stack (Zero-Cost)
| Layer | Tool | Cost |
|-------|------|------|
| Hosting | Cloudflare Pages | Free |
| Domain | `*.pages.dev` subdomain (or custom later) | Free |
| Source Control | GitHub (single repo) | Free |
| Analytics | Cloudflare Web Analytics | Free |
| CMS | JSON file (`links.json`) edited via GitHub | Free |
