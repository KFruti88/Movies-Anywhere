# 🎬 Werewolf Movie Directory
### Personal Library Hub for werewolf.ourflora.com

## 📖 Project Overview
This repository hosts the centralized movie directory for **werewolf3788**. It aggregates film collections from Google Movies, Movies Anywhere, Apple TV, and Amazon Prime Video into a single, searchable, and responsive web interface.

The goal is to provide a clean "Watch List" hub that links directly to the respective streaming platforms while utilizing Amazon Affiliate tracking for Prime Video titles.

---

## 🛠️ Technical Standards
- **Width:** Default 90% container width for all screens.
- **Responsiveness:** Fully cross-compatible (Mobile, Tablet, Desktop, TV).
- **Branding:** Aligned with "Clay County" Color Lock (Charcoal/White) or custom "Werewolf" branding.
- **Compatibility:** Optimized for GitHub Pages, WordPress (Divi 4/5), and CodePen.
- **Caching:** Includes "No-Cache" meta tags and asset versioning (`style.css?v=1.0`).

---

## 🔗 Amazon Affiliate Integration
All Amazon Prime Video links must follow the **High-Yield Target** strategy:
- **Tracking ID:** `werewolf3788-20`
- **Link Structure:** `https://www.amazon.com/dp/ASIN_HERE?tag=werewolf3788-20`
- **Global Cookie Strategy:** Focuses on "Check Price" or "Watch Now" to activate the 24-hour tracking window.

---

## 📊 Data Structure (A–N Column Mapping)
To keep data consistent with other town projects, the `movies.json` or Google Sheet follows this logic:
| Column | Detail |
| :--- | :--- |
| **A** | Image ID (Movie Poster) |
| **B** | Movie Name |
| **C** | Streaming Service |
| **D** | Quality (4K, HD, SD) |
| **E** | Category (Genre) |
| **F** | N/A |
| **G** | Studio |
| **H** | Runtime |
| **I** | Website (Direct Watch URL) |
| **K** | Bio (Movie Synopsis) |
| **L** | Affiliate Text |
| **N** | Affiliate Link |

---

## 🚀 Deployment Instructions
1. **Update Data:** Add new films to the `movies.json` file.
2. **Version Control:** Increment the CSS/JS version string in `index.html` (e.g., `?v=1.01`).
3. **Commit:** Push changes to the GitHub repository.
4. **Automation:** The GitHub Action will automatically update the XML feed for Zapier/Facebook integration.

---

## 👥 Ownership & Contacts
- **Owner:** Kevin (werewolf3788)
- **Domain:** [werewolf.ourflora.com](https://werewolf.ourflora.com)
- **Project Lead:** Scott (S&K Ventures Inc.)
