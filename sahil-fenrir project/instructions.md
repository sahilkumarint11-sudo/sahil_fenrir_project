# Project Instruction Document

**Project Title:** Online Gaming Website
**Deliverable Format:** Source Code + Documentation (Public GitHub Repository)

---

## Purpose of This Document

This document defines the complete requirements, behaviour, and expected deliverables for the Online Gaming Website project. It is written for the development team and serves as the single source of truth for everything that must be built. Every page, component, and feature described here must be delivered exactly as specified. Nothing in this document is optional unless explicitly stated.

---

## Table of Contents

1. [Project Overview](#1-project-overview)
2. [Scope of Work](#2-scope-of-work)
3. [Tech Stack Required](#3-tech-stack-required)
4. [Folder Structure](#4-folder-structure)
5. [Deliverables](#5-deliverables)
6. [Page & Component Specifications](#6-page--component-specifications)

---

## 1. Project Overview

### Purpose

This project requires the design and development of a complete online gaming website. The site must bring together game discovery, user profiles, leaderboards, tournaments, and community features into a single cohesive, fast, and visually striking platform.

### Product Summary

The deliverable is a fully responsive, multi-page gaming website built on a consistent design system, including a home page, game catalog, game detail pages, authentication pages, user profile, leaderboard, tournament section, and community/forum area. The platform must feel modern, fast, and native to a gaming audience.

### Target Audience

- Casual gamers browsing and discovering new games
- Competitive players tracking rankings and tournaments
- Game publishers or content partners managing listings
- Site administrators moderating community content

### Core Functionality

- Responsive landing page with featured games
- Searchable, filterable game catalog
- Detailed game pages with media, requirements, and reviews
- User authentication flows (sign up, login, password reset)
- User profile with favourites, achievements, and activity
- Leaderboards and tournament registration
- Community/forum threads with comments

---

## 2. Scope of Work

### What's Included

- Home page with hero/carousel, trending, and new releases sections
- Game catalog page with filters, search, and pagination/infinite scroll
- Game detail page with media gallery, system requirements, and reviews
- Authentication pages: sign up, login, password reset (front-end only)
- User profile page with avatar, bio, favourites, and achievements
- Leaderboard page with ranked tables and filters
- Tournament listing, detail, and registration pages
- Community/forum thread listing, thread view, and new post form
- A defined design system: colour palette, typography, spacing, and reusable components
- Dark theme as default with a light theme toggle
- Full responsiveness across mobile, tablet, and desktop

---

## 3. Tech Stack Required

### Development Tools

| Tool | Purpose |
|------|---------|
| React (or plain HTML/CSS/JavaScript) | Core frontend framework |
| Tailwind CSS, SCSS, or styled-components | Styling system |
| Git + GitHub | Version control and public repository hosting |
| Figma or equivalent (optional) | Wireframing and layout planning |

**Note:** Whichever framework and styling approach is chosen, it must be applied consistently across the entire codebase. Components must be modular and organized into a clear folder structure (e.g., `/components`, `/pages`, `/assets`, `/styles`).

### Asset Licensing

All images, icons, and fonts used must be either original, open-source (e.g., Google Fonts, open icon libraries), or properly licensed for use in a public repository.

---

## 4. Folder Structure

All deliverables must be organised in the following folder structure before submission. The folder must be named using the contributor's own name in `first_last` format and pushed to a public GitHub repository.

```
first_last/
├── overview.txt
├── scope_of_work.txt
├── assets.pdf
├── reference_image.png
├── instructions.md
└── rubrics.txt
```

Every file listed must be present in the root of this folder. Naming conventions must be followed exactly (lowercase, underscores, correct extensions).

---

## 5. Deliverables

All 6 deliverables are required. No deliverable may be omitted or partially completed.

| ID | Deliverable | File Name | Format | Notes |
|----|-------------|-----------|--------|-------|
| D-01 | Project Overview | `overview.txt` | TXT | Problem statement, vision, target users, core functionality |
| D-02 | Scope of Work | `scope_of_work.txt` | TXT | Included items, tech guidelines, milestones |
| D-03 | Assets Document | `assets.pdf` | PDF | Compiled reference of design assets, colours, fonts, icons used |
| D-04 | Reference Image | `reference_image.png` | PNG | Visual reference/mockup of the website's look and feel |
| D-05 | Instructions File | `instructions.md` | Markdown | This document — full project instructions |
| D-06 | Rubrics | `rubrics.txt` | TXT | Evaluation rubric for the project |

---

## 6. Page & Component Specifications

### Home Page
- Hero section with featured game banner or carousel
- "Trending Games" section (card grid)
- "New Releases" section (card grid)
- Primary navigation bar and footer with social links

### Game Catalog Page
- Grid or list view of games
- Filter controls: genre, platform, rating, release date
- Search bar with live/instant filtering
- Pagination or infinite scroll

### Game Detail Page
- Title, cover art, and media gallery (screenshots/trailer placeholder)
- Description, genre tags, platform availability
- System requirements table
- Ratings/review section
- Related games section

### Authentication Pages
- Sign up: username, email, password fields with validation
- Login: email/username and password
- Password reset / forgot password flow

### User Profile Page
- Avatar, display name, bio
- Favourite/saved games list
- Achievements or badges section
- Activity feed / match history (mock data acceptable)

### Leaderboard Page
- Ranked table of players per game (mock data acceptable)
- Filters by game and time period (weekly/monthly/all-time)

### Tournament Pages
- Tournament listing (upcoming and past)
- Tournament detail view: rules, prize pool, schedule
- Registration form (front-end only)

### Community / Forum Section
- Thread listing page
- Individual thread view with comments
- New post form (front-end only)

### Design System
- Defined colour palette and typography scale
- Reusable components: buttons, cards, navigation bar, footer, modals, form inputs, badges, tooltips
- Dark theme default, with light theme toggle

---

*This document is the single source of truth for the project. Any ambiguity must be resolved by referring back to this document. Deviations from the specifications above require written approval before implementation.*
