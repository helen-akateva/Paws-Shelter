# Paws Shelter 🐾

[![Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://helen-akateva.github.io/Paws-Shelter/)

**Every life matters. Find your loyal friend.**

Paws Shelter is a web application designed to help homeless animals find loving homes. The platform enables users to browse available pets, filter by categories, view detailed information, and submit adoption requests.

## 📋 About the Project

This team project addresses an important social mission - helping homeless animals find forever homes. The application provides:

- Browse a catalog of animals with detailed information
- Filter pets by categories (cats, dogs, etc.)
- Read success stories of adopted pets
- Submit adoption requests
- Learn more about the organization and its mission

## 🛠️ Technologies & Stack

### Core Technologies
- **HTML5** - Semantic markup
- **CSS3** - Styling and responsive design
- **JavaScript (ES6+)** - Functionality and interactivity
- **Vite** - Build tool and development server

### Libraries & Tools
- **Swiper.js** - Sliders and carousels
- **RateYo** - Star rating display
- **iziToast** - Push notifications
- **REST API** - Data fetching and submission

### Development
- **Git & GitHub** - Version control
- **GitHub Pages** - Deployment
- **Prettier** - Code formatting
- **EditorConfig** - Code style consistency

## ✨ Key Features

### Homepage
- Hero section with welcome message and navigation
- Pet catalog with filtering and pagination
- About Us slider with organization information
- FAQ accordion with common questions
- Reviews carousel with adoption success stories

### Pet Catalog
- Filter by categories (cats, dogs, and more)
- Lazy loading with pagination (9 items on desktop, 8 on mobile/tablet)
- Detailed information in modal windows
- Ability to submit adoption requests

### Modal Windows
- Pet details with full information and characteristics
- Adoption request form with contact data
- Form validation and error handling

### Responsive Design
- **Mobile:** from 320px (fluid layout), adaptive from 375px
- **Tablet:** from 768px
- **Desktop:** from 1440px

## 🚀 Getting Started

### Installation

```bash
# Clone the repository
git clone https://github.com/helen-akateva/Paws-Shelter.git

# Navigate to project directory
cd Paws-Shelter

# Install dependencies
npm install
```

### Development

```bash
# Start development server
npm run dev
```

### Production Build

```bash
# Build for production
npm run build

# Preview production build
npm run preview
```

## 📡 API Integration

The project uses a REST API for data operations:

- `GET /api/categories` - Fetch animal categories
- `GET /api/animals` - Fetch list of animals
- `GET /api/feedbacks` - Fetch user reviews
- `POST /api/orders` - Submit adoption request

## 🎯 Project Highlights

- **Fully responsive design** across all devices
- **Accessibility** - ARIA attributes and semantic HTML
- **Performance** - Optimized images and code
- **Loading indicators** for all API requests
- **UX-friendly** - Intuitive navigation and interactions
- **Error handling** with user-friendly messages

## 👥 Team Project

This project was developed by a team of students as part of the GoIT educational course. Each team member contributed to different aspects of the application.

### My Contribution
I was responsible for developing the **Stories section** ([src/partials/stories.html](src/partials/stories.html)), which showcases heartwarming adoption success stories and testimonials. I also presented this project to our mentor.

## 👤 Author

**Olena Akatieva**

- LinkedIn: [linkedin.com/in/olena-akatieva](https://linkedin.com/in/olena-akatieva)
- GitHub: [@helen-akateva](https://github.com/helen-akateva)

## 📄 License

© 2024 Paws Shelter. All rights reserved.

---

**Help us find a home for every pet! 🐾**
