# Currency Converter (React + Vite)

🔗 **Live Demo:** https://interactive-currency-converter.netlify.app/

A modern currency conversion application demonstrating clean component architecture, API integration, and responsive UI development using **React** and **Vite**. This project highlights practical front-end engineering skills, including state management, API handling, and production-ready UI implementation.

## Project Summary

This application:

- Fetches real-time exchange rates from a public API
- Supports conversions across 150+ currencies
- Includes currency swapping functionality
- Displays country flags dynamically
- Uses a clean, mobile-responsive layout
- Follows modern React development best practices (Hooks, modular components)

The project is intentionally lightweight to emphasize clarity, maintainability, and code quality.

## Key Skills Demonstrated

### Front-End Engineering

- React functional components
- Hooks: useState, useEffect
- Component-driven design

### API & Data Handling

- REST API integration
- Async functions + error handling
- Dynamic UI based on API responses

### Modern Tooling

- Vite build system
- ES6+ JavaScript
- Clean project structuring and architecture

### UI/UX Implementation

- Responsive layout
- Form handling and validation
- Dynamic flag rendering (FlagsAPI)

## Tech Stack

| Category | Technologies |
|---------|--------------|
| Framework | React |
| Build Tool | Vite |
| Language | JavaScript (ES6+) |
| Styling | CSS |
| APIs | ExchangeRate API, FlagsAPI |

## Running the Project

Clone and install dependencies:

```bash
git clone https://github.com/PavelLakov/Currency Converter.git
cd REPO-NAME
npm install
```

Start development:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview:

```bash
npm run preview
```

## API Setup

Inside `ConverterForm.jsx`, add your API key:

```javascript
const API_KEY = "YOUR_API_KEY";
```

Get your key at: <https://www.exchangerate-api.com/>

## Project Structure (Simplified)

```
src/
  components/
    ConverterForm.jsx
    CurrencySelect.jsx
  App.jsx
  main.jsx
  index.css
public/
index.html
```

## Purpose of This Project

This repository is part of my portfolio and demonstrates my ability to:

- Build real-world, user-ready interfaces
- Integrate external APIs cleanly
- Write maintainable, modular front-end code
- Use modern tooling (Vite + React) effectively

It reflects the development approach I bring to professional environments: clarity, consistency, and scalability.

## License

MIT License
