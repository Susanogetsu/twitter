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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


//creación proyecto
npx create-next-app@latest
//convertir el manejador de dependencias en pnpm
pnpm install
//configurar el linter de eslint
 npx eslint --init
 //agregar esta linea en parser options
 "project": "./tsconfig.json"
 //agregar estas reglas en rules
   "react/prop-types": "off",
        "react/react-in-jsx-scope": "off",
        "@typescript-eslint/no-floating-promises": "off",
        "@typescript-eslint/explicit-function-return-type": "off",
        "@typescript-eslint/no-missued-promises": "off"
//instalamos supabase
npm install @supabase/auth-helpers-nextjs @supabase/supabase-js -E
//instalamos next-ui
npm i @nextui-org/react framer-motion
import {nextui} from "@nextui-org/react";
//agregamos al content de tailwind
    "./node_modules/@nextui-org/theme/dist/**/*.{js,ts,jsx,tsx}",
  //creamos un provider para envolver la aplicación
  //crear archivo .npmrc
  public-hoist-pattern[]=*@nextui-org/*
  // commit github
  //iniciar git
  git init
  //crear o usar la rama main
  git branch -M main
  git add .
  git commit -m "no toaster"
  //conectar al repo de git
  git remote add origin https://github.com/Susanogetsu/Twitter.git
  git push -u origin main