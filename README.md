## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### CREAR PROYECTO

1. Crear carpeta de proyecto.
2. npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm
3. cd nextjs-dashboard
4. Correr servidor: 
    - pnpm i    (instalar packages)
    - pnpm dev   (inicia servidor)   

### CARPETAS

# DATA
1.  /app/lib/placeholder-data  -------   Datos a añadir (tb por json) (users, customers, pelis...)
2. /app/lib/definitions.ts  --------- Modelos de las tablas (tabla users, tabla pelis....)

# CSS styles

1. /app//ui/global.css ------ Reglas de los css. Importamos componentes aqui.
2. /app/layout.tsx   ------ Estilos globales de la app. Importa el global.css
3. /app/page.tsx    ------- Tailwind clases

# Github push
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <URL_DEL_REPOSITORIO>
git push -u origin main