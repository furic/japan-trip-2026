# 🇯🇵 Japan Trip 2026 — A Claude-Planned Itinerary

[![Live Site](https://img.shields.io/github/deployments/furic/japan-trip-2026/github-pages?label=Live%20Site&logo=github&color=success)](https://furic.github.io/japan-trip-2026)
[![Made with Claude](https://img.shields.io/badge/Made%20with-Claude%20Sonnet-8A2BE2?logo=anthropic&logoColor=white)](https://claude.ai)
[![Japan Trip](https://img.shields.io/badge/Japan-Oct%E2%80%93Dec%202026-DC143C)](https://furic.github.io/japan-trip-2026)
[![HTML](https://img.shields.io/badge/HTML-100%25-E34F26?logo=html5&logoColor=white)](https://github.com/furic/japan-trip-2026)


> **An experiment in AI-assisted personal travel planning**
> *From first search to confirmed bookings, entirely orchestrated by Claude*

**Live itinerary →** [furic.github.io/japan-trip-2026](https://furic.github.io/japan-trip-2026)

---

## About This Project

This repository documents a real 40-day trip itinerary (Oct–Dec 2026) that was planned end-to-end in a single extended session with **Claude Sonnet** (Anthropic). No separate browser tabs. No manual research. No copy-pasting between apps.

It was an experiment to answer one question:

> *Can an AI assistant handle the full complexity of personal logistics — research, comparison, booking assistance, communication, and documentation — without the human needing to context-switch?*

The planning phase suggests yes — but the real verdict comes after the trip (Nov–Dec 2026), when the itinerary is tested against reality: transport timings, hotel accuracy, on-the-ground logistics, and whether any AI hallucinations surface.

---

## What Claude Did

### 🔍 Research & Decision Making
- Researched ski season opening dates for Shiga Kogen, Madarao, and Hokkaido resorts
- Compared Shibu Onsen ryokans across platforms (じゃらん, Rakuten Travel, Booking.com, Agoda)
- Cross-referenced flight prices across Qantas, Cathay Pacific, HK Airlines, and HK Express
- Verified snow conditions with historical data and recent news

### ✈️ Booking Assistance
- Guided flight selection across 4 legs (MEL↔HKG, HKG↔HND/NRT)
- Navigated じゃらん (Japanese booking platform) including form-filling in Japanese
- Caught a critical issue mid-booking: the selected plan was a breast cancer survivor special — applicable surcharges would apply to a non-qualifying guest
- Helped complete Recruit ID registration (including handling Japanese-only character set errors)

### 📅 Calendar & Reminders
- Set 3 Google Calendar reminders via MCP integration:
  - Book Tokyo hotel (Sep 15)
  - Buy Shiga Kogen 5-day lift pass (Nov 1)
  - Book Shibu Onsen ryokan (Aug 1) ← nearly missed a Rakuten 20% coupon deadline

### 💬 Communication
- Sent the trip itinerary to a friend via Slack (MCP integration)
- Drafted WhatsApp-formatted messages for sharing

### 🗺️ Documentation
- Generated this HTML travel document with embedded Google Maps, verified place IDs, distance diagrams, and a full day-by-day itinerary
- Deployed to GitHub Pages

---

## Tech Stack (Claude's Toolbox)

| Tool | Used For |
|------|----------|
| Web Search | Flight prices, hotel reviews, ski resort schedules |
| Google Calendar MCP | Setting reminders |
| Slack MCP | Sending itinerary to contacts |
| Claude in Chrome MCP | Navigating じゃらん, filling Japanese forms |
| Google Places API | Verified map pins with real place IDs |
| GitHub | Hosting this page |

---

## The Itinerary

```
Oct 29  MEL → HKG  (QF29)
        ├── Macau home stay (~2.5 weeks)
Nov 23  HKG → Tokyo HND  (UO622)
        ├── Nov 24: Akihabara
        ├── Nov 25: Tokyo → Shibu Onsen (小石屋旅館)
        ├── Nov 26-30: Shiga Kogen skiing ⛷
        ├── Nov 28: Snow Monkey Park 🐒
        ├── Nov 29: → Yumoto Ryokan (湯本旅館)
        ├── Dec 1: 九湯めぐり (9 Onsen Bath Tour) ♨️
        ├── Dec 2: → Nagano City, Zenkoji Temple ⛩
        ├── Dec 3-4: → Tokyo
Dec 5   Tokyo NRT → HKG  (UO857)
Dec 6   HKG → MEL  (QF30)
```

---

## Confirmed Bookings

| Item | Ref | Cost |
|------|-----|------|
| QF29/QF30 MEL↔HKG | EYPCJS | AUD $1,224 |
| UO622/UO857 HKG↔Tokyo | SFSP4R | HKD $3,036 |
| 小石屋旅館 Nov 25–29 | じゃらん | ¥28,000 (paid) |
| 湯本旅館 Nov 29–Dec 1 | じゃらん | ¥47,000 (pay on site) |

---

## Reflections

This session validated a few things about using Claude as a personal assistant:

**What worked exceptionally well:**
- Maintaining full trip context across hundreds of messages without losing track
- Proactively catching issues (wrong booking plan, expired coupons, room type mismatches)
- Navigating foreign-language platforms natively
- Producing structured, reusable output (this HTML document)

**Current limitations:**
- Cannot handle final payment steps (by design — security boundary)
- MCP tool authentication sometimes requires manual setup
- Cannot upload files from the server environment to third-party hosts directly

**Overall verdict:** For trip planning specifically, Claude functions as a capable co-pilot that handles research, logistics, and coordination — reducing what would typically be 6–8 hours of planning to a single focused session.

---

## Files

| File | Description |
|------|-------------|
| `index.html` | Full interactive trip itinerary with maps, timeline, and budget |
| `README.md` | This file |

---

*Planned with [Claude](https://claude.ai) · August 2026*
