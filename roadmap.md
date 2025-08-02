# YieldMap Development Roadmap

This roadmap outlines the key milestones, modules, and phases required to launch and scale YieldMap — a geospatial AI tool for assessing development potential in the UK.

---

## 🚀 MVP Phase (Cornwall Pilot)

### ✅ Core Goals
- Click-to-analyze map with parcel detection
- Density calculator (units per acre/hectare)
- Zoning + constraint overlays (flood, conservation)
- Output visual result and PDF report

### 🛠 Features
- [ ] Upload Cornwall parcel boundaries (GeoJSON)
- [ ] Enable Mapbox map in Bubble
- [ ] Trigger backend workflow on map click
- [ ] Return density, zoning type, constraint flags
- [ ] Generate traffic-light style feasibility rating
- [ ] Display results in panel + download as PDF

---

## 📡 Phase 2 – Data Enrichment

### ✅ Core Goals
- Add more real-world data and logic
- Improve credibility of feasibility insights

### 🛠 Features
- [ ] Integrate planning applications (local authority APIs or scrape)
- [ ] Upload sales comps dataset (CSV or Supabase)
- [ ] Implement GDV uplift estimation (based on sales comps)
- [ ] Add rule-based policy logic (if zone=X, and constraint=Y → amber)

---

## 🧠 Phase 3 – AI + Scoring Engine

### ✅ Core Goals
- Introduce intelligent development scoring

### 🛠 Features
- [ ] Add Risk Scoring Model (flood risk, planning history, constraints)
- [ ] Auto-summarize planning policy PDF using AI
- [ ] Generate detailed “Planning Uplift Score”

---

## 🗺️ Phase 4 – Scale-Up & Multi-Region

### ✅ Core Goals
- Expand beyond Cornwall
- Improve database scalability

### 🛠 Features
- [ ] Add new areas: London, Bristol, Surrey
- [ ] Switch from Bubble DB to Supabase fully
- [ ] Add admin panel to manage uploaded data
- [ ] Add user dashboard with saved reports

---

## 💳 Phase 5 – Payments + SaaS Model

### ✅ Core Goals
- Monetize with clear subscription model

### 🛠 Features
- [ ] Stripe integration (3 free reports, then upgrade)
- [ ] Add Pro features: Save reports, access multi-layer maps
- [ ] Generate branded white-label PDFs for agents/developers