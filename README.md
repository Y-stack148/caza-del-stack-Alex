# La Caza del Stack: Vercel Inc.
## 1. Entorno de Edición (IDE)
El equipo de ingeniería de Vercel estandariza su desarrollo en entornos optimizados para la web moderna:
* **Editor:** **Visual Studio Code (VS Code)**.
* **Extensiones Recomendadas:**
    * **Prettier**: Para el formateo automático de código.
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
* **Herramientas Modernas Detectadas:**
    * **Next.js**: Su framework esta basado en React.
    * **Tailwind CSS**: Para el diseño visual rápido y eficiente.
    * **Bun**: Han comenzado a integrar este runtime moderno por ser más rápido que Node.js en ciertas tareas de servidor.
    * **Turbopack**: Su motor de empaquetado escrito en **Rust**.

**Manual de Investigación**
* **Ofertas de Empleo**
    Visité el portal y analicé la vacante de Ejecutivo de cuentas, Base de Instalaciones Comerciales
    <img width="1648" height="864" alt="image" src="https://github.com/user-attachments/assets/bf34ff3d-4ace-43ca-8468-51996d38dd63" />

* **StackShare**
   <img width="1023" height="461" alt="image" src="https://github.com/user-attachments/assets/b493383a-df02-4551-b127-b645d93dd3f3" />

* **Wappalyzer: Inspección en Tiempo Real**
* Instalé la extensión y navegué por vercel.com.
    <img width="632" height="620" alt="image" src="https://github.com/user-attachments/assets/db32e619-0fe0-409a-9fc5-87cccf6941cd" />
    <img width="611" height="538" alt="image" src="https://github.com/user-attachments/assets/0afe4943-89a0-4eb0-9157-dd909c2fa390" />

* **Engineering Blogs**
Busqué en Google, Vercel Engineering Blog.

Implementaron React Server Components y Partial Prerendering (PPR) para eliminar los "spinners" de carga. Lograron que la barra de             búsqueda    mantenga el foco y el estado al navegar entre páginas mediante una sincronización inteligente con la URL, reduciendo el            tiempo de respuesta    en móvil en un 70%.
  
* **Búsqueda Avanzada en GitHub**
Revisé el repositorio oficial de Vercel.

Al abrir el package.json, vi que gestionan su monorepo con pnpm y Turbo para maximizar la velocidad. Además, mantienen la calidad del código   mediante una configuración estricta de ESLint y TypeScript, prohibiendo incluso el uso de funciones obsoletas como .substr() a través de       reglas personalizadas.

**¿Qué es Biome y para qué sirve en el desarrollo web?**
