# 🚗 AutoPro Vehicle Service Center Management System

A modern, responsive web-based management system for vehicle service centers built with HTML, CSS, JavaScript, and Bootstrap 5. This frontend-only application helps manage customers, vehicles, service bookings, and generates invoices with a professional dashboard.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![Bootstrap](https://img.shields.io/badge/bootstrap-5.3-purple.svg)

## ✨ Features

### 📊 Dashboard
- Real-time statistics (Total Customers, Vehicles, Today's Bookings, Revenue)
- Monthly revenue chart using Chart.js
- Recent bookings quick view
- Responsive cards with hover animations

### 👥 Customer Management
- Add, Edit, Delete customer records
- Complete vehicle details (Number, Brand, Model, Fuel Type, Year)
- Search functionality by name, mobile, or vehicle number
- Form validation for required fields
- Mobile number validation (10 digits)

### 📅 Service Booking
- Select customer and service type
- Multiple service options:
  - General Service
  - Oil Change
  - Brake Service
  - Engine Repair
  - Washing
  - Battery Replacement
  - AC Service
  - Wheel Alignment
- Date and time selection
- Technician assignment
- Automatic cost calculation with GST (18%)
- Discount option available
- Final bill generation

### 📜 Service History
- View all previous services
- Search by vehicle number or customer name
- Service details (date, technician, cost, status)
- Status indicators (Pending, Completed)
- Printable invoice for each service

### 🎨 UI/UX Features
- **Dark/Light Mode** toggle
- Professional blue and white theme
- Smooth fade-in animations
- Responsive sidebar navigation
- Mobile-friendly design
- Font Awesome icons
- Interactive cards with hover effects
- Clean and modern interface

### 💾 Data Persistence
- All data stored in browser's LocalStorage
- Sample data pre-loaded for demonstration
- Data persists across browser sessions
- No backend required

### 🖨️ Invoice Generation
- Printable professional invoices
- Complete service and cost breakdown
- Customer and vehicle details
- GST calculation display

## 🚀 Quick Start

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server or installation required

### Installation

1. **Clone or download the repository**
   ```bash
   git clone <repository-url>
   cd auto-pro-service-center
