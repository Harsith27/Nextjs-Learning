This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.







## My notes

if i have hooks and usestate and all its client side rendered one 

in server side rendering you dont use hoooks of hooks are used it is automatically converted to client side rendering

enclose the folder with () to not make it a page as we do localhos.../dashboard



## Task

### 1.Usecase
### 1. Usecase

#### Converting React Pages to Next.js Routes
When migrating a React application to Next.js, you're transitioning from a single-page application (SPA) to a file-based routing system.

#### API Development in Next.js

**Folder Structure:**
```
src/
├── app/
│   ├── api/
│   │   └── routes.ts
│   └── pages/
└── ...
```

**Key Points:**
- All API routes are defined in `routes.ts`
- API logic is written directly in the route handler file
- Dynamic routes use bracket notation: `[id]` represents a dynamic parameter

**Dynamic Routing Example:**
```
api/
├── users/
│   ├── [id]/
│   │   └── routes.ts    // Handles /api/users/{id}
│   └── routes.ts        # Handles /api/users
```

#### Frontend-Backend Integration

**Architecture:**
- **Frontend:** Client-side components fetch data from API endpoints
- **Backend:** Server-side API routes handle business logic and database operations
- **Integration:** RESTful APIs connect both layers

**Debugging Tips:**
- Server-side components: check `console.log` outputs in **terminal**
- Client-side components: check `console.log` outputs in **browser console**

#### Additional Tools
- **Prisma Studio:** Visual database management tool for viewing and editing data

## Rough work - Non formatted
we have a page in react we convert it using nextjs using routes

how we write api in nextjs and how to integrate both
inside src folder we use api folder
all routes will be in routes.ts
we will write the api logic in that file

rest apis for next

[id] here the id can be any value for the routing part where [id] is a folder or directory

creating api and integration 
frontend backend and integration usecase - assessment

console.log outputs in terminal for server side component and in browsesr for client side component

prisma studio