# 🏠 HomeImproveAI - Frontend

![HomeImproveAI Screenshot](/public/screenshot.png) <!-- Replace with actual screenshot -->

**AI-Powered Home Design Generator** | Next.js 15 · TypeScript · Tailwind CSS

Transform your home improvement ideas into reality with AI-generated designs, material lists, and step-by-step guides.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Next.js](https://img.shields.io/badge/Next.js-15.0.0-black.svg)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-blue.svg)](https://www.typescriptlang.org/)

## ✨ Features

- 🖼️ **AI-Powered Renderings**: Generate 4+ design options from text or image inputs
- 🛒 **Smart Shopping List**: Automatically generated materials and tools list
- ⏱️ **Project Estimator**: Time and cost calculations for your projects
- 📱 **Responsive Design**: Fully mobile-optimized interface
- 🔍 **Type-Safe**: Full TypeScript integration for better developer experience
- 🎨 **Modern UI**: Beautiful, accessible components with Tailwind CSS

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org/) (App Router)
- **Language**: [TypeScript 5](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) + [shadcn/ui](https://ui.shadcn.com/)
- **State Management**: [Zustand](https://zustand-demo.pmnd.rs/)
- **API Client**: [Axios](https://axios-http.com/) with TypeScript types
- **Form Handling**: [React Hook Form](https://react-hook-form.com/)
- **Testing**: [Jest](https://jestjs.io/) + [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

## 📦 Getting Started

### Prerequisites

- Node.js 18+
- pnpm (recommended) or npm/yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/homeimproveai-frontend.git
   cd homeimproveai-frontend
2. Install dependencies:
   pnpm install
   # or
   npm install
   # or
   yarn install
3. Set up environment variables:
   cp .env.example .env.local
4. Run the development server:
   pnpm dev
   # or
   npm run dev
   # or
   yarn dev
Open http://localhost:3000 in your browser.
🏗️ Project Structure
homeimproveai-frontend/
├── app/                    # Next.js App Router
│   ├── (auth)/             # Authentication routes
│   ├── api/                # API route handlers
│   ├── generate/           # AI generation pages
│   ├── projects/           # Project management
│   └── layout.tsx          # Root layout
├── components/             # Reusable components
├── hooks/                  # Custom React hooks
├── lib/                    # Utilities and helpers
│   ├── api/                # API client configuration
│   └── stores/             # Zustand state stores
├── public/                 # Static assets
├── styles/                 # Global styles
├── types/                  # TypeScript type definitions
└── tests/                  # Test files
🧪 Running Tests
pnpm test
# or
npm run test
# or
yarn test
🚀 Deployment
Deploy to Vercel:

https://vercel.com/button

🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the project

Create your feature branch (git checkout -b feat/amazing-feature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feat/amazing-feature)

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
