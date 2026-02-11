## 🚀 Live Demo

🔗 **Live Demo:** [https://lithish-s.github.io/CodeAlpha_ImageGallery/](https://lithish-s.github.io/CodeAlpha_ImageGallery/)

## 📋 Task Requirements Met

# 🖼️ CodeAlpha Image Gallery

![Image Gallery](https://img.shields.io/badge/CodeAlpha-Image%20Gallery-blueviolet)
![HTML5](https://img.shields.io/badge/HTML5-Orange)
![CSS3](https://img.shields.io/badge/CSS3-Blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-6-teal)

A stunning, fully responsive image gallery with lightbox view, real-time search, category filtering, and smooth animations. Built with pure HTML, CSS, and JavaScript as part of the CodeAlpha Frontend Development Internship (Task 1).



### ✅ Core Features (100% Complete)
| Feature | Implementation |
|---------|----------------|
| **Image Gallery Layout** | Responsive CSS Grid with auto-fill |
| **Navigation (Next/Prev)** | Lightbox navigation with arrow buttons |
| **Lightbox View** | Full-screen modal with zoom animation |
| **Hover Effects** | Scale, translateY, info slide-up |
| **Smooth Transitions** | CSS transitions on all interactive elements |
| **Responsive Design** | Mobile, tablet, desktop breakpoints |

### ✅ Bonus Features (100% Complete)
| Bonus Feature | Implementation |
|---------------|----------------|
| **Category Filtering** | 4 categories + All button |
| **Search Functionality** | Real-time search with debounce |
| **Image Statistics** | Total/visible counts, active category |
| **Keyboard Navigation** | ← → ESC keys in lightbox |
| **Lazy Loading** | `loading="lazy"` on images |
| **Error Handling** | Fallback image on load failure |
| **Touch Optimized** | Prevent scroll during lightbox |

## ✨ Key Features

### 🎯 Gallery Interface
- **Clean, Modern Design** - Gradient background with glassmorphism effects
- **Responsive Grid** - Auto-adjusts from 4 columns (desktop) to 1 column (mobile)
- **Hover Animations** - Image zoom, card lift, info panel slide-up
- **Category Badges** - Color-coded category indicators

### 🔍 Advanced Filtering
- **Category Buttons** - Filter by Nature, Technology, Architecture, Abstract
- **Live Search** - Real-time filtering by title, category, or description
- **Debounced Input** - Optimized performance with 300ms delay
- **Active State** - Visual feedback for current filter

### 🖼️ Lightbox Experience
- **Smooth Zoom Animation** - Scale from 0.8 to 1 with fade
- **Full Metadata** - Title, description, category, dimensions
- **Navigation** - Next/Prev buttons with infinite loop
- **Multiple Close Options** - X button, ESC key, click outside
- **Keyboard Support** - Arrow keys for navigation

### 📊 Statistics Dashboard
- **Total Images** - Complete collection count
- **Visible Images** - Current filtered results
- **Active Category** - Selected filter indicator
- **Category Count** - 4 distinct categories

## 💻 Technologies Used

| Technology | Purpose | Key Features |
|------------|---------|--------------|
| **HTML5** | Structure | Semantic tags, lazy loading |
| **CSS3** | Styling | Grid, Flexbox, animations, variables |
| **JavaScript ES6+** | Logic | Filtering, lightbox, event handling |
| **Bootstrap 5** | Layout | Responsive utilities, spacing |
| **Font Awesome 6** | Icons | Navigation, UI elements |

## 📱 Responsive Breakpoints

| Device | Columns | Grid Gap | Font Size |
|--------|---------|----------|-----------|
| Desktop (>992px) | 4 columns | 25px | 3rem (header) |
| Tablet (768-992px) | 3 columns | 20px | 2.5rem |
| Mobile (480-768px) | 2 columns | 15px | 2rem |
| Small Mobile (<480px) | 1 column | 10px | 1.8rem |

## 🖼️ Image Collection

### Categories & Count
| Category | Images | Description |
|----------|--------|-------------|
| 🌄 **Nature** | 3 | Landscapes, forests, mountains, ocean |
| 🏛️ **Architecture** | 3 | Modern, historical, futuristic buildings |
| 🎨 **Abstract** | 3 | Digital art, color splash, geometric |
| 💻 **Technology** | 3 | Programming, devices, circuits |

### Sample Images (Unsplash)
All images are sourced from Unsplash with proper dimensions:
- Mountain Landscape (1920×1080)
- Modern Cityscape (1920×1280)
- Abstract Art (1350×900)
- Tech Devices (1350×900)
- Forest Path (1920×1280)
- Futuristic Architecture (1350×900)
- Digital Art (1350×900)
- Programming Code (1920×1080)
- Ocean Waves (1920×1280)
- Historical Building (1350×900)
- Color Splash (1350×900)
- Circuit Board (1920×1080)

## 🎮 How to Use

### 📖 Basic Usage
1. **Browse Gallery** - Scroll through responsive image grid
2. **Hover Over Images** - See zoom effect and info panel
3. **Click Image** - Open full-screen lightbox
4. **Navigate Lightbox** - Use arrows or keyboard
5. **Close Lightbox** - Click X, press ESC, or click outside

### 🔎 Filtering Images
```javascript
// Category Filter
Click: "Nature" → Shows only nature images
Click: "Technology" → Shows only tech images
Click: "All" → Resets to all images

// Search Filter
Type: "mountain" → Shows images with "mountain" in title/category/description
Type: "abstract" → Shows all abstract images
