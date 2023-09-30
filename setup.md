Doc: https://jsmastery.notion.site/Setup-ESLint-Prettier-in-VS-Code-56e50002b82b45b88e36265c5eafbb24

PS D:\Learning\nextjs13> npx create-next-app@latest
Need to install the following packages:
create-next-app@13.5.3
Ok to proceed? (y) y
√ What is your project named? ... my-app
√ Would you like to use TypeScript? ... No / Yes
√ Would you like to use ESLint? ... No / Yes
√ Would you like to use Tailwind CSS? ... No / Yes
√ Would you like to use `src/` directory? ... No / Yes
√ Would you like to use App Router? (recommended) ... No / Yes
√ Would you like to customize the default import alias? ... No / Yes
Creating a new Next.js app in D:\Learning\nextjs13\my-app.

npm i eslint-config-standard
npm i eslint-plugin-tailwindcss
npm i eslint-config-prettier

{
  "extends": ["next/core-web-vitals","standard","plugin:tailwindcss/recommended","prettier"]
}