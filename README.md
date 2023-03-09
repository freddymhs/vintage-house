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

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

# consideraciones para mi mismo

Puedes utilizar useMemo y useCallback para memoizar valores y funciones que no cambian con frecuencia.

puedes usar Suspense para carga diferida en react

revisar usando react developers tools

# herramientas

- nextjs
  sql
- tailwind css
  styled component
  scss
- mercado pago o stripe
- facebook api

# pilares importantes (sistema simple integracion con fb page -> que permite vista y compra usandolo como base de datos)

- Integración con Facebook
  Gestión de productos

- Módulo de pagos
  Carrito de compras y checkout

- graficos de inventarios simples

- Seguridad

- Servicio al cliente / contactos rapidos / bots? /ia?

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

# TODO (plataforma apoyo)

## TODO para proyecto Next.js

### Configuración inicial (2sem)

- [ ] Crear el proyecto en Next.js
- [ ] Configurar la base de datos SQL
- [ ] Instalar y configurar Tailwind CSS
- [ ] Instalar y configurar Styled Components
- [ ] Configurar Mercado Pago o Stripe para pagos en línea
- [ ] Configurar la API de Facebook

### Integración con Facebook (1sem)

- [ ] Crear una página de Facebook para el negocio
- [ ] Configurar la integración con Facebook en el proyecto
- [ ] Obtener los productos de la página de Facebook
- [ ] Crear una vista de productos en el sitio web
- [ ] Permitir la compra de productos directamente desde el sitio web

### Módulo de pagos (3sem)

- [ ] Crear un carrito de compras
- [ ] Integrar el módulo de pagos de Mercado Pago o Stripe
- [ ] Configurar el checkout
- [ ] Probar la funcionalidad del módulo de pagos

### Gráficos de inventarios simples (2sem)

- [ ] Obtener información sobre el inventario de la página de Facebook
- [ ] Mostrar gráficos simples del inventario en el sitio web
- [ ] Actualizar los gráficos de inventario en tiempo real

### Seguridad (3sem)

- [ ] Implementar medidas de seguridad para proteger los datos de los clientes
- [ ] Configurar certificado SSL para encriptar la comunicación entre el sitio web y los clientes

### Servicio al cliente / Contactos rápidos / Bots / IA (5sem)

- [ ] Configurar un chat en vivo para brindar soporte a los clientes
- [ ] Configurar un formulario de contacto para recibir solicitudes de los clientes
- [ ] Implementar un chatbot para responder preguntas frecuentes
- [ ] Implementar una IA para personalizar la experiencia de compra
