# Splitr – Modern Bill Splitting App

> Effortlessly split expenses, track payments, and manage groups with a beautiful, modern UI.

---

## ✨ Features

- **Modern UI**: Built with shadcn/ui, Radix UI, and Tailwind CSS for a clean, responsive, and accessible experience.
- **Authentication**: Secure sign-in/sign-up with Clerk.
- **Real-time Data**: Powered by Convex for instant updates and collaboration.
- **Expense Management**: Add, split, and track expenses with friends or groups.
- **Smart Splitting**: Supports equal, percentage, and exact amount splits.
- **Group Support**: Create and manage groups for trips, events, or households.
- **Payment Reminders**: Automated email reminders for outstanding balances (Resend integration).
- **Analytics**: Visualize your spending with charts (Recharts).
- **Mobile Friendly**: Fully responsive and touch-optimized.
- **Dark Mode**: Seamless light/dark theme switching.

---

## 🛠️ Tech Stack

- [Next.js 15 (App Router)](https://nextjs.org/)
- [React 19](https://react.dev/)
- [shadcn/ui](https://ui.shadcn.com/) & [Radix UI](https://www.radix-ui.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Convex](https://convex.dev/) (serverless database & functions)
- [Clerk](https://clerk.com/) (authentication)
- [Resend](https://resend.com/) (email delivery)
- [Recharts](https://recharts.org/) (charts & analytics)
- [Sonner](https://sonner.emilkowal.ski/) (toasts/notifications)

---

## 🚀 Getting Started

1. **Clone the repo:**

   ```bash
   git clone https://github.com/Kakarot30/AI-Bill-Splitting-.git
   cd AI-Bill-Splitting-
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure environment variables:**

   - Copy `.env.local.example` to `.env.local` (or use the provided `.env.local`).
   - Fill in your keys for Convex, Clerk, Resend, etc.

4. **Run the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open the app:**
   Visit [http://localhost:3000](http://localhost:3000)

---

## ⚙️ Environment Variables

Your `.env.local` should include:

```
NEXT_PUBLIC_CONVEX_URL=...
CONVEX_DEPLOY_KEY=...
CONVEX_DEPLOYMENT=...
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...
NEXT_PUBLIC_CLERK_SIGN_IN_URL=...
NEXT_PUBLIC_CLERK_SIGN_UP_URL=...
CLERK_JWT_ISSUER_DOMAIN=...
RESEND_API_KEY=...
GEMINI_API_KEY=...
```

---

## 🖌️ Modern UI Concepts

- **Component-driven**: All UI is built from reusable, accessible components (see `/components` and `/components/ui`).
- **Utility-first styling**: Tailwind CSS for rapid, consistent design.
- **Dark mode**: Theme toggling with `next-themes` and custom CSS variables.
- **Radix UI**: For accessible popovers, dialogs, tabs, and more.
- **Motion & Feedback**: Subtle animations, toasts, and loaders for a delightful UX.

---

## 📁 Project Structure

- `app/` – Next.js app directory (routing, pages, layouts)
- `components/` – Shared and UI components (shadcn/ui)
- `convex/` – Convex backend functions and types
- `lib/` – Utilities and helpers
- `public/` – Static assets (images, icons, etc.)

---

## 📦 Scripts

- `npm run dev` – Start the dev server
- `npm run build` – Build for production
- `npm run start` – Start the production server
- `npm run lint` – Lint the codebase

---

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.
