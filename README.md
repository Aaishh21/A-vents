# A-vents — City Events Platform

A modern, responsive website for discovering and booking cultural events in Atyrau. Built with HTML, CSS, and JavaScript.

# Features

- **Event Discovery**: Browse concerts, festivals, exhibitions, and cultural events
- **Dynamic Event Loading**: Events are loaded from JSON data with real-time filtering
- **Advanced Search & Filtering**: Filter by category, location, date, and price
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Interactive UI**: Smooth animations, mobile navigation, and scroll effects
- **Event Details**: Dedicated pages for each event with detailed information
- **Multi-language Support**: English, Russian, and Kazakh language options

# Live Demo

Visit the live website: [https://aaishh21.github.io/A-vents/](https://aaishh21.github.io/A-vents/)

# Project Structure

A-vents/
├── index.html              # Homepage (main landing page)
├── Events.html             # Events listing page with filters
├── about.html              # About us page
├── event page specific.html # Individual event details page
├── events.json             # Event data (JSON format)
├── style.css               # Main stylesheet for Events page
├── apec.css               # Stylesheet for homepage
├── home.css               # Additional homepage styles
├── icons/                 # Icon assets
├── img/                   # Image assets
└── README.md              # This file

# Technologies Used

- **Design**: Figma
- **Frontend**: HTML5, CSS3, JavaScript
- **Data**: JSON for event storage
- **Fonts**: Google Fonts (Inter, Anton)
- **Icons**: Custom SVG icons
- **Responsive**: CSS Grid, Flexbox, Media Queries

# Pages Overview

### Homepage (`index.html`)
- Hero section with featured music festival
- Scrollable event cards
- FAQ section with tabs
- Newsletter subscription
- Mobile-responsive navigation

### Events Page (`Events.html`)
- Complete event listing
- Search and filter functionality
- Category and location filters
- Price and date sorting
- Load more functionality

### Event Details (`event page specific.html`)
- Individual event information
- Event-specific styling and content
- Dynamic loading based on URL parameters

### About Page (`about.html`)
- Company information and mission
- Team introduction
- Contact details

# Known Issues

- **File Protocol**: Direct file opening (file://) may not work in Chrome due to CORS restrictions. Use a local server instead.
- **Cache**: Browser caching may show outdated events. Use Ctrl+F5 for hard refresh during development.
---


**A-vents** — Your gateway to Atyrau's vibrant cultural scene. Discover concerts, exhibitions, and events that bring our community together.