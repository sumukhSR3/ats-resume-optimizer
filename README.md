# ats-resume-optimizer
# AI Resume Analyzer

An intelligent, production-ready web application built with **React Router v8**, **Tailwind CSS v4**, and **TypeScript** for analyzing resumes and providing feedback/scores.

## 🚀 Features

- **Resume Upload & Parsing**: Seamlessly drag and drop resumes (PDFs) to start the analysis.
- **ATS Scoring & Matching**: Evaluate candidates' resumes against specific job roles/descriptions.
- **Feedback System**: Clear, detailed feedback categorizing candidate strengths, weaknesses, and potential score metrics.
- **Modern User Interface**: Styled using Tailwind CSS v4, featuring a beautiful custom design system, modern gradients, glassmorphism shadows, and smooth HMR.
- **TypeScript Support**: Full, end-to-end type safety.

---

## 📁 Project Structure

```
├── app/                        # Main application code
│   ├── routes/                 # App routes and views
│   │   └── home.tsx            # Main landing/home route
│   ├── welcome/                # Welcome component & assets
│   │   ├── welcome.tsx         # Welcome page interface
│   │   └── logo-*.svg          # UI assets
│   ├── app.css                 # Global styles and Tailwind design system rules
│   ├── root.tsx                # App root layout, links, and Error Boundary
│   └── routes.ts               # React Router config definition
├── public/                     # Public static assets
│   ├── favicon.ico
│   └── pdf.worker.min.mjs      # Pre-bundled PDF.js worker
├── package.json                # Project dependencies and run scripts
├── tsconfig.json               # TypeScript configuration
├── vite.config.ts              # Vite compiler configuration
└── react-router.config.ts      # React Router compilation configuration
```

---

## ⚡ Getting Started

### 1. Installation
Install the project dependencies:
```bash
npm install
```

### 2. Run the Development Server
Start the development server with Hot Module Replacement (HMR):
```bash
npm run dev
```
The application will be available at [http://localhost:5173](http://localhost:5173).

### 3. Build for Production
Generate the production-ready build artifacts:
```bash
npm run build
```

---

## 🛠 Tech Stack

- **Framework**: [React Router](https://reactrouter.com/) (v8)
- **Bundler**: [Vite](https://vite.dev/) (v8)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (v4)
- **Icons & Animation**: Custom svg icons, `tw-animate-css`
- **Language**: [TypeScript](https://www.typescriptlang.org/)
