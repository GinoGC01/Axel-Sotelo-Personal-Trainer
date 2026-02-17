# ⚡ Axel Sotelo Fitness | High-Performance Landing Page

Landing page de alto rendimiento desarrollada para el ecosistema digital de Axel Sotelo.
El proyecto fue migrado desde una arquitectura SPA tradicional (React) hacia un enfoque de Generación Estática (SSG) con Astro, priorizando velocidad de carga, SEO técnico y conversión directa.

---

## 🛠 Tech Stack

| Tecnología          | Propósito                                                                   |
| ------------------- | --------------------------------------------------------------------------- |
| **Astro**           | Framework principal basado en Islands Architecture para máximo rendimiento. |
| **Tailwind CSS v4** | Sistema de estilizado utilitario con estética brutalista.                   |
| **TypeScript**      | Tipado estricto para mayor robustez y mantenibilidad.                       |
| **Vanilla JS**      | Interactividad ligera (Navbar, menús, modales) sin overhead.                |
| **Lucide Icons**    | Iconografía técnica optimizada mediante SVG inline.                         |

---

## 🚀 Características Principales

### Zero JS by Default

La mayoría de los componentes se renderizan en build time, eliminando hidratación innecesaria y reduciendo drásticamente el tiempo de carga.

### Brutalist Design System

Estética agresiva y de alto impacto basada en:

* Tipografías display pesadas
* Contrastes fuertes
* Bordes marcados
* Texturas de ruido (Noise Overlay)
* Layouts centrados en conversión

### Mobile-First & Animated

* Navbar con animaciones escalonadas (staggered)
* Transiciones fluidas en CSS puro
* Experiencia optimizada para interacción táctil

### WhatsApp Funnel

Estrategia de conversión directa orientada a cierre de ventas mediante mensajería instantánea, reduciendo fricción en el proceso de contacto.

### Layout Adaptativo

Uso de unidades dinámicas (`dvh`, `vw`) para asegurar que el Hero y los elementos visuales mantengan proporciones correctas en cualquier pantalla.

---

## 📁 Estructura del Proyecto

```
/
├── public/              # Assets estáticos (imágenes, favicons, media)
├── src/
│   ├── components/      # Componentes reutilizables (.astro)
│   ├── layouts/         # Plantilla base (Layout.astro)
│   ├── pages/           # Rutas del sitio (index, términos, privacidad)
│   └── styles/          # Core CSS con Tailwind v4 (@import)
├── astro.config.mjs     # Configuración del motor Astro
└── package.json         # Dependencias y scripts
```

---

## ⚙️ Instalación y Desarrollo

### 1) Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/axel-sotelo-fitness.git
```

### 2) Instalar dependencias

```bash
npm install
```

### 3) Iniciar entorno de desarrollo

```bash
npm run dev
```

### 4) Build de producción

```bash
npm run build
```

---

## 🎨 Guía de Estilo — Brutalism Core

### Colores

* **Primary:** `#FF6B00` (Naranja intenso)
* **Background:** `#0A0A0A` (Negro profundo)
* **Surface:** `#121212` (Gris técnico)

### Tipografía

* **Display:** Oswald (Bold / Italic)
  Uso: títulos, hero, impacto visual.

* **Body:** Roboto
  Uso: textos largos y lectura continua.

* **Mono:** Roboto Mono
  Uso: detalles técnicos, microcopy y meta-info.

---

## 🧠 Filosofía de Producto

La landing está diseñada bajo principios de conversión directa:

* Menos distracción visual
* Jerarquía agresiva
* CTA dominantes
* Narrativa de disciplina y transformación
* Identidad visual masculina y de alto rendimiento

---

## ⚖️ Legal y Privacidad

El proyecto incluye páginas dedicadas a:

* Términos y Condiciones
  Enfocados en responsabilidad del entrenamiento físico y uso del servicio.

* Política de Privacidad
  Cumplimiento RGPD con énfasis en protección de datos personales y métricas de contacto.

---

## 📈 Objetivo del Proyecto

* Maximizar velocidad de carga
* Mejorar posicionamiento SEO técnico
* Optimizar conversión desde tráfico social
* Centralizar contacto vía mensajería directa
* Consolidar marca personal con identidad visual fuerte

---

## ✍️ Autor

Desarrollado como parte del ecosistema digital de alto rendimiento orientado a posicionamiento, conversión y escalabilidad.

---

> **"La fuerza no se negocia, se construye."**
