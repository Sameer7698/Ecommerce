# 🧠 E-Commerce Web Application





## 🚀 Live Demo






---

## 🎯 Features
- Fully responsive e-commerce UI
- Dynamic product listing and product pages
- Integration with Sanity CMS for managing products and content
- Server-side rendering (SSR) and static generation with Next.js
- Modern file-based routing using the App Router
- Clean and modular project structure


---

## 📦 Tech Stack
- Framework: Next.js 13
- Styling: Tailwind CSS
- CMS: Sanity.io
- Deployment: Vercel

---


## 📂 Project Structure
The project is organized as follows:
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

---


## 🖥️ Local Setup

**1. Clone the Repository**
git
cd your-repo-name

**2. Install Dependencies**
npm install

**3. Set Up Sanity CMS**
Navigate to the sanity/ directory.
Run the following command to initialize Sanity:
dev.to

sanity init

Follow the prompts to set up your Sanity project.


**4. Configure Environment Variables**
Create a .env.local file in the root directory and add the following variables:

NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
NEXT_PUBLIC_SANITY_DATASET=production

Replace your_project_id with your actual Sanity project ID.

**5. Run the Development Server**
npm run dev


---


## 🚀 Deployment
For deployment, Vercel is recommended due to its seamless integration with Next.js.

Push your code to a Git repository (GitHub, GitLab, or Bitbucket).
Connect your repository to Vercel.
Vercel will automatically detect the Next.js framework and deploy your application.

---

## 📄 License
This project is licensed under the MIT License.







