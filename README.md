# 📊 ADmyBRAND Insights - Analytics Dashboard

A modern, responsive analytics dashboard built with React and Next.js, featuring beautiful UI design, interactive charts, and real-time data visualization for digital marketing agencies.

## 🚀 Live Demo

**🌐 [View Live Dashboard](https://ai-powered-analytics-dashboard-qvme-e47rkszqn.vercel.app/)**

## ✨ Features

### 📈 **Interactive Analytics**
- **Real-time Data Visualization** - Line charts, bar charts, and pie charts with smooth animations
- **Metric Cards** - Key performance indicators with growth percentages and trend indicators
- **Advanced Data Table** - Sortable columns, search functionality, and pagination
- **Period Selection** - Toggle between 7d, 30d, and 90d views

### 🎨 **Modern UI/UX**
- **Dark/Light Mode Toggle** - Seamless theme switching with system preference detection
- **Responsive Design** - Perfect experience on desktop, tablet, and mobile devices
- **Smooth Animations** - Micro-interactions and hover effects throughout
- **Glassmorphism Design** - Modern aesthetic with beautiful gradients and shadows

### ⚡ **Performance & Accessibility**
- **Fast Loading** - Optimized with Next.js 14+ App Router
- **SEO Friendly** - Meta tags and semantic HTML structure
- **Keyboard Navigation** - Full accessibility support
- **Cross-browser Compatible** - Works on all modern browsers

## 📦 Installation & Setup

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn package manager
- Git (optional)

### Quick Start

```bash
# Clone the repository
git clone https://https://github.com/shivswrj/AI-Powered-Analytics-Dashboard.git
cd admybrand dashboard

# Install dependencies
npm install

# Start development server
npm run dev

### Manual Setup

```bash
# Create new Next.js project
npx create-next-app@latest admybrand-dashboard --tailwind --eslint --app
cd admybrand-dashboard

# Install required dependencies
npm install recharts lucide-react

# Configure Tailwind for dark mode (see tailwind.config.js)
# Copy dashboard component to app/page.js
# Update app/globals.css with Tailwind directives

# Run the project
npm run dev
```

Visit `http://localhost:3000` to see the dashboard in action.

## 📁 Project Structure

```
admybrand-dashboard/
├── app/
│   ├── globals.css          # Global styles and Tailwind imports
│   ├── layout.js           # Root layout component
│   ├── page.js             # Main dashboard component
│   └── favicon.ico
├── public/                 # Static assets
├── components/            # Reusable components (if extracted)
├── tailwind.config.js     # Tailwind configuration
├── next.config.js         # Next.js configuration
├── package.json           # Dependencies and scripts
└── README.md             # Project documentation
```

## 🎨 Key Components

### MetricCard Component
- Displays KPI metrics with animated counters
- Gradient backgrounds and hover effects
- Growth percentage indicators with color coding

### Interactive Charts
- **Line Chart**: Revenue trends over time
- **Bar Chart**: Traffic source distribution  
- **Pie Chart**: Device type breakdown
- All charts feature smooth animations and tooltips

### Data Table
- Sortable columns with visual indicators
- Real-time search filtering
- Pagination with navigation controls
- Responsive design for mobile viewing

## 🌐 Deployment

### Deploy to Vercel (Recommended)
# Using Vercel CLI
npm install -g vercel
vercel login
vercel




