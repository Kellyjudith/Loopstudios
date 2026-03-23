# 🏝️ Proyecto: Loopstudios Landing Page

Este proyecto consiste en el desarrollo de la **landing page de Loopstudios** utilizando **Astro** y **Tailwind CSS**.  
El objetivo es aplicar los conocimientos sobre **componentes de Astro**, **maquetación**, **estilos responsivos** y **utilidades CSS** para construir un diseño limpio, moderno y adaptable a diferentes dispositivos.

---

## 📖 Descripción general

### 🧩 Vista previa del proyecto
Agrega aquí una **captura de pantalla** del resultado final de tu landing page.  

![Vista previa del proyecto](./screenshot.png)

---

### 🔗 Enlaces del proyecto

- **Repositorio en GitHub:** [Agrega aquí la URL de tu repositorio](https://github.com/)
- **Sitio desplegado (opcional):** [Agrega aquí la URL del proyecto desplegado, si usaste Vercel o Netlify](https://)

---

## 🧠 Proceso de desarrollo

### 🛠️ Tecnologías utilizadas
Lista las herramientas y tecnologías que utilizaste en el proyecto. Por ejemplo:

- [Astro](https://astro.build)
- [Tailwind CSS](https://tailwindcss.com/)
- HTML5 semántico
- Diseño responsivo (Mobile-first)
- Componentes de Astro reutilizables
- Interacciones con JavaScript (opcional para el toggle del menú móvil)

---

### 💡 Lo que aprendí
En esta sección describe brevemente **qué aprendiste o reforzaste** al desarrollar este proyecto.  
Puedes incluir fragmentos de código o mencionar conceptos nuevos que aplicaste.

Durante este proyecto reforcé el uso de componentes en Astro para dividir la página en secciones reutilizables. Aprendí a aplicar diseño responsivo con Tailwind CSS usando breakpoints como `md:` y `lg:`, y a manejar imágenes responsivas con la etiqueta `<picture>` para cargar versiones distintas según el dispositivo.
```astro
<!-- Ejemplo de imagen responsiva con picture -->
<picture>
  <source media="(min-width: 768px)" srcset="/images/desktop/image-hero.jpg" />
  <img src="/images/mobile/image-hero.jpg" alt="Hero" class="w-full h-full object-cover" />
</picture>
```
```js
// Toggle del menú móvil
const btn = document.getElementById('menu-btn');
const menu = document.getElementById('mobile-menu');

btn?.addEventListener('click', () => {
  menu?.classList.toggle('hidden');
  menu?.classList.toggle('flex');
});
```

---

### 🚀 Áreas de mejora

- Mejorar las animaciones de transición al abrir el menú móvil.
- Implementar transiciones más suaves entre secciones.
- Explorar variables de Tailwind personalizadas para el sistema de colores.
- Agregar más interactividad a las tarjetas de creaciones.

---
### 📚 Recursos útiles

Incluye los enlaces, documentación o tutoriales que te ayudaron a completar este proyecto.

- [Documentación de Astro](https://docs.astro.build)  
- [Guía oficial de Tailwind CSS](https://tailwindcss.com/docs)  
- [MDN Web Docs - HTML y CSS](https://developer.mozilla.org/es/)  
- [Guía de diseño responsivo](https://web.dev/responsive-web-design-basics/)  

---

### 👩‍💻 Autor

- **Nombre completo:** Kelly Judith Salmeron Villalba
- **Carrera:** Ingenieria en tecnologias de la informacion y comunicaciones
- **Grupo:** 11 am
- **Correo institucional:** 23151196@aguascalientes.tecnm.mx  

---

### ✨ Reflexión final

Este proyecto fue un reto muy completo porque implicó trabajar con un framework nuevo como Astro, organizar componentes de forma estructurada y replicar un diseño real con atención al detalle. 
Lo que más disfruté fue ver cómo cada componente encajaba para formar la página completa. Aplicaré estos conocimientos en futuros proyectos para construir interfaces más organizadas y mantenibles.

