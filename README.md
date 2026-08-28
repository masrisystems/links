<div align="center">

# ⚡ Masri Systems — Links Hub

**Lightweight, privacy-first, self-hosted link-in-bio hub connecting all Masri Systems flagships, services, and social platforms.**

[![Live Site](https://img.shields.io/badge/Live-links.masrisystems.com-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://links.masrisystems.com)
[![PageSpeed Score](https://img.shields.io/badge/PageSpeed-100%2F100-brightgreen?style=for-the-badge&logo=lighthouse&logoColor=white)](https://pagespeed.web.dev/analysis/https-links-masrisystems-com/17ex80ryq4?form_factor=mobile)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)
[![Docker](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)](docker/)

[**🌐 Live Hub**](https://links.masrisystems.com) • [**🏢 Main Flagship**](https://masrisystems.com) • [**📄 Resume & Portfolio**](https://resume.masrisystems.com) • [**✍️ Technical Blog**](https://masrisystems.com/blog)

</div>

---

## 🚀 Overview

`masrisystems/links` is the official link aggregator and Linktree alternative for **Masri Systems** ([links.masrisystems.com](https://links.masrisystems.com)). Built from the fundamentals with zero heavy framework overhead, it serves as a central gateway for client discovery calls, active software projects, service catalogues, and verified social media channels.

### ✨ Highlights & Features

- 🏎️ **100/100 Lighthouse Performance:** Pure Vanilla HTML5 & CSS with zero JavaScript dependencies. Instant load times on all network tiers.
- 🌓 **Adaptive Theme Engine:** Native support for `system-preference`, `dark`, and `light` modes with automatic contrast stroke boundaries.
- 🎯 **Advanced SEO & Local SEO:** Built-in `Schema.org` (LocalBusiness / ProfessionalService / Person) structured data targeting Oldenburg, Germany & remote international clients.
- 🔒 **Privacy-First & Self-Hosted:** No third-party trackers, no cookies, strictly self-hosted under EU data sovereignty.
- 🐳 **Docker & Multi-Platform Deployment Ready:** Ships with standard Docker Compose recipes, Nginx configs, and one-click cloud integration.

---

## 🛠️ Project Structure

```text
├── css/
│   ├── brands.css       # Brand-specific SVG icons, colors, and button styling
│   ├── reset.css        # Modern CSS box-sizing and baseline reset
│   └── style.css        # Layout, typography, responsive card styles, and theme variables
├── docker/
│   ├── compose.yaml     # Docker Compose orchestration
│   ├── Dockerfile       # Lightweight static web server container
│   └── README.md        # Container deployment guide
├── images/
│   ├── avatar.png       # Masri Systems profile avatar (128x128)
│   ├── avatar@2x.png    # High-density Retina avatar (256x256)
│   └── icons/           # Custom SVG brand & platform icons
├── index.html           # Core semantic HTML page + Schema.org JSON-LD
└── README.md
