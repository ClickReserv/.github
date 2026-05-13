<div align="center">

# ClickReserv

**AI-powered booking. 56 business templates. One integration.**

Multi-tenant booking SaaS with payments, POS, jukebox, CRM, and graph-based service recommendations.

[**🌐 reserv.click**](https://reserv.click)&nbsp;&nbsp;·&nbsp;&nbsp;[**🏠 GitHat platform**](https://githat.io)

</div>

---

## What ClickReserv is

A booking platform that ships with **56 business templates** — barbershops, salons, restaurants, gyms, clinics, dog groomers, photographers, escape rooms, and 48 more — each with the right calendar shape, deposit rules, service-recommendation graph, and POS catalog wired in on day one.

- **Bookings** with deposits, recurring series, waitlists, no-show fees
- **Payments** via [Sebastn](https://github.com/SebasTN-Rhys) Stripe Connect Express
- **POS** for products + drinks alongside services
- **Jukebox** Spotify-powered customer music requests (tier-gated)
- **CRM** with customer profiles, history, preferences
- **AI chat** with MCP tool integration for ops + bookings
- **Multi-language** (10 locales, AWS Translate auto-fallback)
- **Auth** by [GitHat](https://github.com/GitHat-IO)

## Security

- ✅ Verified domain (`reserv.click`, `www.reserv.click`)
- ✅ AWS-native: Route 53 → CloudFront (ACM cert) → EC2 (Caddy → Node)
- ✅ Stripe Connect Express via Sebastn (PCI scope minimized)
- ✅ Slot-reservation atomicity (ADR-001), feature gates (ADR-002)
- ✅ CAA records, signed commits, secret scanning

## Contact

Security: [security@reserv.click](mailto:security@reserv.click)
Support: [hello@reserv.click](mailto:hello@reserv.click)
