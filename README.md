# InvoSync - Invoice Management System
Powered By Finkraft.ai

<div align="center">
  <h3>🏆 Hackathon Round </h3>
  <p>A full-stack web application for automated invoice downloading, parsing, and management</p>
  
  ![License](https://img.shields.io/badge/license-MIT-blue.svg)
  ![Node.js](https://img.shields.io/badge/Node.js-v18+-green.svg)
  ![React](https://img.shields.io/badge/React-v18+-blue.svg)
</div>

---

## 📋 Table of Contents

- [About The Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🚀 About The Project

**InvoSync** is a comprehensive invoice management system built as part of a hackathon challenge. The application simulates a real-world workflow where users can download airline invoice PDFs using passenger data, extract key information from those PDFs using intelligent parsing, and manage all invoices through an intuitive dashboard.

### Problem Statement
- **Invoice Download**: Fetch invoice PDFs from airline portals using passenger records
- **Invoice Parsing**: Extract structured data (Invoice Number, Date, Airline, Amount, GSTIN) from PDFs
- **Dashboard Management**: Provide a responsive UI for managing invoices with real-time status updates
- **Backend APIs**: RESTful APIs for seamless frontend-backend communication

---

## ✨ Features

### Core Features
- 📄 **Automated PDF Download** - Download invoices from airline portals using passenger data
- 🔍 **Intelligent PDF Parsing** - Extract key fields (Invoice No, Date, Airline, Amount, GSTIN)
- 📊 **Interactive Dashboard** - Real-time status tracking and management
- 🔄 **Status Management** - Track download and parsing status for each record
- 📈 **Analytics & Summary** - View airline-wise totals and high-value invoices

### UI/UX Features
- ✅ **Responsive Design** - Works seamlessly on desktop and mobile
- 🎯 **Real-time Updates** - Live status updates with loading indicators
- 🏷️ **Flag System** - Mark invoices for review
- 📱 **Bootstrap UI** - Clean, modern interface
- 🚨 **Error Handling** - Graceful error states and user feedback

### Advanced Features
- 🔗 **PDF Viewer Integration** - Direct PDF access from dashboard
- 📊 **Summary Statistics** - Total amounts, airline breakdowns
- 💰 **High-value Detection** - Identify invoices above specified thresholds
- 📁 **File Management** - Organized storage of PDFs and parsed data

---

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern React with Hooks
- **React Bootstrap** - Responsive UI components
- **Axios** - HTTP client for API calls
- **Bootstrap 5** - CSS framework

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **PDF-Parse** - PDF text extraction
- **Axios** - HTTP client for external APIs
- **CORS** - Cross-origin resource sharing
- **fs-extra** - Enhanced file system operations

### Development Tools
- **npm** - Package manager
- **Git** - Version control
- **GitHub** - Repository hosting

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- **Node.js** (v18 or higher)
- **npm** (v8 or higher)
- **Git**


---

## 💻 Usage

### Step-by-Step Workflow

1. **View Passenger Records**
   - Navigate to the "Passenger Records" tab
   - See all passenger data with initial "Pending" status

2. **Download Invoices**
   - Click "Download Invoice" for each passenger
   - Status updates to "Success", "Not Found", or "Error"
   - PDFs are saved locally and accessible via "Open PDF"

3. **Parse Invoices**
   - Click "Parse Invoice" (only enabled after successful download)
   - System extracts key data from PDFs
   - Parsed invoices appear in the "Parsed Invoices" tab

4. **Manage Invoices**
   - View all parsed invoices in a structured table
   - Flag invoices for review using checkboxes
   - Access PDFs directly from the dashboard

5. **View Analytics**
   - Monitor total invoices and amounts in summary cards
   - Track airline-wise breakdowns
   - Identify high-value invoices

---
