# Keprecios - Aplicación Web de Comparación de Precios (Proyecto Final de Carrera)

> Este repositorio contiene el código fuente y la documentación completa del proyecto final para la carrera de Ingeniería en Sistemas de Información (UTN). "Keprecios" es una aplicación web full-stack diseñada para ayudar a los consumidores a encontrar las mejores ofertas y combatir la inflación a través de la colaboración comunitaria.

## 🚀 Resumen del Proyecto

En un contexto de alta inflación y dispersión de precios, "Keprecios" nace como una solución colaborativa que permite a los usuarios registrar, comparar y encontrar las mejores ofertas de productos en comercios locales. El proyecto abarcó el ciclo de vida completo de desarrollo de software, desde la concepción de la idea y el análisis de requisitos hasta el despliegue de un Producto Mínimo Viable (MVP).

La aplicación fue desarrollada por el equipo "Los Supervivientes" utilizando el **framework ágil Scrum** para gestionar el trabajo en sprints, asegurar entregas de valor continuas y mantener una alta colaboración.

## ✨ Características Principales (MVP)

-   **Gestión de Usuarios:** Sistema de registro, inicio de sesión y perfiles de usuario.
-   **Plataforma Colaborativa:** Los usuarios pueden registrar comercios, productos y ofertas.
-   **Sistema de Gamificación:** Se implementó un sistema de puntos de reputación y vouchers para incentivar la participación y asegurar la confiabilidad de los datos.
-   **Búsqueda y Filtros Avanzados:** Un buscador potente que permite a los usuarios filtrar ofertas por producto, marca, categoría, comercio y rango de precios.
-   **Listas de Compras Inteligentes:** Funcionalidad para crear listas de compras y comparar automáticamente en qué comercio se consigue el precio total más bajo.
-   **Geolocalización:** Integración con APIs de mapas (OpenStreetMap, Google Maps) para mostrar comercios cercanos a la ubicación del usuario.

- **Repositorio con el código del proyecto:** https://github.com/maxibellini/keprecios

## 🛠️ Arquitectura y Stack Tecnológico

La aplicación se construyó siguiendo el patrón arquitectónico **Modelo-Vista-Controlador (MVC)** para una clara separación de responsabilidades.

-   **Backend:** **PHP** sobre el framework **Symfony 5.2**. Se utilizó Doctrine como ORM para la persistencia de datos.
-   **Base de Datos:** **MariaDB** (un fork de MySQL), gestionada a través de phpMyAdmin.
-   **Frontend:** Motor de plantillas **Twig** para el renderizado de vistas, junto con **HTML5, CSS3 y JavaScript** para una experiencia de usuario responsive ("mobile-first").
-   **Control de Versiones:** **Git** y **GitHub** para la gestión colaborativa del código fuente.
-   **Gestión de Proyecto:** **Scrum** como metodología ágil, con **Trello** para la gestión del backlog y el seguimiento de sprints.
-   **Entorno de Desarrollo:** XAMPP (Apache, MariaDB, PHP).
-   **Despliegue:** La aplicación fue desplegada en un entorno PaaS en **Hostinger**.

## 📄 Documentación del Proyecto

Este proyecto fue documentado exhaustivamente en cada una de sus fases. Los documentos clave se encuentran en la carpeta de `/Documentacion` (o similar):

-   **📄 Especificación de Requisitos de Software (ERS):** Define el alcance, los requisitos funcionales y no funcionales.
-   **📐 Arquitectura de Software:** Describe la arquitectura de alto nivel, los diagramas de capas, de contexto y el stack tecnológico.
-   **🗓️ Planificación del Proyecto:** Detalla la planificación de las 5 releases y los 13 sprints, incluyendo historias de usuario y burn-down charts.
-   **🧪 Casos de Prueba:** Documentación de los casos de prueba de caja negra para cada funcionalidad.
-   **📖 Manual de Usuario y de Instalación:** Guías detalladas para usuarios y administradores.

## 👥 Equipo de Desarrollo ("Los Supervivientes")

Este proyecto fue un esfuerzo colaborativo de:

-   **Gonzalo Facundo Benitez Peressi** (*Analista de Negocios, Scrum Master*)
-   Santiago Aguilar (*Desarrollador Backend, DevOps, Tester*)
-   Maximiliano Alain Bellini (*Desarrollador Full-Stack*)
-   Leticia Monzón (*Analista, Tester, Documentación*)
-   Luis A. Sánchez Negrette (*Desarrollador Backend, Documentación*)

---
*Universidad Tecnológica Nacional - Facultad Regional Resistencia | Proyecto Final | 2022*
