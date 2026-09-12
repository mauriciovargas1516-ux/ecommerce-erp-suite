# Ecommerce ERP Suite (Python)

Suite centralizada de gestión y automatización diseñada para operar como un mini-ERP para tiendas basadas en WooCommerce. Este sistema integra 7 herramientas operativas para eliminar el error humano, optimizar la logística de inventarios y proteger la rentabilidad del negocio.

### ⚙️ Funcionalidades Clave
* **Sincronización Inteligente:** Creación y actualización masiva de productos (SKU, precios, stock) mediante la API de WooCommerce.
* **Procesamiento Multihilo (Turbo):** Extracción y clonación completa del catálogo web a entornos locales utilizando concurrencia para reducir tiempos de ejecución.
* **Motor de Reglas de Negocio:** Asignación automática de categorías y estructuración de inventario mediante análisis de texto y coincidencia de patrones (Materiales/Medidas).
* **Sanitización Segura:** Limpieza condicional de bases de datos locales e imágenes para evitar pérdidas accidentales de información.

### 💻 Stack Tecnológico
* **Lenguaje:** Python 3 (tkinter, concurrent.futures, hashlib, BeautifulSoup)
* **Integraciones:** WooCommerce REST API, WordPress Media API
* **Despliegue:** Sistema orquestado compatible con ejecución en servidores Linux (Google Cloud Platform).
