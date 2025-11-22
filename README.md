# 🌍 WorldExplorer - Travel Planning Desktop Application

A feature-rich desktop application built with Electron.js that helps users explore countries, plan trips, and manage travel itineraries with integrated mapping and currency exchange features.

![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Integration](#api-integration)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## 🎯 Overview

WorldExplorer is a cross-platform desktop application designed to assist travelers in researching destinations, planning itineraries, and managing trip details. Built as a semester project to demonstrate proficiency in desktop application development, REST API integration, and modern web technologies.

**Development Period:** Semester 4, 2024  
**Purpose:** Object-Oriented Programming Final Project

## ✨ Features

### 🔍 Country Explorer
- Browse comprehensive information about countries worldwide
- View detailed country profiles including:
  - Population statistics
  - Geographic location and region
  - Capital city information
  - Official languages
  - Currency details
  - Time zones
- Filter countries by region (Africa, Americas, Asia, Europe, Oceania)
- Search functionality for quick country lookup

### 🗺️ Interactive Mapping
- Integrated Leaflet.js maps for geographic visualization
- View country locations on interactive maps
- Google Maps integration for detailed exploration
- Zoom and pan capabilities

### 📅 Itinerary Management (CRUD Operations)
- **Create** new travel itineraries with custom details
- **Read** and view all saved itineraries
- **Update** trip information and travel plans
- **Delete** completed or cancelled trips
- Add trip details including:
  - Destination country
  - Travel dates (start and end)
  - Duration
  - Activities and things to do
  - Custom trip images

### 💱 Currency Exchange Calculator
- Real-time currency conversion
- Support for multiple international currencies
- User-friendly interface for quick calculations
- Essential tool for budget planning

### 🖼️ Visual Trip Planning
- Upload and attach images to itineraries
- Pre-loaded destination images for popular countries
- Visual trip cards with country imagery

## 📸 Screenshots

### Explore Countries
*Browse and search countries with detailed information cards*

### Country Details
*View comprehensive country information with interactive maps*

### Trip Planner
*Create and manage travel itineraries with ease*

### Currency Exchange
*Calculate currency conversions for budget planning*

> **Note:** Screenshots showcase the clean, intuitive user interface designed for seamless travel planning.

## 🛠️ Technologies Used

### Core Technologies
- **Electron.js** - Cross-platform desktop application framework
- **JavaScript (ES6+)** - Application logic and interactivity
- **HTML5** - Structure and content
- **CSS3** - Styling and responsive design

### APIs & Libraries
- **REST Countries API** - Country data and information (https://restcountries.com/v3.1/all)
- **Leaflet.js** - Interactive mapping library
- **Google Maps API** - Additional mapping features

### Development Tools
- **Electron Forge** - Build and packaging tool
- **Node.js** - Runtime environment
- **npm** - Package management

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/naqibhazian/WorldExplorer.git
cd WorldExplorer
```

2. **Install dependencies**
```bash
npm install
```

3. **Run the application in development mode**
```bash
npm start
```

4. **Build for production**
```bash
npm run make
```

The built application will be available in the `out/` directory.

## 🚀 Usage

1. **Launch the Application**
   - Run the application using `npm start` or launch the built executable

2. **Explore Countries**
   - Navigate to "Explore Country" from the sidebar
   - Browse country cards or use the search feature
   - Click on any country to view detailed information

3. **Create an Itinerary**
   - Go to "My Itinerary" section
   - Click "Add Trip" button
   - Fill in trip details (destination, dates, activities)
   - Upload a trip image (optional)
   - Save your itinerary

4. **Manage Trips**
   - View all saved itineraries in the "My Itinerary" section
   - Edit trip details by clicking on any itinerary
   - Delete trips when completed or no longer needed

5. **Currency Exchange**
   - Access "Currency Exchange" from the sidebar
   - Select source and target currencies
   - Enter amount to convert
   - View real-time exchange rates

## 📁 Project Structure

```
WorldExplorer/
├── src/
│   ├── index.html              # Main home page
│   ├── index.js                # Electron main process
│   ├── index.css               # Global styles
│   ├── preload.js              # Preload scripts
│   ├── explore-country.html    # Country browsing interface
│   ├── country.html            # Detailed country view
│   ├── travel.html             # Trip planner interface
│   ├── itenarary.html          # Itinerary management
│   ├── money.html              # Currency exchange calculator
│   └── [images]                # Pre-loaded destination images
├── package.json                # Project dependencies
├── package-lock.json           # Locked dependency versions
├── forge.config.js             # Electron Forge configuration
├── .gitignore                  # Git ignore rules
└── README.md                   # Project documentation
```

## 🔗 API Integration

### REST Countries API
The application integrates with the REST Countries API to fetch comprehensive country data:

**Endpoint:** `https://restcountries.com/v3.1/all`

**Data Retrieved:**
- Country names (common and official)
- Population figures
- Geographic coordinates
- Regional information
- Capital cities
- Languages
- Currencies
- Flags and coat of arms
- Time zones

**Implementation:**
- Asynchronous fetch requests
- Error handling for API failures
- Data caching for improved performance
- Dynamic rendering of country information

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- ✅ Desktop application development with Electron.js
- ✅ REST API integration and data fetching
- ✅ CRUD operations and data persistence
- ✅ Interactive map implementation with Leaflet.js
- ✅ Event-driven programming
- ✅ Asynchronous JavaScript (Promises, async/await)
- ✅ DOM manipulation and dynamic content rendering
- ✅ User interface design and user experience
- ✅ Application packaging and distribution

## 🚧 Future Enhancements

Potential features for future development:
- [ ] Cloud synchronization for itineraries across devices
- [ ] Weather forecasts for destination countries
- [ ] Flight and accommodation booking integration
- [ ] Budget tracking and expense management
- [ ] Collaborative trip planning with multiple users
- [ ] Export itineraries to PDF format
- [ ] Offline mode with cached country data
- [ ] Social media integration for sharing trips
- [ ] Travel recommendations based on preferences
- [ ] Multi-language support

## 👨‍💻 Developer

**Naqib Hazian**
- GitHub: [@naqibhazian](https://github.com/naqibhazian)
- LinkedIn: [Naqib Hazian](https://linkedin.com/in/naqibhazian)

## 📄 License

This project is licensed under the MIT License - feel free to use it for learning purposes.

## 🙏 Acknowledgments

- **REST Countries API** for providing comprehensive country data
- **Leaflet.js** community for excellent mapping documentation
- **Electron.js** team for the powerful desktop framework
- **Object-Oriented Programming Course** (Semester 4) for project guidance

---

⭐ If you find this project helpful, please consider giving it a star!

**Built with passion for travel and code** 🌏✈️💻