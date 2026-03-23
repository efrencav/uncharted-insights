---
name: Mobile responsiveness work needed
description: Mobile layout has known issues flagged for future fix, triggered by QR code traffic potential
type: project
---

Mobile responsiveness on index.html needs attention before or shortly after QR code campaign drives mobile traffic.

**Why:** Nav links disappear on mobile (<900px breakpoint) with no hamburger menu replacement, and some content cuts off on narrow screens. User noticed this and wants to address it if QR code usage picks up.

**How to apply:** When the user asks to work on mobile, the known issues are:
1. No mobile nav — `.nav-links { display: none; }` at 900px with no hamburger/slide-out replacement
2. Hero section hides the Jim photo on mobile (`display: none`)
3. Large section padding may clip content on narrow screens
4. Typography and fixed widths likely need scaling adjustments
