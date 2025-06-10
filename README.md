# HomeDIY Web

This is the **frontend** for the HomeDIY MVP — a web app for DIY home improvement enthusiasts. Built with **Next.js 15**, **Tailwind CSS**, and **TypeScript** using the App Router.

## 🌟 Purpose

The frontend allows users to:
- Input a DIY idea via text (and soon: image upload)
- View AI-generated decorative renderings
- Select one and receive a step-by-step improvement plan
- Review a cost estimate, material list, and installation guide

## 🧱 Tech Stack

- [Next.js 15 (App Router)](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [shadcn/ui](https://ui.shadcn.com/) (optional component system)
- [React Hook Form](https://react-hook-form.com/)

## 📁 Folder Structure
app/
├── page.tsx # Entry page
├── components/ # UI components
├── features/ # Functional blocks: InputForm, RenderingGrid, PlanView
lib/
├── api.ts # Axios/fetch for backend requests
public/
styles/
tailwind.config.ts

## 🚀 Expected Behavior (Copilot Prompting)

> "Build a React component that takes user input and submits to `/api/intent`, then shows a rendering grid with 4 images returned."

> "Create a plan viewer that shows a shopping list and guides returned from the backend."

## 🛠 Local Development

```bash
pnpm install
pnpm dev
🧪 TODO
 Add image upload (Cloudinary or S3)

 Improve responsive layout for rendering grid
