# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2024-12-19

### Added
- **Multi-language support** - Ukrainian, English, French interface
- **Demining Calculator** with comprehensive cost calculation
  - Area-based calculations (hectares)
  - Territory complexity factors (minimal, easy, medium, hard, critical)
  - Slope angle considerations (0-15°, 15-40°, 40-90°)
  - Depth calculations with surcharge for depths over 15cm
  - Urgency surcharge option
  - Transport cost calculations
  - Customizable coefficients
- **NTS Calculator** for non-technical survey cost estimation
  - Survey area calculations
  - Distance-based transport costs
  - Complexity coefficients
  - Urgency options
  - Fuel consumption calculations
- **EORE Calculator** for safety training cost estimation
  - Base training cost
  - Distance and trip calculations
  - Urgency factors
  - Customizable coefficients
- **Route Calculator** with advanced features
  - Interactive map integration (Leaflet.js)
  - Multiple waypoints support
  - Real-time route calculation via OSRM API
  - Route alternatives display
  - Mini calculator for embedded use
- **PDF Export functionality** for all calculators
  - Professional proposal generation
  - Multi-language PDF content
  - Company branding support
- **Coefficient Management System**
  - Customizable calculation parameters
  - Local storage persistence
  - Per-calculator settings
- **Responsive Design**
  - Mobile-friendly interface
  - Grid-based layout
  - Touch-optimized controls
- **Dark Theme** with red accent colors
- **Times New Roman** font throughout the application

### Technical Features
- Bootstrap 5 for responsive design
- Font Awesome icons
- Leaflet.js for interactive maps
- OSRM API integration for route calculation
- jsPDF for PDF generation
- LocalStorage for settings persistence
- Modern CSS with CSS variables
- Cross-browser compatibility

### Localization
- Complete Ukrainian interface
- Full English translation
- Comprehensive French translation
- Language switching with persistent settings
- Localized PDF exports
- Multi-language formula displays

### User Experience
- Intuitive calculator interfaces
- Real-time calculations
- Interactive map controls
- Hover effects and animations
- Form validation
- Auto-save functionality
- Professional styling