# Feedback #3 — Features / Services
**Subspace.money · Product Teardown · May 2026**

---

## (a) Observed

When you open the Subspace app or website, every feature is presented at the same visual weight. Shared subscriptions, gift cards, rentals, bill splitting, a subscription marketplace — all of it lands on the same screen with the same prominence. There is no hierarchy. Nothing tells the user what this product is fundamentally for.

A first-time visitor has no way of knowing that the shared subscription model — where you join a group plan for Netflix or Spotify and pay a fraction of the full price — is the product's core offering and the thing that makes Subspace genuinely different from anything else in the market.

Gift cards and rentals are real features inside the app, but they have direct, large-scale competition. Amazon and Flipkart already dominate gift cards. Zepto and Blinkit dominate instant delivery. These are not Subspace's moat. The shared subscription model is — and the product layout does not reflect that at all.

---

## (b) Problem

When everything is the MVP, nothing is the MVP. A product that does not lead with its strongest feature dilutes its own value proposition. A user landing on Subspace today sees gift cards before they see a reason to split a Netflix plan. That ordering is backwards. Gift cards are a commodity. Shared subscriptions at 80% off are not.

The current feature architecture is training users to think of Subspace as a discount aggregator — which is a weak, easily replicable position — rather than as the trusted infrastructure for group subscription plans in India, which is a strong and defensible one.

This also creates a retention problem. A user who comes for a gift card and has a fine experience has no reason to come back. A user who saves ₹400 a month on their Netflix bill through a shared plan is a sticky, recurring user. The product is not structured to drive users toward the high-retention feature first.

---

## Proposed Feature Hierarchy

| Priority | Feature | Rationale |
|----------|---------|-----------|
| **Core — full hero screen** | Shared Subscriptions | The MSP. Netflix, Spotify, Canva, YouTube Premium group plans. This is what makes Subspace different. |
| **Secondary strip** | Discounted Gift Cards | Useful add-on, visible after the core feature lands. Not a reason to open the app. |
| **Collapsed / Explore section** | Rentals + Local Marketplace | Discoverable, not front-loaded. Competes with Zepto and Blinkit — not a moat. |

---

## (c) Ship Instead

Restructure the home screen so that shared subscriptions take up the full hero section — a single bold headline, the top 6 platforms available, and a clear CTA like *"Join a plan, pay 20% of the cost."* Below that, a secondary strip for discounted gift cards. Everything else — rentals, marketplace, bill splitting — collapses into an "Explore more" section that is discoverable but does not compete for first-impression attention.

This is not about removing features. It is about making the product's information architecture reflect its actual competitive advantage. The user's first 10 seconds on Subspace should leave them with one thought: *"I can split my subscriptions here and save a lot of money."* Everything else is secondary.

The sequencing of information on the home screen is a product decision, not just a design decision. Right now it is communicating the wrong thing about what Subspace is. Fixing it costs nothing and changes the entire first impression.


<img width="1905" height="767" alt="image" src="https://github.com/user-attachments/assets/6519c932-b911-40d7-9ac9-d6ae9e36d516" />
