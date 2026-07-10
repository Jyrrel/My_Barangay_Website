# Barangay Bag-ong Lapasan Website

Official website for Barangay Bag-ong Lapasan, Cagayan de Oro City, Philippines — a static site built to give residents and visitors a central place to learn about the barangay's history, leadership, events, schools, and points of interest.

## 🌐 Pages

 Page  File  Description 
---------
 Home  `index.html`  Landing page with a welcome hero, quick links, and emergency hotlines. 
 About  `about.html`  Barangay history (with video), location, and an embedded map. 
 Officials  `officials.html`  Barangay Kapitan and council members. 
 Tourist Spots  `tourist-spots.html`  Notable places to visit in Lapasan (Coastal Road, Barangay Plaza). 
 Festivals & Events  `festivals.html`  Annual community events and celebrations. 
 Schools  `schools.html`  Schools serving the barangay, from elementary to university. 

Every page shares a common header (logo + navigation), footer (contact info, hotlines, office hours), and design system for a consistent look and feel.

## ✨ Features

- Fully responsive layout (desktop, tablet, mobile)
- Sticky navigation with mobile menu toggle
- Smooth page-to-page transitions (View Transitions API with a fade fallback)
- Embedded Google Map of the barangay location
- Embedded Facebook video for barangay history
- Emergency hotline directory (Tanod, Social Services, BDRRMO, Fire Station)
- Office hours and contact info in the footer on every page

## 🛠️ Built With

- HTML5 & CSS3 (no framework — custom design system using CSS variables)
- Google Fonts — [Fraunces](httpsfonts.google.comspecimenFraunces) & [EB Garamond](httpsfonts.google.comspecimenEB+Garamond)
- Embedded Google Maps and Facebook Video Plugin
- Vanilla JavaScript for navigation toggle and page transitions

## 📁 Folder Structure

```
My_Barangay
├── index.html
├── about.html
├── officials.html
├── tourist-spots.html
├── festivals.html
├── schools.html
├── images
│   ├── logo.png
│   ├── overview.jpg
│   ├── captain-photo.jpg
│   ├── council-1.jpg ... council-4.jpg
│   ├── event-fiesta.jpg
│   ├── event-libreng-sakay.jpg
│   ├── event-month-of-ocean.jpg
│   ├── coastal-road.jpg
│   ├── barangay-plaza.jpg
│   ├── east-city-central.jpg
│   ├── lapasan-high-school.jpg
│   └── ustp.jpg
└── README.md
```

## 🚀 Running Locally

No build tools or dependencies required — it's a static site.

1. Clone the repository
   ```bash
   git clone https://github.com/Jyrrel/My_Barangay_Website.git
   ```
2. Open `index.html` directly in your browser, or serve it locally
   ```bash
   # Python 3
   python3 -m http.server 8000
   ```
   Then visit `httplocalhost8000` in your browser.

## 📌 To Do  Notes

- Add specific landmarks, sitios, or directions on the About page.
- Confirm exact barangay hall coordinates on the map.

---

Made for the community of Barangay Bag-ong Lapasan, Cagayan de Oro City. 🇵🇭
