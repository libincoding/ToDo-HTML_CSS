# 📋 TaskFlow - Modern TODO Dashboard

A stunning, fully responsive TODO task management dashboard built with **pure HTML5 and advanced CSS** - no JavaScript, no frameworks, no libraries.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## ✨ Features

### 🎨 **Pure CSS Interactivity**
- **Dark Mode Toggle** - Smooth theme switching using checkbox hack
- **Custom Checkboxes** - Animated task completion with `:checked` pseudo-class
- **Filter Tabs** - Show All/Active/Completed tasks using radio buttons
- **Collapsible Widgets** - Accordion-style activity feed
- **Hover Animations** - Interactive cards, buttons, and charts

### 📊 **Visual Components**
- **KPI Stats Cards** - 4 animated cards with glassmorphism effects
- **Progress Bars** - Animated completion tracking
- **Pie Chart** - CSS `conic-gradient` visualization (60/25/15 split)
- **Bar Chart** - Weekly activity with staggered animations
- **Streak Widget** - Animated flame icon with shimmer effect

### 🎯 **Task Management**
- 10 sample tasks with priority badges (High/Medium/Low)
- Custom checkboxes with strike-through on completion
- Slide-out delete buttons on hover
- Due date badges with emoji icons
- Scrollable task list with custom scrollbar

### 📱 **Responsive Design**
- CSS Grid layout with named areas
- Mobile-first responsive breakpoints (768px, 1024px)
- Flexbox for component layouts
- Optimized for desktop, tablet, and mobile

### ♿ **Accessibility**
- Semantic HTML5 structure
- ARIA labels on interactive elements
- `:focus-visible` keyboard navigation
- `prefers-reduced-motion` support
- `prefers-contrast: high` support
- Proper heading hierarchy

## 🚀 Quick Start

### **Method 1: Direct Opening (Recommended)**
Simply double-click `index.html` in your file explorer.

### **Method 2: Browser Address Bar**
```
file:///C:/Users/ASUS/.gemini/antigravity/scratch/todo-dashboard/index.html
```

### **Method 3: Local Development Server**

**Using Python:**
```bash
cd todo-dashboard
python -m http.server 8000
```
Then open: `http://localhost:8000`

**Using Node.js (npx):**
```bash
cd todo-dashboard
npx serve
```

**Using PHP:**
```bash
cd todo-dashboard
php -S localhost:8000
```

## 🎮 Usage

### **Dark Mode**
Click the moon/sun toggle in the header to switch themes.

### **Task Filtering**
- **All** - Show all tasks
- **Active** - Show only unchecked tasks
- **Completed** - Show only checked tasks

### **Task Completion**
Click the checkbox next to any task to mark it complete. The task title will strike through and fade.

### **Activity Feed**
Click "Recent Activity" in the sidebar to expand/collapse the activity list.

### **Responsive Testing**
Resize your browser window to see the layout adapt:
- **Desktop** (>1024px): Grid layout with sidebar
- **Tablet** (768px-1024px): Stacked layout
- **Mobile** (<768px): Single column, simplified navigation

## 🛠️ Technical Highlights

### **CSS Techniques Used**
- CSS Grid with `grid-template-areas`
- Flexbox for component layouts
- CSS Custom Properties (CSS Variables) for theming
- `conic-gradient` for pie charts
- `backdrop-filter` for glassmorphism
- Neumorphic shadows with `box-shadow`
- Keyframe animations (`@keyframes`)
- Pseudo-classes (`:checked`, `:hover`, `:focus-visible`, `:has()`)
- Pseudo-elements (`::before`, `::after`, `::placeholder`)
- `clip-path` for custom shapes
- Sibling selectors (`~`) for filter logic
- Custom scrollbar styling (`::-webkit-scrollbar`)

### **No JavaScript Required**
All interactivity is achieved through:
- Checkbox hack for toggles
- Radio buttons for filters
- CSS `:checked` pseudo-class
- Sibling and child selectors
- CSS transitions and animations

## 📁 Project Structure

```
todo-dashboard/
├── index.html          # Complete dashboard (HTML + embedded CSS)
└── README.md          # This file
```

## 🎨 Design System

### **Color Palette**
- **Accent**: `#3b82f6` (Blue)
- **Success**: `#10b981` (Green)
- **Warning**: `#f59e0b` (Orange)
- **Danger**: `#ef4444` (Red)

### **Typography**
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

### **Spacing Scale**
- XS: 0.25rem, SM: 0.5rem, MD: 1rem, LG: 1.5rem, XL: 2rem, 2XL: 3rem

### **Border Radius**
- SM: 0.375rem, MD: 0.5rem, LG: 0.75rem, XL: 1rem, Full: 9999px

## 🌐 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ⚠️ IE 11 (Limited support - no CSS Grid)

## 📝 Customization

### **Changing Colors**
Edit the CSS variables in `:root`:
```css
:root {
    --accent: #3b82f6;
    --success: #10b981;
    --warning: #f59e0b;
    --danger: #ef4444;
}
```

### **Adding Tasks**
Duplicate a `.task-item` div and update:
- `id` and `for` attributes (must match)
- Task title, description, priority, and due date

### **Modifying Charts**
- **Pie Chart**: Adjust `conic-gradient` percentages
- **Bar Chart**: Change `.bar` height percentages

## 📄 License

This project is open source and available for personal and commercial use.

## 🤝 Contributing

Feel free to fork, modify, and enhance this dashboard. Some ideas:
- Add more chart types (line charts with SVG)
- Create additional widget types
- Implement more filter options
- Add print stylesheet
- Create theme variations

## 📧 Contact

For questions or feedback, feel free to reach out!

---

**Built with ❤️ using pure HTML5 & CSS3**
