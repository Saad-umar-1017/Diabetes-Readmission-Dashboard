# 🏥 Diabetes Readmission Dashboard

**Course:** DSC327 — Data Visualization Techniques  
**Dataset:** UCI Diabetes 130-US Hospitals (1999–2008) · ~101,766 patient encounters  
**CLO 5:** Develop a web-based system using interactive visualization techniques and libraries

---

## 📁 Project Structure

```
├── index.html       ← Main dashboard (all-in-one HTML + D3.js)
└── README.md        ← This file
```

---

## 🚀 How to Run

### Option 1 — Open Locally (Simplest)
1. Download `index.html`
2. Double-click it — opens directly in any browser (Chrome, Firefox, Edge)
3. No server, no install needed

### Option 2 — GitHub Pages (Hosted)
1. Create a new GitHub repository
2. Upload `index.html` and `README.md`
3. Go to **Settings → Pages → Branch: main → Save**
4. Your dashboard is live at: `https://<your-username>.github.io/<repo-name>/`

### Option 3 — Local Server
```bash
# Python
python -m http.server 8080
# then open http://localhost:8080
```

---

## 📊 Visualizations

| # | Chart | Type | Interaction |
|---|-------|------|-------------|
| 1 | Overall Readmission Risk | Animated Arc Gauge | Auto-updates on filter |
| 2 | Readmission Rate by Age Group | Bar Chart | Hover tooltips, filter highlight |
| 3 | Readmission Class Distribution | Donut Chart | Hover expand + tooltip |
| 4 | Admission Type vs Readmission Rate | Horizontal Bar | Hover tooltips, filter highlight |
| 5 | Hospital Stay vs Medications | Scatter Plot | Hover tooltip + scroll to zoom |
| 6 | Prior Inpatient Visits vs Readmission | Color-scaled Bar | Hover tooltips |

---

## 🎛️ Interactions

- **Age Group filter** — highlights the selected age group across all charts
- **Admission Type filter** — highlights the selected type across all charts
- **Reset button** — clears all filters
- **Tooltips** — hover any data point for exact values
- **Scatter zoom** — scroll/pinch to zoom into the scatter plot
- **Donut hover** — segments expand on hover

---

## 🛠️ Technologies

- **D3.js v7** — all visualizations
- **Vanilla HTML/CSS/JS** — no build step required
- **Google Fonts (Inter)** — typography

---

## 📌 Key Findings

- Overall 30-day readmission rate: **11.2%**
- Highest readmission age group: **70–80 years (12.4%)**
- Emergency admissions have the highest readmission rate: **12.8%**
- Patients with 6+ prior inpatient visits have **33.8%** readmission rate vs **9.1%** for none
- Readmitted patients tend to have longer hospital stays and more medications

---

## 👥 Team
- Student 1: ___________________
- Student 2: ___________________
