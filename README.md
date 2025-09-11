# Module 1 - Major Project: Professional Landing Page
## Comprehensive Web Development Portfolio Piece

**⏱️ Timeline:** 4 weeks (1 month)  
**🎯 Skills Demonstrated:** HTML5, CSS3, Responsive Design, Git Workflow, Optional JavaScript  
**📊 Weight:** Major assignment covering Weeks 1-3 curriculum

---

## 🎯 Project Overview

Create a professional landing page for a business, service, or personal brand of your choice. This project will demonstrate mastery of all concepts learned in the first three weeks and serve as a showcase piece for your portfolio.

**Choose ONE of these options:**
- **Local Business:** Restaurant, coffee shop, fitness studio, salon
- **Tech Startup:** App launch, SaaS product, digital agency
- **Personal Brand:** Freelancer, consultant, creative professional
- **Non-Profit:** Community organization, charity, awareness campaign
- **Creative Concept:** Your own business idea or fictional company

---

## 📋 Technical Requirements

### **Week 1 Skills - HTML Foundation (Required)**
- [ ] **Semantic HTML5 structure** with proper document outline
- [ ] **Complete head section** with meta tags, title, favicon
- [ ] **Accessibility features** with proper alt text, ARIA labels where needed
- [ ] **Valid HTML** that passes W3C validation
- [ ] **Professional content hierarchy** using proper heading structure

### **Week 2 Skills - CSS Fundamentals (Required)**
- [ ] **External CSS file** with organized, commented code
- [ ] **Typography system** using Google Fonts with proper font hierarchy
- [ ] **Color scheme** with consistent palette (minimum 3 colors)
- [ ] **Box model mastery** with proper spacing and layout
- [ ] **Flexbox layouts** for navigation and content sections
- [ ] **CSS reset/normalize** for cross-browser consistency

### **Week 3 Skills - Advanced CSS (Required)**
- [ ] **Responsive design** that works on mobile, tablet, and desktop
- [ ] **CSS Grid** for complex layout sections
- [ ] **CSS positioning** for overlapping elements or special layouts
- [ ] **BEM methodology** for organized CSS class naming
- [ ] **Hover effects and transitions** for interactive elements
- [ ] **Media queries** with mobile-first approach

---

## 🏗️ Page Structure Requirements

### **1. Header Section**
```html
<header class="site-header">
    <!-- Navigation bar with logo and menu -->
    <!-- Hero section with compelling headline -->
    <!-- Call-to-action button -->
</header>
```

**Must Include:**
- Logo or brand name
- Navigation menu (minimum 4 items)
- Compelling headline and subheadline
- Primary call-to-action button
- Hero image or background

### **2. Main Content Sections (Choose 4-6)**
Pick the sections that best fit your chosen business/brand:

**🏢 Business Options:**
- About Us / Our Story
- Services / Products
- Features / Benefits
- Team / Staff
- Testimonials / Reviews
- Portfolio / Work Examples
- Pricing / Packages

**🎨 Creative Options:**
- Process / How It Works
- Why Choose Us
- Our Mission / Values
- Case Studies
- Blog Preview
- Awards / Recognition

### **3. Footer Section**
```html
<footer class="site-footer">
    <!-- Contact information -->
    <!-- Social media links -->
    <!-- Copyright and legal -->
</footer>
```

**Must Include:**
- Contact information with proper semantic markup
- Social media icons/links (minimum 3)
- Copyright notice
- Additional navigation or legal links

---

## 📱 Responsive Design Requirements

### **Mobile First Approach:**
- [ ] Design starts at 320px width minimum
- [ ] Touch-friendly button sizes (minimum 44px)
- [ ] Readable text without zooming
- [ ] Easy navigation on small screens

### **Breakpoint Requirements:**
```css
/* Mobile First Base Styles */
/* Default styles for mobile */

/* Tablet: 768px and up */
@media (min-width: 768px) {
    /* Tablet-specific styles */
}

/* Desktop: 1024px and up */  
@media (min-width: 1024px) {
    /* Desktop-specific styles */
}

/* Large Desktop: 1200px and up */
@media (min-width: 1200px) {
    /* Large screen styles */
}
```

### **Responsive Testing:**
- [ ] Test on actual mobile devices or browser dev tools
- [ ] Ensure all content is accessible at every breakpoint
- [ ] Verify images scale appropriately
- [ ] Confirm navigation works on touch devices

---

## 🎨 Design Requirements

### **Visual Design Standards:**
- [ ] **Consistent spacing** using a spacing scale (8px, 16px, 24px, etc.)
- [ ] **Typography hierarchy** with clear size differences
- [ ] **Color accessibility** meeting WCAG contrast requirements
- [ ] **Professional imagery** (use Unsplash, Pexels, or original photos)
- [ ] **White space** for clean, uncluttered layout

### **Required Design Elements:**
- [ ] **Loading states** or transitions for better UX
- [ ] **Hover effects** on interactive elements
- [ ] **Focus states** for keyboard navigation
- [ ] **Consistent button styles** throughout the site
- [ ] **Card components** using BEM methodology

---

## 💻 Technical Implementation

### **File Structure:**
```
project-name/
├── index.html
├── css/
│   ├── styles.css
│   └── normalize.css (optional)
├── images/
│   ├── logo.png
│   ├── hero-image.jpg
│   └── other-images/
├── js/
│   └── script.js (for stretch goals)
└── README.md
```

### **CSS Organization (BEM Required):**
```css
/* Component Example */
.hero {
    /* Block styles */
}

.hero__title {
    /* Element styles */
}

.hero__title--large {
    /* Modifier styles */
}

.hero__button {
    /* Element styles */
}

.hero__button--primary {
    /* Modifier styles */
}
```

### **Git Workflow Requirements:**
- [ ] **Minimum 8 meaningful commits** throughout development
- [ ] **Descriptive commit messages** following best practices
- [ ] **Feature branch workflow** (create branches for major features)
- [ ] **Clean commit history** with logical progression
- [ ] **README.md** with project description and setup instructions

---

## 🚀 Stretch Goals (Optional JavaScript)

### **Beginner JavaScript Features (Choose 1-2):**
- [ ] **Mobile menu toggle** - Hamburger menu that opens/closes
- [ ] **Smooth scrolling** navigation links
- [ ] **Image carousel/slider** for testimonials or portfolio
- [ ] **Form validation** for contact forms
- [ ] **Scroll animations** - fade in elements as user scrolls

### **Example Mobile Menu:**
```javascript
// Simple mobile menu toggle
const menuButton = document.querySelector('.menu-toggle');
const navigation = document.querySelector('.nav-menu');

menuButton.addEventListener('click', () => {
    navigation.classList.toggle('nav-menu--open');
});
```

### **Example Smooth Scrolling:**
```javascript
// Smooth scroll for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});
```

---

## 📅 Development Timeline

### **Week 1: Planning & Setup (25% complete)**
- [ ] Choose your business/brand concept
- [ ] Create wireframes or sketches
- [ ] Set up Git repository and file structure
- [ ] Write HTML structure with semantic elements
- [ ] **Deliverable:** Complete HTML structure with placeholder content

### **Week 2: Core Styling (50% complete)**
- [ ] Implement CSS reset and typography system
- [ ] Create navigation and header styling
- [ ] Style main content sections
- [ ] Add color scheme and spacing
- [ ] **Deliverable:** Desktop version with basic styling

### **Week 3: Responsive & Polish (75% complete)**
- [ ] Implement responsive design with media queries
- [ ] Add hover effects and transitions
- [ ] Optimize images and performance
- [ ] Test across devices and browsers
- [ ] **Deliverable:** Fully responsive site

### **Week 4: Final Polish & Stretch Goals (100% complete)**
- [ ] Add final content and copy
- [ ] Implement JavaScript features (if desired)
- [ ] Cross-browser testing and bug fixes
- [ ] Documentation and final Git cleanup
- [ ] **Deliverable:** Production-ready landing page

---

## 📊 Assessment Rubric

### **HTML Structure & Semantics (20 points)**
- **Excellent (18-20):** Perfect semantic structure, accessibility features, validates without errors
- **Good (14-17):** Good semantic structure, minor validation issues
- **Satisfactory (10-13):** Basic structure present, some semantic issues
- **Needs Work (0-9):** Poor structure, major validation errors

### **CSS Implementation (25 points)**
- **Excellent (23-25):** Professional styling, perfect BEM implementation, advanced techniques
- **Good (18-22):** Good styling, mostly consistent methodology
- **Satisfactory (13-17):** Basic styling present, some organizational issues
- **Needs Work (0-12):** Poor styling, lack of organization

### **Responsive Design (20 points)**
- **Excellent (18-20):** Flawless across all devices, mobile-first approach
- **Good (14-17):** Works well on most devices, minor issues
- **Satisfactory (10-13):** Basic responsiveness, some layout problems
- **Needs Work (0-9):** Not responsive or major layout failures

### **Design & UX (15 points)**
- **Excellent (14-15):** Professional design, excellent user experience
- **Good (11-13):** Good design choices, minor UX issues
- **Satisfactory (8-10):** Acceptable design, room for improvement
- **Needs Work (0-7):** Poor design choices, bad user experience

### **Code Quality & Git (10 points)**
- **Excellent (9-10):** Clean code, excellent Git workflow, comprehensive commits
- **Good (7-8):** Good code quality, decent Git usage
- **Satisfactory (5-6):** Acceptable code, basic Git workflow
- **Needs Work (0-4):** Poor code quality, insufficient Git usage

### **Content & Completion (10 points)**
- **Excellent (9-10):** Complete, professional content, all requirements met
- **Good (7-8):** Good content, most requirements met
- **Satisfactory (5-6):** Basic content, some requirements missing
- **Needs Work (0-4):** Incomplete or poor content

### **Bonus: JavaScript Implementation (+5 points)**
- Successfully implementing any JavaScript stretch goals

---

## 📝 Submission Requirements

### **Repository Submission:**
1. **Public GitHub repository** with descriptive name
2. **Live demo** using GitHub Pages or Netlify
3. **Complete README.md** with:
   - Project description
   - Features implemented
   - Technologies used
   - Setup instructions
   - Live demo link
   - Screenshots

### **README.md Template:**
```markdown
# Project Name

Brief description of your landing page and the business/brand it represents.

## Features
- List key features implemented
- Responsive design
- Accessibility features
- Any JavaScript functionality

## Technologies Used
- HTML5
- CSS3
- JavaScript (if applicable)
- Google Fonts
- [Any other tools]

## Live Demo
[Link to your deployed site]

## Setup Instructions
1. Clone the repository
2. Open index.html in your browser
3. Or visit the live demo link above

## Screenshots
[Add screenshots of desktop and mobile versions]
```

---

## 🆘 Resources & Support

### **Design Inspiration:**
- **Dribbble:** https://dribbble.com/tags/landing_page
- **Awwwards:** https://www.awwwards.com/
- **Land-book:** https://land-book.com/
- **OnePageLove:** https://onepagelove.com/

### **Assets & Tools:**
- **Images:** Unsplash, Pexels, Pixabay
- **Icons:** Font Awesome, Feather Icons, Heroicons
- **Colors:** Coolors.co, Adobe Color
- **Fonts:** Google Fonts, Font Pair

### **Technical Help:**
- **MDN Web Docs:** https://developer.mozilla.org/
- **W3Schools:** https://www.w3schools.com/
- **CSS Tricks:** https://css-tricks.com/
- **Can I Use:** https://caniuse.com/

### **Validation & Testing:**
- **HTML Validator:** https://validator.w3.org/
- **CSS Validator:** https://jigsaw.w3.org/css-validator/
- **Accessibility:** https://wave.webaim.org/
- **Performance:** https://pagespeed.web.dev/

---

## 🏆 Success Criteria

**You'll know you've succeeded when:**
- Your landing page looks professional and modern
- It works perfectly on all device sizes
- Your code is clean, organized, and well-commented
- You can explain every design and technical decision you made
- Other students say "Wow, I want to hire this business!"

**This project should be portfolio-worthy** - something you're proud to show potential employers or clients. Take your time, iterate on the design, and create something that represents your best work.
