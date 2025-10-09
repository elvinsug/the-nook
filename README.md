# The Nook - Study Café Website

<div align="center">

**Singapore's Premier Study Café Website**

A modern, responsive website for The Nook study café, designed to provide students with an affordable, comfortable space to focus and thrive.

</div>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Setup Instructions](#-setup-instructions)
- [Sitemap](#-sitemap)
- [Design System](#-design-system)
- [Browser Support](#-browser-support)
- [Contact Information](#-contact-information)

---

## 🎯 Project Overview

**The Nook** is a comprehensive website for a student-focused study café in Singapore. The website showcases the café's offerings, allows users to browse the menu, learn about the story behind The Nook, reserve seats, and get in touch with the team.

### Key Highlights

- **Target Audience**: University students and study groups
- **Location**: 123 Study Street, Singapore 123456 (5-min walk from Kent Ridge MRT)
- **Operating Hours**: 8:00 AM - 11:00 PM Daily
- **Contact**: +65 1234 5678 | info@thenook.com

---

## ✨ Features

### 1. **Homepage**
- Eye-catching hero section with compelling value proposition
- Weekly deals and promotional bundles
- Seat options showcase (Solo Desk, Group Table, Private Table)
- Student testimonials with auto-scrolling carousel
- FAQ section with expandable accordion
- Call-to-action buttons throughout

### 2. **About Us Page**
- Founder's story and mission statement
- Interactive timeline showcasing The Nook's journey
- Core values and amenities grid
- Student reviews and ratings (4.9/5.0 based on 700+ reviews)
- High-quality imagery

### 3. **Menu Page**
- Filterable menu items (All, Promo, Beverages, Foods)
- **Beverages** (9 items):
  - Lychee Oolong Tea ($7)
  - Honey Lemon Tea ($6)
  - Classic Iced Tea ($5)
  - Green Focus Smoothie ($8)
  - Tropical Booster Smoothie ($8)
  - Brain Booster Smoothie ($8)
  - Matcha Latte ($7)
  - Iced Americano ($5)
  - Latte ($6)
- **Foods** (9 items):
  - Avocado Toast ($8)
  - Chicken Sandwich ($9)
  - Quinoa Salad ($8)
  - Pasta Bowl ($9)
  - Egg Sandwich ($7)
  - Granola Bowl ($7)
  - Grilled Teriyaki Chicken Bowl ($9)
  - Salmon Grain Bowl ($9)
  - Chicken Chop with Rice ($9)
- Detailed menu item pages with descriptions and pricing

### 4. **Booking System**
- **Step 1**: Interactive calendar with date/time selection
- **Step 2**: Seat type selection with real-time availability
- **Step 3**: Payment summary with QR code
- **Step 4**: Confirmation page with reservation details
- Progress indicator throughout the booking flow
- Student discount (10% off) automatically applied
- Reservation ID generation
- Downloadable confirmation QR code

### 5. **Contact Page**
- Contact form with validation
- Store information and operating hours
- Location details with map reference
- Multiple contact methods (phone, email, address)
- Success confirmation modal

### 6. **Responsive Design**
- Fully responsive across all devices (mobile, tablet, desktop)
- Mobile-first approach
- Optimized navigation for small screens
- Touch-friendly interface elements

---

## 🛠 Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **JavaScript (ES6+)** - Interactive components
- **Tailwind CSS** - Utility-first CSS framework (via CDN)

### Libraries & Frameworks
- **Google Fonts (Inter)** - Body text typography
- **Lucide Icons** - Modern icon set for UI elements
- **html2canvas** - Screenshot functionality for booking confirmations

### Design Assets
- **Custom Fonts**: Labil Grotesk (Regular, Medium, Bold)
- **Custom Color Palette**: Brand colors, beige tones, and neutral shades
- **High-Quality Images**: WebP and PNG formats for optimal performance

---

## 📁 Project Structure

```
the-nook/
│
├── public/                      # Static assets
│   ├── about/                  # About page images
│   │   ├── hero.jpg
│   │   └── pour-coffee.jpg
│   ├── booking/                # Booking page assets
│   │   └── qr.jpg
│   ├── footer/                 # Footer images
│   │   └── footer.png
│   ├── home/                   # Homepage images
│   │   ├── deal-1.webp
│   │   ├── deal-2.webp
│   │   ├── deal-3.webp
│   │   ├── hero.webp
│   │   ├── seat-1.webp
│   │   ├── seat-2.webp
│   │   ├── seat-3.webp
│   │   └── study-ambience.webp
│   ├── icon/                   # UI icons
│   │   ├── clock.svg
│   │   ├── location.svg
│   │   ├── mail.svg
│   │   ├── menu.svg
│   │   └── phone.svg
│   ├── logo/                   # Brand logos
│   │   ├── icon-only-dark.svg
│   │   ├── icon-only-white.svg
│   │   ├── with-text-dark.svg
│   │   └── with-text-white.svg
│   ├── menu/                   # Menu item images
│   │   ├── drink/              # Beverage images (drink-1 to drink-9)
│   │   ├── food/               # Food images (food-1 to food-9)
│   │   └── hero.png
│   └── favicon.ico
│
├── src/                        # Source files
│   ├── font/                   # Custom fonts
│   │   ├── Labil Grotesk Bold.ttf
│   │   ├── Labil Grotesk Medium.ttf
│   │   └── Labil Grotesk Regular.ttf
│   ├── pages/                  # HTML pages
│   │   ├── about/
│   │   │   └── index.html
│   │   ├── booking/
│   │   │   ├── index.html      # Main booking page
│   │   │   └── deal.html       # Deal booking page
│   │   ├── contact/
│   │   │   └── index.html
│   │   ├── menu/
│   │   │   └── index.html
│   │   └── menu-details/       # Individual menu item pages
│   │       ├── beverages/      # 9 beverage detail pages
│   │       └── foods/          # 9 food detail pages
│   ├── global.css              # Global styles
│   └── index.html              # Homepage
│
└── README.md                   # Project documentation
```

---

## 🚀 Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for best experience)

### Installation & Running

#### Option 1: Direct File Opening
1. Clone or download the repository
2. Navigate to the project folder
3. Open `src/index.html` in your web browser

#### Option 2: Using a Local Server (Recommended)

**Using Python:**
```bash
# Navigate to project directory
cd the-nook

# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Open http://localhost:8000/src/index.html
```

**Using Node.js (with http-server):**
```bash
# Install http-server globally (if not already installed)
npm install -g http-server

# Navigate to project directory
cd the-nook

# Start server
http-server

# Open http://localhost:8080/src/index.html
```

**Using VS Code Live Server:**
1. Install "Live Server" extension in VS Code
2. Right-click on `src/index.html`
3. Select "Open with Live Server"

---

## 🗺 Sitemap

### Main Pages

```
the-nook/
│
├── Homepage (/)
│   └── src/index.html
│
├── About Us (/about)
│   └── src/pages/about/index.html
│
├── Menu (/menu)
│   └── src/pages/menu/index.html
│
├── Booking (/booking)
│   ├── src/pages/booking/index.html
│   └── src/pages/booking/deal.html
│
└── Contact (/contact)
    └── src/pages/contact/index.html
```

### Menu Detail Pages

#### Beverages (9 pages)
```
/menu-details/beverages/
├── brain-booster.html
├── classic-iced-tea.html
├── green-focus.html
├── honey-lemon-tea.html
├── iced-americano.html
├── latte.html
├── lychee-oolong-tea.html
├── matcha-latte.html
└── tropical-booster.html
```

#### Foods (9 pages)
```
/menu-details/foods/
├── avocado-toast.html
├── chicken-chop-with-rice.html
├── chicken-sandwich.html
├── egg-sandwich.html
├── granola-bowl.html
├── grilled-teriyaki-chicken-bowl.html
├── pasta-bowl.html
├── quinoa-salad.html
└── salmon-grain-bowl.html
```

### Navigation Flow

```
Homepage
├── Reserve Now → Booking System (Step 1: Date/Time)
│   ├── Step 2: Seat Selection
│   ├── Step 3: Payment
│   └── Step 4: Confirmation
│
├── See Menu → Menu Page
│   ├── Filter by Category (All/Promo/Beverages/Foods)
│   └── Click Item → Menu Detail Page
│
├── Menu → Menu Page
├── About Us → About Page
└── Contact → Contact Page

Promotional Deals (from Homepage)
├── Focus Fuel Bundle → Deal Booking Page
├── Brain Food Bundle → Deal Booking Page
└── Power Bundle → Deal Booking Page

Seat Options (from Homepage)
├── Solo Desk → Booking (pre-selected)
├── Group Table → Booking (pre-selected)
└── Private Table → Booking (pre-selected)
```

---

## 🎨 Design System

### Typography

#### Desktop Sizes
- **Display**: 64px, Bold, 100% line-height
- **H1**: 48px, Medium, 110% line-height
- **H2**: 42px, Medium, 110% line-height
- **H3**: 32px, Medium, 110% line-height
- **H4**: 28px, Medium, 110% line-height
- **H5**: 24px, Medium, 110% line-height
- **H6**: 16px, Medium, 120% line-height
- **Body (p)**: 16px, Regular, 20px line-height

#### Mobile Sizes
- **Display**: 40px, Bold, 110% line-height
- **H1**: 32px, Medium, 110% line-height
- **H2**: 28px, Medium, 110% line-height
- **H3**: 24px, Medium, 110% line-height
- **H4**: 20px, Medium, 110% line-height
- **H5**: 16px, Medium, 110% line-height
- **H6**: 14px, Medium, 110% line-height
- **Body (p)**: 14px, Light, 120% line-height

#### Fonts
- **Headings**: Labil Grotesk (Custom)
- **Body**: Inter (Google Fonts)

### Color Palette

#### Brand Colors
- **Brand 1** (Warm Beige):
  - Primary: `#e0bca2`
  - Dark: `#c8885b`
  - Light: `#f1e1d6`

- **Brand 2** (Brown):
  - Primary: `#a68170`
  - Dark: `#3c2c25` (Primary CTA color)
  - Light: `#d7c7bf`

#### Neutral Colors
- **Beige Tones**: `#fbf8f5` (backgrounds)
- **Gray Scale**: `#1f1f1f` (text) to `#f1f1f1` (light gray)

### Components

#### Buttons
1. **Primary Button** (`.btn-primary`)
   - Background: `var(--brand-2-700)` (#3c2c25)
   - Text: White
   - Padding: 16px 20px (mobile) / 20px 24px (desktop)
   - Hover: Slight lift + opacity change

2. **Secondary Button** (`.btn-secondary`)
   - Background: White
   - Text: `var(--primary-700)` (#1f1f1f)
   - Border: 1px solid
   - Hover: Slight lift + opacity change

3. **Tertiary Button** (`.btn-tertiary`)
   - Background: Transparent
   - Text: White
   - Hover: Slight lift + reduced opacity

### Spacing System
- Small: 12px / 16px
- Medium: 24px / 32px
- Large: 48px / 64px

### Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

---

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 📞 Contact Information

### The Nook Study Café

**Address:**  
123 Study Street, Singapore 123456  
(5-minute walk from Kent Ridge MRT)

**Operating Hours:**  
Monday - Sunday: 8:00 AM - 11:00 PM

**Contact:**  
Phone: +65 1234 5678  
Email: info@thenook.com

**Social Proof:**  
⭐ 4.9/5.0 Rating (700+ Google Reviews)  
🎓 2,000+ Study Sessions Booked  
⏰ 10,000+ Study Hours Logged

---

## 📝 Additional Features

### Seat Types & Pricing

1. **Solo Desk** - $4/hour
   - Max 2 people
   - Perfect for individual study
   - 10% student discount

2. **Group Table** - $12/hour
   - Max 6 people
   - Ideal for study groups
   - 10% student discount

3. **Private Table** - $22/hour
   - Max 12 people
   - Great for meetings/presentations
   - 10% student discount

### Weekly Deals

1. **Focus Fuel Bundle** - $18 (Save $7)
   - 4-hour Solo Desk + 1 Coffee + 1 Pastry

2. **Brain Food Bundle** - $25 (Save $6.25)
   - 4-hour Solo Desk + 1 Smoothie + 1 Sandwich

3. **Power Bundle** - $35 (Save $9)
   - 8-hour Solo Desk + 1 Coffee + 1 Pastry + 1 Sandwich + 1 Main Course

### Amenities

✓ High-Speed WiFi (500 Mbps)  
✓ Power Outlets at Every Seat  
✓ Air Conditioning  
✓ Comfortable Seating  
✓ Natural Lighting  
✓ Quiet Zones  
✓ Fresh Coffee & Food  
✓ Printing Services

---

## 🔒 Notes for Deployment

### Performance Optimization
- All images are optimized (WebP format where possible)
- Lazy loading implemented for images
- Minimal external dependencies (CDN-based)
- Clean, semantic HTML structure

### SEO Considerations
- Proper meta tags on all pages
- Semantic HTML5 elements
- Descriptive alt text for images
- Mobile-responsive design

### Future Enhancements (Recommended)
- Integration with payment gateway for real bookings
- Backend API for reservation management
- Email confirmation system
- Online ordering system for food/beverages
- Member login/loyalty program
- Blog section for study tips

---

<div align="center">

**Built with ❤️ for students by students**

© 2025 The Nook. All rights reserved.

</div>

