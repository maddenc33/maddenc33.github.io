# Biodiversity Dashboard | Plotly.js, D3.js, JavaScript, HTML

**Christopher Madden** | [LinkedIn](http://bit.ly/4uMMPV7) | [GitHub Portfolio](https://bit.ly/3Pz5LS3)

🌐 **[View Live Dashboard](https://maddenc33.github.io/)**

---

## Project Overview

This project builds and deploys an interactive data dashboard using Plotly.js and D3.js to explore a biodiversity dataset cataloging microbial species (operational taxonomic units, or OTUs) found in human belly buttons. Users can select individual test subjects from a dropdown menu and the dashboard dynamically updates to display that subject's top OTUs, sample metadata, and microbial frequency.

The dashboard is fully deployed as a live GitHub Pages site.

This is a portfolio project completed as part of my Data Analytics Certificate program at Case Western Reserve University (2022).

---

## Tools & Skills Demonstrated

- **Languages:** JavaScript (ES6+), HTML5, CSS3
- **Libraries:** Plotly.js, D3.js
- **Deployment:** GitHub Pages
- **Techniques:** JSON data fetching, dynamic chart rendering, dropdown event handling, functional programming, responsive layout
- **Competencies:** Interactive data visualization, front-end dashboard development, API data consumption, web deployment

---

## Dashboard Features

- **Dropdown selector** — choose any test subject ID to update all charts simultaneously
- **Bar chart** — displays the top 10 OTUs found for the selected individual, with sample values and OTU labels
- **Bubble chart** — visualizes the full OTU sample, with marker size representing sample value and color encoding OTU ID
- **Metadata panel** — displays demographic information for the selected subject (age, location, ethnicity, etc.)
- **Gauge chart** — shows weekly belly button washing frequency for the selected subject

---

## Repository Structure

```
maddenc33.github.io/
├── index.html          # Main dashboard page
├── JS/
│   └── charts.js       # Plotly chart logic and D3 data fetching
├── static/
│   └── samples.json    # Biodiversity dataset
└── README.md
```

---

## About the Author

I am a Data Analyst with experience in SQL, Python, R, Power BI, Tableau, and Excel. I specialize in data cleaning, statistical analysis, dashboard development, and translating complex data into clear business insights.

📧 maddenc33@gmail.com | [LinkedIn](http://bit.ly/4uMMPV7) | [GitHub](https://bit.ly/3Pz5LS3)
