
\# POS-Nelly-Buffet

A simple POS project for a restaurant.

Un sistema de Punto de Venta (POS) simple, offline y funcional, diseñado específicamente para un restaurante. El proyecto está contenido en un único archivo HTML, lo que lo hace extremadamente portátil y fácil de desplegar.

#Concepto Clave: Funcionamiento 100% Offline

La principal característica de este POS es su capacidad para operar de forma completamente offline. En lugar de depender de una base de datos en la nube o del almacenamiento volátil del navegador (caché), el sistema utiliza un archivo JSON local como su base de datos persistente.

El usuario selecciona este archivo al iniciar la aplicación, y toda la información (productos, ventas, reportes) se lee y se escribe directamente en él. Esto garantiza que los datos nunca se pierdan por un borrado de caché y que el control de la información permanezca siempre en manos del usuario.

#Características Principales

Gestión de Productos: Añadir, editar y eliminar productos con detalles como nombre, precio, categoría e imagen.

Interfaz de Venta Rápida: Una cuadrícula de productos visual e intuitiva para añadir artículos a la orden actual de forma ágil.

Proceso de Pago Completo: Cálculo de cambio y flujo de pago claro y sencillo.

Impresión de Recibos: Generación de recibos optimizados para impresoras térmicas de 58mm y 80mm.

Cuadre de Caja (Cierre de Día): Un panel completo para ver el resumen de ventas del día, los productos más vendidos y los retiros de efectivo.

Reportes de Ventas: Generación de reportes de ventas diarios y mensuales con la opción de exportar los datos a formato CSV.

Seguridad y Roles: Sistema de PIN de administrador para proteger acciones críticas como la edición/eliminación de ventas, el cambio de configuraciones y el cierre del día.

Optimizado para Pantallas Táctiles: Interfaz diseñada para su uso en pantallas táctiles, con scroll mejorado (touch-action), barras de scroll más anchas y teclados numéricos contextuales (inputmode).

#Entorno de Ejecución: Modo Kiosco

Este proyecto está diseñado para ser ejecutado en el navegador Google Chrome en Modo Kiosco. Esto permite que la aplicación se muestre a pantalla completa, sin barras de navegación ni menús, y habilita la impresión directa en la impresora térmica sin mostrar el diálogo de impresión del navegador.

Es crucial configurar un acceso directo para lanzar la aplicación con los parámetros correctos para un funcionamiento óptimo.

#Tecnologías Utilizadas

*   HTML5
    
*   CSS3 con Tailwind CSS para un diseño rápido y responsivo.
    
*   JavaScript (Vanilla JS) para toda la lógica de la aplicación.
    
*   Chart.js para la visualización de gráficas en los reportes.
    
*   Font Awesome para los iconos.
