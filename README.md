# Two Visual Choices for a Healthcare Analytics Dashboard 

A Power BI visualization project showcasing patient satisfaction across hospital type featuring two visual options for an interactive ribbon chart with a zoom slider.

---

### Visual themes:

-	**Monochrome Blue:** A clean, clinical style reflecting the healthcare setting.
-	**Jewel Tone:** A vibrant alternative using gold and higher saturation hues for strong category distinction.

Both dashboards are designed to demonstrate how aesthetic choices can facilitate unique user needs while preserving data clarity and interaction.

---

## Dataset Overview

Sources: 
- [Kaggle](https://www.kaggle.com/datasets/kaggleprollc/healthcare-patient-satisfaction-data-collection)
- [CMS, Centers for Medicare and Medicaid Services](https://data.cms.gov/provider-data/archived-data/hospitals)

## Method 

Hospital star ratings for patient satisfaction are segmented by facility type (acute care hospital or critical access hospital).

The public datasets contain hospital ratings (1 to 5 stars) and metadata such as location, facility type, and identifiers.

---

## Data Preparation

To ensure clarity and consistency in visual storytelling, the dataset was cleaned with the following steps:

-	Removed rows labeled Not Applicable, Not Available, and empty values
-	Dropped duplicate facility codes to avoid over-representation
-	Filtered down to valid, complete entries suitable for concise star rating analysis
-	Final data focused on Hospital Type and Rating for visualization

---

## Visualization and Interactivity

The core visual is a Power BI Ribbon Chart, selected for its aesthetic and ability to emphasize relative category movement across star ratings.

Zoom Slider: Allows viewers to explore rating distributions interactively

Screen Recordings: This project features both versions as short videos via Vimeo links

---

## Insights & Applications

This project serves as both a technical showcase and a creative experiment in making data feel alive, clear, and impactful.

-	How Power BI can merge design and analytics
-	The impact of visual theme selection on stakeholder engagement
-	How a single dashboard can provide different stakeholders with the specific insights they need
-	A reusable template for future healthcare or satisfaction-based dashboards

