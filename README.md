📸 Demo



🚀 Tech Stack
Framework: Next.js 13
Styling: Tailwind CSS
CMS: Sanity.io
Deployment: Vercel

🧰 Features
Fully responsive e-commerce UI
Dynamic product listing and product pages
Integration with Sanity CMS for managing products and content
Server-side rendering (SSR) and static generation with Next.js
Modern file-based routing using the App Router
Clean and modular project structure

📂 Folder Structure (Simplified)
.
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── product/[slug]/page.tsx
├── components/
│   ├── Navbar.tsx
│   ├── ProductCard.tsx
│   └── Footer.tsx
├── lib/
│   └── sanity.ts
├── sanity/
│   ├── schemas/
│   └── sanity.config.ts
├── styles/
└── tailwind.config.js

🧪 Getting Started
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:
npm install
Set up Sanity Studio:
Install Sanity CLI: npm install -g @sanity/cli
Run: sanity init --template e-commerce
Configure environment variables in a .env.local file:
NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
NEXT_PUBLIC_SANITY_DATASET=production
Run the development server:
npm run dev
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
