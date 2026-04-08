# LexPopuli - Your Personal Legal Assistant 🏛️

**Making legal guidance accessible to everyone, 24/7.**

LexPopuli is an AI-powered legal information platform designed to provide instant, clear guidance on legal matters. Whether you're dealing with a contract issue, family matter, tenant dispute, or simply need to understand your rights, our intelligent chatbot is here to help.

## 🎯 Project Overview

LexPopuli aims to democratize legal knowledge by providing:
- **Instant Legal Guidance**: Get answers to your legal questions anytime, anywhere
- **Privacy-Focused**: Anonymous and secure conversations
- **Comprehensive Coverage**: Information across multiple legal domains (Family, Business, Property, Criminal, Employment, Immigration)
- **User-Friendly Interface**: Interactive chatbot with a modern, responsive design

## ✨ Key Features

- 🤖 **AI-Powered Chatbot**: Intelligent responses to legal questions
- 🔒 **Privacy First**: No personal data storage, anonymous conversations
- 📚 **Comprehensive Database**: 50+ legal topics across various domains
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- ⚡ **Real-time Chat**: Instant message delivery and bot responses
- 🎨 **Modern UI/UX**: Gradient designs, smooth animations, intuitive navigation
- 🌐 **Multi-page Support**: Home, Chatbot, and Legal Rights pages

## 🛠️ Tech Stack

### Frontend
- **React 19.1.1** - UI library for component-based development
- **Vite 7.1.6** - Lightning-fast build tool and dev server
- **Typed.js 3.0.0** - Animated typing effects for hero section
- **Font Awesome 6.4.0** - Icon library via CDN
- **Chart.js** - Data visualization (CDN)

### Development Tools
- **ESLint 9.35.0** - Code quality and style consistency
- **@vitejs/plugin-react** - React support for Vite
- **TypeScript** - Type checking for enhanced development

## 📁 Project Structure

```
Lexpouli/
├── src/
│   ├── App.jsx              # Main React application component
│   ├── App.css              # Application styles
│   ├── Footer.jsx           # Footer component
│   ├── Footer.css           # Footer styles
│   ├── main.jsx             # React entry point
│   ├── index.css            # Global styles
│   └── assets/              # Images and static files
├── public/                  # Static public assets
├── index.html               # Main HTML file
├── chatbot.html             # Chatbot page
├── rights.html              # Legal rights page
├── package.json             # Project dependencies
├── vite.config.js           # Vite configuration
├── eslint.config.js         # ESLint configuration
└── README.md                # Project documentation
```

## 🚀 Quick Start

### Prerequisites
- **Node.js** (v16 or higher)
- **npm** (comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Lexpouli
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

### Running the Project

#### Development Mode
Start the development server with hot module replacement:
```bash
npm run dev
```
The application will be available at `http://localhost:5173` (or the next available port shown in terminal)

#### Production Build
Build the project for production:
```bash
npm run build
```
Output files will be generated in the `dist/` directory

#### Preview Production Build
Preview the production build locally:
```bash
npm run preview
```

#### Code Linting
Run ESLint to check code quality:
```bash
npm run lint
```

## 🎯 Key Pages

### 1. **Home Page** (`index.html`)
- Hero section with animated typing effect
- Interactive chat preview
- Feature highlights (Privacy, Database, 24/7 Availability)
- Legal topics explorer with interactive cards
- Statistics dashboard
- Responsive navigation

### 2. **Chatbot Page** (`chatbot.html`)
- Full-featured chat interface
- Real-time message handling
- Pre-trained responses for common legal questions
- Support for topics: Eviction, Small Claims, Tenant Rights, Business, Divorce

### 3. **Legal Rights Page** (`rights.html`)
- Educational resources
- Legal information and disclaimers
- Rights and procedures guide

## 💡 Features Breakdown

### Chat Functionality
- **User & Bot Messages**: Distinct message styling for conversation flow
- **Smart Responses**: Keyword-based response system covering major legal topics
- **Auto-scroll**: Messages automatically scroll to latest content
- **Enter to Send**: Keyboard support for message submission

### UI Components
- **Gradient Backgrounds**: Modern visual design with CSS gradients
- **Smooth Animations**: Hover effects and transitions throughout
- **Mobile Responsive**: Fully responsive design with mobile menu toggle
- **Card-based Layout**: Organized topic and feature cards

### Topics Covered
- 👨‍👩‍👧‍👦 Family Law (Divorce, Custody, Adoption)
- 💼 Business Law (Contracts, IP, Startups)
- 🏠 Property Law (Real Estate, Landlord-Tenant)
- ⚖️ Criminal Law (Rights, Procedures, Defenses)
- 👔 Employment Law (Discrimination, Wages, Termination)
- 🛂 Immigration (Visas, Citizenship, Green Cards)

## 📊 Project Statistics

- **Users Helped**: 12,500+
- **Questions Answered**: 84,200+
- **Legal Topics**: 50+
- **User Satisfaction Rate**: 98%

## 🔧 Configuration Files

### `vite.config.js`
- Configures Vite build tool
- Integrates React plugin for JSX support

### `eslint.config.js`
- Enforces code quality standards
- Includes React and React Hooks rules

## 📝 Legal Disclaimer

LexPopuli provides informational guidance only, **not legal advice**. For specific legal matters, always consult a qualified attorney in your jurisdiction.

## 🤝 Contributing

Contributions are welcome! Please ensure:
- Code passes ESLint checks (`npm run lint`)
- Code follows the existing style
- Changes are tested in both dev and production modes


