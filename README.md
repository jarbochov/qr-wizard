# QR Code Wizard

A clean, zero-backend static QR code generator and shareable QR viewer.

- **Wizard (`/wizard/`):** Build QR codes for URLs, plain text, WiFi, email, phone, SMS, vCards, calendar events, and geo coordinates with custom colors, transparency, dot/corner styles, logo overlays, presets, and PNG/SVG/clipboard export.
- **Viewer (`/index.html?data=...`):** Frameless QR renderer driven by URL query parameters (visiting `/index.html` without `?data=` redirects to `/wizard/`).

> **Note:** QR codes encode static text only. If you may need to change a link's destination after printing or sharing, encode a **URL forwarder** — ideally a **redirect on a domain you control**.
