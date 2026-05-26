# Auditoría de Seguridad: Repositorio de Evidencias

Este repositorio constituye un registro técnico y documentado de los hallazgos, análisis de vulnerabilidades y exposiciones de infraestructura web identificados en el marco de ejercicios de ciberseguridad ética y auditorías de sistemas.

---

## 🏛️ Propósito
El objetivo de este proyecto es centralizar la documentación de incidentes y debilidades de seguridad bajo un estándar profesional. Cada reporte contenido en este repositorio incluye el análisis de impacto, la evaluación de criticidad y las recomendaciones de mitigación correspondientes para fortalecer la postura de seguridad de los activos evaluados.

## ⚙️ Stack Tecnológico
El despliegue y la gestión de este sitio se fundamentan en las siguientes tecnologías:

* **Arquitectura:** Jekyll 4.3 (Motor de generación estática).
* **Diseño e Interfaz:** Implementación personalizada con Tailwind CSS para una experiencia responsiva y eficiente.
* **Infraestructura de Despliegue:** CI/CD automatizado mediante GitHub Actions para garantizar una compilación limpia y despliegue continuo en GitHub Pages.
* **Gestión de Dependencias:** Entorno controlado mediante `Bundler` para asegurar la reproducibilidad del entorno.

## 📂 Organización del Repositorio
* `_layouts/`: Definición de estructuras y plantillas para el despliegue de reportes.
* `assets/`: Recursos gráficos (imágenes optimizadas en formato `.webp`) y hojas de estilo con Tailwind.
* `reportes/`: Documentación técnica de hallazgos.
* `.github/workflows/`: Automatización de procesos de integración y despliegue (CI/CD).

## 🚀 Despliegue Local
Para fines de auditoría y revisión, el sitio puede ser compilado localmente siguiendo estos pasos:

1. **Clonar el repositorio:**
   ```bash
     git clone https://github.com/hideonn1/hideonn1.github.io.git
     cd hideonn1.github.io```

2. **Instalar dependencias:**
   ```bash
      bundle install```

4. **Ejecutar servidor de desarrollo:**
   ```bash
      bundle exec jekyll serve```

## ⚖️ Declaración de Ética y Responsabilidad
Toda la información contenida en este repositorio es estrictamente para fines educativos y profesionales. El autor ha realizado estas auditorías respetando los marcos de legalidad y ética profesional. Se prohíbe el uso de esta información para fines malintencionados o no autorizados. El autor declina toda responsabilidad sobre el uso indebido de los datos aquí expuestos.

---

## 👤 Contacto y Referencias
* **Autor:** Pedro Lorca (hideonn1)
* **GitHub:** @hideonn1
* **Correo electrónico:** p.lorca20@proton.me
