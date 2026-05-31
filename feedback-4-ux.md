# Feedback #4 — UX
**Subspace.money · Product Teardown · May 2026**

---

## (a) Observed

Two specific things stood out immediately on the website and app that do not belong there.

**First** — the top left corner of the homepage shows a location selector with the text *"Delivery in 11 minutes."* This is a direct copy of the UI pattern used by Zepto, Blinkit, and Swiggy Instamart. But Subspace is not a quick-commerce app. Its core product is shared digital subscriptions — Netflix, Spotify, Canva. These are not physical items. Nothing is being delivered in 11 minutes. The only thing that could arguably trigger this is the rentals feature, which is available only in select cities and is not the reason most users are on the platform.

A first-time visitor seeing "Delivery in 11 minutes" alongside a Netflix subscription tile is immediately confused about what kind of app this is.

**Second** — the user profile asks for a full delivery address including flat number, floor, area, and landmark. Again, this makes sense for a rental or physical delivery flow, but it appears as part of the general account setup, not gated inside the rentals section. A user who signs up purely to split a Netflix subscription has no reason to give their home address to a fintech app — and many won't.

### Specific UX friction points

| Element | Location | Problem |
|---------|----------|---------|
| "Delivery in 11 minutes" banner | Homepage, top left | Quick-commerce UI pattern on a digital subscription app — creates identity confusion before the user reads a single feature |
| Address fields (flat no., floor, area, landmark) | General profile / account setup | Unnecessary data ask for the primary ICP (subscription users). Silently kills conversions among privacy-conscious users |
| Visual identity — deep indigo (#4F46E5) | Entire app and website | Standard SaaS-blue. Cold, generic, no warmth for a savings app targeting young Indians |

---

## (b) Problem

The "Delivery in 11 minutes" banner is not just a cosmetic issue — it is a positioning problem. In the first 3 seconds of landing on a product, a user is forming a mental model of what this app is. If that first signal reads like Zepto or Blinkit, the user does not understand that this is a subscription management platform. It creates friction before they even read a single feature description. For a product whose primary use case is entirely digital and async, this UI element actively lies about what the product is.

The address collection problem is a trust issue. Fintech apps in India already face high user skepticism around data collection. Asking for a home address before the user has made a single transaction — and without explaining why — will silently kill conversions, especially among the college student segment who are the core ICP. Many will quietly abandon the sign-up flow rather than ask why their address is needed to split a Spotify plan.

Both of these are zero-effort fixes that have outsized impact on first impressions and conversion. They are not asking for a new feature or a redesign sprint — they are asking for two things to be removed.

---

<img width="611" height="85" alt="image" src="https://github.com/user-attachments/assets/348977c6-070a-4803-9fd9-8b56d7773c7b" />


## (c) Ship Instead

**Remove the delivery location banner** entirely from the homepage. If the rentals feature needs a location, ask for it contextually — only when a user taps into the rentals section for the first time. The homepage should open clean, with the product's core value front and center.

**Move the address fields** out of general account setup entirely. Gate them behind the rentals flow as a just-in-time ask. For the subscription and gift card user — which is most users — the profile should only need a name and a phone number. That is all the trust surface they need to transact.

**On the visual identity** — the current indigo is cold and generic. Given that the core ICP is young, price-conscious Indians who are used to apps like Zepto, CRED, and Swiggy, the UI language should feel warmer and more personal. A palette built around warm beige as the base surface with a muted amber-orange as the primary accent would feel approachable and distinct without being loud. It would also visually separate Subspace from every other blue fintech app on the Play Store — which is itself a positioning move.

The goal is not something photogenic or flashy. It is something subtle, clean, and easy on the eye — a product that feels like it was designed for the person using it, not for a B2B SaaS demo.
