# Manguyá — Néctar Artesanal de Mango y Maracuyá

> **Prototipo Web e Interactividad de Marca** | Proyecto Académico de Administración y Marketing

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Estado](https://img.shields.io/badge/Estado-Finalizado-success?style=flat-square)]()

---

## Sobre el Proyecto

**Manguyá** es una propuesta comercial de néctar artesanal elaborada a base de Mango Kent y Maracuyá de huerto. Esta plataforma web funciona como canal digital interactivo de ventas y catálogo institucional para la marca.

### Presentaciones y Precios

| Presentación | Capacidad | Precio Unitario |
| :--- | :--- | :--- |
| **Botella Personal** | 330 ml | S/ 3.50 |
| **Botella Familiar** | 1 Litro | S/ 9.00 |

---

## Arquitectura y Funcionalidades

* **Mezclador de Sabor:** Simulación interactiva que permite al usuario ajustar la proporción de fruta y visualizar notas de cata dinámicas.
* **Geolocalización:** Integración con **Leaflet.js** para la selección del punto de entrega por GPS.
* **Procesamiento de Pedido:** Carrito de compras integrado con generación automática de comprobante en formato **PDF** (`jsPDF`).
* **Integración WhatsApp:** Redirección codificada directa al canal oficial de ventas (+51 918591764).

---

## Estructura del Repositorio

```text
Manguyá-SAC/
├── assets/
│   └── img/             # Recursos gráficos (logos, productos y fotos)
├── index.html           # Estructura principal, estilos y lógica JS
└── README.md            # Documentación del proyecto
