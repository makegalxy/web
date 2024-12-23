<img src="./docs/cvz-logo.png" alt="description" width="120" height="120">

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)

# Web - Convērs

This is the frontend implementation for Convērs, built with **Next.js 15**, **Tailwind CSS**, **ShadCN**, and **ESLint 9**.

## Table of Contents
- [Getting Started](#getting-started)
- [Requirements](#requirements)
- [Setup Instructions](#setup-instructions)
- [Development](#development)
- [Folder Structure](#folder-structure)
- [License](#license)

---

## Getting Started
Start your journey by setting up the frontend for Convērs, enabling secure and intuitive conversation threads across distributed systems.

---

## Requirements
Ensure you have the following installed before proceeding:
- Node.js (>= 18.x)
- npm (>= 9.x) or yarn (>= 1.x)
- Docker engine (optional for API integration)

---

## Setup Instructions

### 1. Clone the Repository
Clone the project repository to your local machine:
```bash
git clone https://github.com/convrz/frontend.git
cd frontend
```

### 2. Install Dependencies
Install all required dependencies:
```bash
npm install
# or
yarn install
```

### 3. Environment Variables
Create a `.env.local` file in the root directory and configure the following variables:
```bash
NEXT_PUBLIC_API_URL=https://api.convrz.com
NEXT_PUBLIC_APP_NAME=Convrz
```

### 4. Run the Development Server
Start the local development server:
```bash
npm run dev
# or
yarn dev
```
Visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## Development

### Code Quality
This project uses **ESLint 9** to enforce code quality and standards. Run the following command to lint your code:
```bash
npm run lint
# or
yarn lint
```

### Styling
We use **Tailwind CSS** for utility-first styling. Customize your styles in the `tailwind.config.js` file.

### Component Library
ShadCN is used as the base component library. To add new components, run:
```bash
npx shadcn add [component-name]
```
Visit the [ShadCN documentation](https://ui.shadcn.com/docs) for more details.

### Build
Build the application for production:
```bash
npm run build
# or
yarn build
```
The output will be in the `.next/` directory.

---

## Folder Structure
```plaintext
frontend/
├── public/               # Static files (images, fonts, etc.)
├── src/                  # Source code
│   ├── components/       # Reusable components
│   ├── pages/            # Next.js pages
│   ├── styles/           # Tailwind and global CSS
│   ├── utils/            # Utility functions
│   ├── hooks/            # Custom hooks
│   └── context/          # React Context providers
├── .eslintrc.js          # ESLint configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── package.json          # Dependencies and scripts
└── README.md             # Project documentation
```

---

Made in 🇻🇳 🚀
