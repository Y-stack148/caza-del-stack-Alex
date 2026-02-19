# La Caza del Stack: Vercel Inc.
## 1. Entorno de Edición (IDE)
El equipo de ingeniería de Vercel estandariza su desarrollo en entornos optimizados para la web moderna:
* **Editor:** **Visual Studio Code (VS Code)**.
* **Extensiones Recomendadas:** * **Prettier**: Para el formateo automático de código.
    * **ESLint**: Para asegurar que el código TypeScript no tenga errores lógicos.
    * **Tailwind CSS IntelliSense**: Para autocompletar clases de diseño.
    * **Turbo**: Herramienta interna para gestionar monorepos de alto rendimiento.

## 2. Ecosistema de Navegación
Realizan pruebas exhaustivas para garantizar que la web cargue en milisegundos:
* **Pruebas de Rendimiento:** Utilizan principalmente motores **Chromium (Google Chrome)** para medir las *Core Web Vitals*.
* **Renderizado:** Pruebas de compatibilidad en **Safari (WebKit)** y **Firefox** para asegurar que los componentes de React se vean igual en todos los dispositivos.

## 3. Gestión de Versiones
Vercel utiliza Git:
* **Sistema:** **Git**.
* **Plataforma de Alojamiento:** **GitHub**. 
* **Dato Clave:** Utilizan una función llamada **Preview Deployments**, donde cada rama de Git genera una URL única para revisar cambios antes de pasarlos a producción.

## 4. Diseño UI/UX
Antes de escribir una sola línea de código, el equipo de diseño define todo visualmente:
* **Herramienta Principal:** **Figma**.
* **Sistema de Diseño:** Han creado su propio lenguaje visual llamado **Geist**, el cual está totalmente prototipado en Figma para mantener una estética limpia, minimalista y profesional.

## 5. Lenguajes y Herramientas Base
El stack de Vercel es el desarrollo web actual:
* **Lenguajes:** **HTML5**, **CSS3** y, sobre todo, **TypeScript (TS)** (lo prefieren sobre JS por seguridad).
* **Herramientas Modernas Detectadas:** * **Next.js**: Su framework esta basado en React.
    * **Tailwind CSS**: Para el diseño visual rápido y eficiente.
    * **Bun**: Han comenzado a integrar este runtime moderno por ser más rápido que Node.js en ciertas tareas de servidor.
    * **Turbopack**: Su motor de empaquetado escrito en **Rust**.

Manual de Investigación
1. El "Truco" de las Ofertas de Empleo 💼
Qué hice: Visité el portal de  y analicé la vacante de Site Engineer.

El Tesoro: Confirmé que piden 5+ años en React, TypeScript y Tailwind CSS. Esto me dio el 90% de la ficha técnica.

2. StackShare: El "Chismógrafo" de la Tecnología 📊
Qué hice: Busqué a Vercel en .

El Tesoro: Descubrí que utilizan Next.js (obviamente), pero también herramientas de infraestructura como AWS y Google Cloud.

3. Wappalyzer: Inspección en Tiempo Real 🔍
Qué hice: Instalé la extensión y navegué por vercel.com.

El Tesoro: La extensión detectó inmediatamente React, Next.js y el uso de Google Analytics y Vercel Speed Insights.

4. "Engineering Blogs" 📖
Qué hice: Busqué en Google Vercel Engineering Blog.

El Tesoro: Leí sobre cómo han optimizado su motor de empaquetado usando Turbopack (escrito en Rust) para reemplazar a Webpack.

5. Búsqueda Avanzada en GitHub 📂
Qué hice: Revisé el repositorio oficial de  manejado por Vercel.

El Tesoro: Al abrir el package.json, vi las dependencias exactas: usan ESLint para calidad y TypeScript como lenguaje base.
