Yogyakarta Coffee Shops Data Analysis & Executive Dashboard

Acomprehensive data analysis project examining consumer reviews, sentiment distribution, and cafe performance across the Special Region of Yogyakarta (DIY). This repository contains both a relational database processing pipeline, a custom executive dashboard featuring a dark glassmorphism design, and a complete presentation slide deck.

Project Overview :
Yogyakarta boasts a thriving culinary ecosystem, particularly coffee shops. This project extracts, cleans, structures, and analyzes consumer review datasets to provide actionable business intelligence for cafe owners and stakeholders.Total Reviews Analyzed: 2,241 customer reviewsUnique Cafes Mapped: 189 unique coffee shops across 10 sub-districts (kecamatan)Overall Satisfaction Rate: 91.6% positive customer sentiment.

📂 Repository Structuredashboard-eksekutif/
│
├── assets/                    # Image assets and graphics
├── css/                       # Stylesheets (if external)
├── js/                        # JavaScript logic files
├── dashboard_eksekutif.html   # Interactive Executive Dashboard (Dark Glassmorphism)
├── COFFEE JOGJA.pdf           # Executive Presentation Slide Deck (Canva)
└── README.md                  # Project Documentation

ETL & Data Pipeline Workflow :
Raw Data Extraction: Handled text-parsing constraints from raw review CSV sources.Database Staging (MySQL): Inserted 2,241 rows of raw review data into relational MySQL tables (ulasan_mentah).Aggregation & Transformation: Created summary metrics tables calculating total reviews, average ratings, and performance metrics.Performance Segmentation: Automatically classified cafes based on strict service quality benchmarks.

Key Findings & Customer Satisfaction Distribution :
Consumer sentiment analysis breakdown from the 2,241 reviews :
5 Stars: 1,632 reviews (72.82%) — Majorities of visitors are deeply impressed.
4 Stars: 421 reviews (18.79%) — Consistent quality in service and taste.
3 Stars: 101 reviews (4.51%) — Moderate / standard baseline feedback.
1–2 Stars: 87 reviews (3.88%) — Identified areas for complaint or service improvement.

Cafe Performance Classification Map :
Top Tier Cafe ($\ge 4.5$ rating) $\rightarrow$ 139 Cafes (Market dominance with exceptional customer satisfaction)
Good Cafe ($4.0 - 4.49$ rating) $\rightarrow$ 38 Cafes (Solid, stable performance, dependable consumer choices)
Needs Improvement ($< 4.0$ rating) $\rightarrow$ 12 Cafes (Requiring targeted operational attention and service upgrades)

Interactive Dashboard & Presentation
Dashboard: Built with pure HTML5 and Tailwind CSS, featuring an elegant dark theme and glassmorphism styling (dashboard_eksekutif.html).
Presentation Deck: A complete executive walkthrough is available in the repository as COFFEE JOGJA.pdf.

Author: 
Oktavian Dwi Pramudya 
