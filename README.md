### Store Project 1
In this project, we are using Next.js version 15.2, TailwindCSS, TypeScript, TurboPack and PostgreSQL.
We are going to create an online store for selling IT products.

### Summary
- We started the project with mobile first, standard second.
- We are using convetional-commits.
- We are using Prisma for ORM, faciliting development this backend.
- We are using SupaBase for data.
- We are using chadcn ui.

### Prisma
- npx prisma migrate dev --name init


### Chadcn UI
- npx shadcn@latest init
- npx shadcn@latest add button (example)


### GCP
- create a api-key IdClientOAuth
- For DEV
- Insert JavaScript autorized - http://localhost:3000
- Insert URI redirect autorized - http://localhost:3000/api/auth/callback/google

### Next Auth
- https://authjs.dev/getting-started/installation
- Install next-auth
- Generate auth secret
- Includes Providers and Adapter