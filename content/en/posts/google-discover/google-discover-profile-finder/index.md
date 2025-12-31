---
title: "Google Discover Profile Finder: this shouldn’t be this hard"
date: 2025-12-27
slug: "google-discover-profile-finder"
description: "A small Streamlit app that finds an entity’s Google Discover Profile via Knowledge Graph (MID → hash → URL)."
tags:
  - google-discover
  - seo
  - knowledge-graph
  - streamlit
images:
  - google-discover-profile-finder.jpeg
toc: true
---


## 👀 Finding a Google Discover Profile shouldn’t be this hard

If you work in **SEO**, **news**, **content**, or **digital publishing**, you already know how mysterious the Google Discover ecosystem can be.

One of the most annoying parts is the existence of those “hidden” Discover profile links Google generates — often tied to **Knowledge Graph entities**.

You know the profile exists.  
But finding the link? It feels like a puzzle.

So I built a small Streamlit app that does the heavy lifting:

- 🔹 queries the **Google Knowledge Graph API**
- 🔹 extracts the entity’s real **MID**
- 🔹 converts the MID into the exact **hash format** Google uses for Discover Profile URLs
- 🔹 returns a clean, ready-to-use Discover Profile link

---

## The result?

👉 A simple, open, transparent way to identify the Discover Profile associated with any entity that exists in the KG.

👉 Example: this is the Google Discover Profile for **Semrush**:  
https://lnkd.in/drnMzBpi

---

## Open-source, lightweight, and zero magic tricks

🔗 https://lnkd.in/d4PnN-zV

If you work with SEO, it’s fun (and useful) to play with.

If you work at Google… sending you my kindest regards. 😅
