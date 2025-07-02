# Information Expansion Lab – ITEM Visualizer - Project Brief

## Overview

This is the official development repository for the IEL ITEM Visualizer, a browser-based learning tool that allows users to: 
- Visualize differences in universe expansion rates betwen the lamda-CDN model and the ITEM model
- Receive AI-powered coaching help when their queries fail or when in help mode (via a hidden Claude API layer)

The playground will be embedded into the Break Into Tech website via an iFrame at:  
**https://iel.breakintotech.com/item**

---

## 🧑‍💻 Roles

### 🎯 Arthur Kudner – Research Engineer
**Title:** Research Engineer – Full Stack Developer 

Arthur is responsible for the full stack including the core UI and backend logic, such as:

1. **UI Development**  
   - Build a clean, responsive UI using React (or preferred framework)
   - Include:
     - DESI DR2 Data 
     - Universe expansion visualization
     - Visualization breakdown of differences between lamba-CDM and ITEM
     - Toggle with view options 
     - AI Assistant for layperson explanations 

2. **Claude Integration via Cloudflare Worker**  
   - Send user prompt to Claude
   - Return custom breakdown of esoteric ITEM and lambda-CDM physics concepts for non-scientific and non-technical users 

3. **Deployment**  
   - Deploy app to Cloudflare Pages at:
     `https://iel.breakintotech.com/item`

---

## 🌐 Deployment Plan

| Component                         | Owner               | Location                                                            |
|-----------------------------------|---------------------|---------------------------------------------------------------------|
| ITEM Visualizer App  - Backend    | Arthur              | `Cloudflare Worker endpoint & Github`                               |
| ITEM Visualizer App - Frontend    | Arthur              | `Cloudflare page & Github`                                          |
| Web Integration                   | Charlotte & Arthur  | `https://breakintotech.com/resources/sql-practice` (Webflow iFrame) |

---

## 🔐 Licensing & Attribution

- All code is licensed for personal/educational use only (see [LICENSE.txt](./LICENSE.txt))
- Arthur will be publicly credited in:
  - GitHub README
  - Public tool embed page (such as `https://iel.breakintotech.com/item`)
