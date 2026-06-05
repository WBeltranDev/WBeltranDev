<div align="center">
  <h1>WILEVER BELTRAN TUAY</h1>
  <p><strong>Ingeniero de Sistemas | Desarrollador Full-Stack & Mobile</strong></p>
</div>

---

### Sobre Mí

Desarrollador enfocado en la creación de soluciones digitales eficientes y escalables. Actualmente continúo mi formación profesional como estudiante de Ingeniería de Sistemas en la Universidad Internacional del Trópico Americano (Unitrópico).

He liderado y colaborado en diversos proyectos universitarios y soluciones autónomas, aplicando buenas prácticas, arquitectura limpia y metodologías ágiles para llevar ideas del papel a código real y funcional.

Mi trayectoria académica previa respalda mis capacidades técnicas en el ciclo de vida del desarrollo de software:
* **Tecnólogo en Diseño y Desarrollo de Software**
* **Técnico Profesional en Desarrollo para Dispositivos Móviles**

---

### Dashboard Tecnológico Interactivo

Pasa el cursor o presiona cualquiera de los logos y del pin de ubicación para ver las animaciones en tiempo real.

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 940 390" width="100%">
  <defs>
    <!-- Estilos CSS con las animaciones de escalado y pulsación -->
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Inter:wght@600;800&amp;display=swap');
      text { font-family: 'Inter', sans-serif; fill: #ffffff; }
      .category-title { font-size: 12px; fill: #8b949e; letter-spacing: 1.5px; font-weight: 800; }
      
      /* Animación interactiva: Crecer al pasar el cursor */
      .interactive-badge {
        transition: transform 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275), filter 0.3s ease;
        transform-box: fill-box;
        transform-origin: center;
        cursor: pointer;
      }
      .interactive-badge:hover {
        transform: scale(1.15);
        filter: drop-shadow(0px 5px 10px rgba(62, 207, 142, 0.4));
      }

      /* Animación del Pin de ubicación */
      .pulse-circle {
        animation: pulseRadar 2.5s infinite ease-out;
        transform-origin: 130px 175px;
      }
      .pin-center {
        animation: floatPin 3s infinite ease-in-out;
        transform-origin: 130px 175px;
      }
      @keyframes pulseRadar {
        0% { r: 15px; opacity: 0.8; stroke-width: 2; }
        100% { r: 65px; opacity: 0; stroke-width: 0.5; }
      }
      @keyframes floatPin {
        0% { transform: translateY(0px); }
        50% { transform: translateY(-8px); }
        100% { transform: translateY(0px); }
      }
    </style>
  </defs>

  <!-- Fondo del Panel -->
  <rect width="940" height="390" rx="12" fill="#0d1117" stroke="#30363d" stroke-width="1"/>

  <!-- ================= SECCIÓN IZQUIERDA: EL PIN DE UBICACIÓN ANIMADO ================= -->
  <!-- Ondas de radar del Pin -->
  <circle cx="130" cy="175" r="35" fill="none" stroke="#3ECF8E" class="pulse-circle" />
  <circle cx="130" cy="175" r="15" fill="#3ECF8E" opacity="0.2"/>
  
  <!-- Estructura Visual del Pin Circular Desenrollado -->
  <g class="pin-center" cursor="pointer">
    <circle cx="130" cy="175" r="22" fill="#161b22" stroke="#3ECF8E" stroke-width="2.5"/>
    <!-- Icono simplificado de localización interna del Pin -->
    <path d="M130 163 C123 163 119 168 119 174 C119 181 130 189 130 189 C130 189 141 181 141 174 C141 168 137 163 130 163 Z" fill="#3ECF8E"/>
    <circle cx="130" cy="174" r="3" fill="#161b22"/>
  </g>
  <text x="130" y="230" font-size="14" font-weight="800" text-anchor="middle" fill="#3ECF8E">UNITRÓPICO</text>
  <text x="130" y="250" font-size="11" fill="#8b949e" text-anchor="middle">Sistemas &amp; Desarrollo</text>

  <!-- Línea Divisoria Vertical -->
  <line x1="260" y1="30" x2="260" y2="360" stroke="#30363d" stroke-dasharray="4 4"/>

  <!-- ================= SECCIÓN DERECHA: SKILLS INTERACTIVOS ================= -->
  
  <!-- LENGUAJES -->
  <text x="300" y="45" class="category-title">LENGUAJES DE PROGRAMACIÓN</text>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" x="300" y="60" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" x="420" y="60" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&amp;logo=php&amp;logoColor=white" x="540" y="60" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&amp;logo=openjdk&amp;logoColor=white" x="660" y="60" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" x="780" y="60" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&amp;logo=dart&amp;logoColor=white" x="300" y="100" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&amp;logo=kotlin&amp;logoColor=white" x="420" y="100" width="110" height="30"/></g>

  <!-- BACKEND -->
  <text x="300" y="165" class="category-title">FRAMEWORKS BACKEND</text>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&amp;logo=laravel&amp;logoColor=white" x="300" y="180" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&amp;logo=spring-boot&amp;logoColor=white" x="420" y="180" width="110" height="30"/></g>

  <!-- FRONTEND & MOBILE -->
  <text x="300" y="245" class="category-title">FRAMEWORKS FRONTEND &amp; MOBILE</text>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&amp;logo=vuedotjs&amp;logoColor=white" x="300" y="260" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/React-20232A?style=for-the-badge&amp;logo=react&amp;logoColor=61DAFB" x="420" y="260" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&amp;logo=angular&amp;logoColor=white" x="540" y="260" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&amp;logo=flutter&amp;logoColor=white" x="660" y="260" width="110" height="30"/></g>

  <!-- BASES DE DATOS -->
  <text x="300" y="325" class="category-title">BASES DE DATOS &amp; BAAA</text>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" x="300" y="340" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&amp;logo=postgresql&amp;logoColor=white" x="420" y="340" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&amp;logo=firebase&amp;logoColor=black" x="540" y="340" width="110" height="30"/></g>
  <g class="interactive-badge"><image href="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&amp;logo=supabase&amp;logoColor=white" x="660" y="340" width="110" height="30"/></g>
</svg>

---

### Proyectos y Colaboraciones
* Soluciones de software desarrolladas bajo requerimientos académicos y entornos de simulación real en la universidad.
* Arquitecturas escalables orientadas a microservicios y desarrollo móvil nativo/híbrido.
