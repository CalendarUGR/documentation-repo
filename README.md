# TempusUGR - Documentación Oficial

Este repositorio contiene toda la documentación oficial del proyecto **TempusUGR**, incluyendo la memoria completa del Trabajo de Fin de Grado (TFG) que detalla el análisis, diseño, implementación y despliegue del sistema.

El objetivo de este repositorio es centralizar el conocimiento del proyecto, facilitando su consulta, mantenimiento y futuras ampliaciones.

---

## 📄 Contenido Principal

El documento principal es la memoria del TFG, escrita en **LaTeX**. Abarca en profundidad las siguientes áreas:

* **Introducción y Contexto:** Motivación del proyecto y descripción del problema en la Universidad de Granada.
* **Estado del Arte:** Análisis de soluciones existentes para la gestión de horarios académicos.
* **Especificación de Requisitos:** Definición de Personas, Escenarios, Historias de Usuario y requisitos funcionales y no funcionales.
* **Planificación y Metodología:** Descripción de la metodología Scrum, cronograma y presupuesto.
* **Diseño del Sistema:** Detalles sobre la arquitectura de microservicios, las tecnologías seleccionadas y el diseño de la API y las bases de datos.
* **Implementación:** Resumen del trabajo realizado en cada uno de los sprints de desarrollo.
* **Despliegue y Pruebas:** Proceso de despliegue en un servidor de producción, contenerización con Docker y resultados de las pruebas de carga.
* **Conclusiones y Trabajos Futuros:** Resumen de los logros, dificultades encontradas y posibles mejoras.

---

## ⚙️ Tecnología y Automatización

* **Lenguaje:** El documento está escrito en **LaTeX**, un sistema de composición de textos de alta calidad tipográfica.
* **Automatización (CI/CD):** Se ha configurado un flujo de trabajo con **GitHub Actions** que compila automáticamente el código fuente `.tex` y genera el archivo `TFG.pdf` final con cada `push` a la rama principal. Esto asegura que el PDF disponible para descargar esté siempre actualizado con los últimos cambios.
* **Colaboración:** El proceso de revisión y corrección se gestionó a través de **Pull Requests**, facilitando la colaboración y el control de versiones del documento.

---

## 📥 Cómo Acceder al Documento

### **Opción 1: Descargar el PDF compilado**

Puedes descargar la última versión de la memoria directamente desde la sección de **Releases** de este repositorio o a través del siguiente enlace:

[➡️ **Descargar TFG.pdf (Última Versión)**](https://github.com/TempusUGR/documentation-repo/blob/main/TFG.pdf)
*(Nota: Reemplaza la URL si el PDF se encuentra en otra ubicación, como en las releases)*

### **Opción 2: Compilar desde el código fuente**

Si deseas compilar el documento tú mismo, necesitarás una distribución de LaTeX instalada en tu sistema (como TeX Live, MiKTeX o MacTeX).

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/TempusUGR/documentation-repo.git](https://github.com/TempusUGR/documentation-repo.git)
    cd documentation-repo
    ```

2.  **Compila el documento:**
    Utiliza tu compilador de LaTeX preferido. Un comando típico sería:
    ```bash
    pdflatex main.tex
    ```
    *(Nota: Puede que necesites ejecutar el comando varias veces para que las referencias cruzadas y la bibliografía se generen correctamente).*
