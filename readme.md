<div align="center">

<a href="https://nextjs.org/" target="_blank" rel="noreferrer">
  <img src="./language/next1.webp" alt="Next.js" width="120" />
</a>
<img src="./language/fast.png" alt="Fast Badge" width="120" />

# **Next.js - Comprehensive Guide**

Official Next.js Website:  
<a href="https://nextjs.org/" target="_blank" rel="noreferrer">nextjs.org</a>

</div>

---

## **Introduction**

Welcome to the **Next.js** project! This repository provides an in-depth understanding of **Next.js** and its key features. **Next.js** is a **React-based framework** that enables the development of high-performance, SEO-friendly, and scalable applications. It supports **Server Components**, **SSR**, **SSG**, and **CSR**, making it a strong choice for modern web apps.

In this repository, you will learn and explore:

- **SSR**, **SSG**, **CSR**, and **React Server Components (RSC)**
- **File-based Routing** (Pages Router and App Router)
- **Image Optimization** using `next/image`
- **Dynamic Routing** and **API Routes / Route Handlers**
- **Middleware** for auth, redirects, and edge logic
- **SEO** using `metadata` (App Router) and `Head` (Pages Router)
- **Fonts** using `next/font`
- **Deployment** on Vercel and other platforms
- **Performance** optimizations and Core Web Vitals
- **Error Handling** with `error.tsx`, `not-found.tsx`, and custom pages
- **TypeScript** setup and best practices

---

## **Key Features of Next.js**

### **1. Server-Side Rendering (SSR)**
Next.js supports **SSR**, where pages are rendered on the server per request. This improves **SEO** and **first load performance**.

- **When to use SSR**: For highly dynamic pages that change on each request.

---

### **2. Static Site Generation (SSG)**
With **SSG**, pages are pre-rendered at build time and served as static HTML.

- **When to use SSG**: For content that rarely changes (docs, blogs, marketing pages).

---

### **3. Client-Side Rendering (CSR)**
Next.js also supports **CSR**, where data loads after the page renders.

- **When to use CSR**: For interactive dashboards, filters, and user-driven screens.

---

### **4. React Server Components (RSC)**
With the **App Router**, components can run on the server by default, reducing client JS and improving performance.

- **Why it matters**: Faster pages, smaller bundles, cleaner data fetching.

---

### **5. Image Optimization**
Next.js includes `next/image` which optimizes images automatically.

- **Why use it**: Better performance via responsive sizing, modern formats, and lazy loading.

---

### **6. Dynamic Routing**
Create routes like `/posts/[id]` to render pages based on params.

- **When to use**: Products, blogs, profiles, admin panels.

---

### **7. API Routes / Route Handlers**
- **Pages Router**: `pages/api/*`
- **App Router**: `app/api/*/route.ts`

- **Why use it**: Lightweight backend endpoints, auth, webhooks, forms.

---

### **8. Middleware**
Middleware runs before a request completes and is great for:

- Auth checks
- Redirects
- Geo-based routing
- Logging / headers

---

### **9. SEO Optimization**
- **App Router**: `export const metadata = {}`
- **Pages Router**: `next/head`

- **Why**: Better indexing, rich previews, and clean social tags.

---

### **10. Fonts (Optimized)**
Use `next/font` for optimized font loading.

- **Why**: Faster loads and fewer layout shifts.

---

### **11. Performance Optimization**
Built-in:

- Code splitting
- Lazy loading
- Caching strategies
- Streaming (App Router)
- Prefetching

---

### **12. TypeScript Integration**
Next.js supports TypeScript out of the box.

- **Why**: Safer refactors, cleaner contracts, fewer runtime bugs.

---

## **How to Use This Repository**

### **1. Install Dependencies**
```bash
npm install
# or
yarn
# or
pnpm install
