# Portafolio Starter Kit

Este portfolio esta creado con Next.js y una libreria llamada Nextra. Te permite escribir Markdown y enfocarte en el contenido de tu portafolio. Este kit de inicio incluye:

- Configurado automáticamente para manejar Markdown/MDX
- Genera un feed RSS basado en tus publicaciones.
- Un hermoso tema incluido.
- Clasifique fácilmente publicaciones con etiquetas
- Carga de fuentes web rápida y optimizada

https://demo.vercel.blog

# Configuracion

1. Actualice su nombre en theme.config.js o cambie el pie de página.
2. Actualice su nombre y la URL del sitio para la fuente RSS en scripts/gen-rss.js.
3. Actualice las metaetiquetas (meta-tags) en pages/_document.tsx.
4. Actualice las publicaciones dentro de pages/posts/*.md con su propio contenido.
5. Hazle deploy al tuyo propio
6. Hazle deploy al ejemplo usando [Vercel](https://vercel.com/?utm_source=github&utm_medium=readme&utm_campaign=next-example) o obtenga una vista previa en vivo con [StackBlitz](https://stackblitz.com/github/vercel/next.js/tree/canary/examples/blog)

# Deploy con Vercel
[![Deploy con Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/next.js/tree/canary/examples/blog&project-name=portfolio&repository-name=portfolio)

# Como usar
Ejecuta ```create-next-app``` con [npm](https://docs.npmjs.com/cli/init), [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/), o [pnpm](https://pnpm.io) para ver el ejemplo:

```npx create-next-app --example blog my-blog```
# o
```yarn create next-app --example blog my-blog```
# o
```pnpm create next-app --example blog my-blog```

Hazle Deploy a la nube con Vercel ([Documentacion](https://nextjs.org/docs/pages/building-your-application/deploying)).
