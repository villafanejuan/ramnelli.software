
# 💻 Ramnelli Software — Transformando Ideas en Realidades Digitales

Esta es la Landing Page oficial de Ramnelli Software, construida para presentar nuestros servicios de desarrollo de software a medida, nuestra misión, visión y proceso de trabajo.

La página está optimizada para performance, SEO y garantiza una experiencia de usuario responsive y moderna.

## 🌟 Características Principales

* **Diseño Moderno:** Estética oscura (`bg-ink-900`) con acentos en violeta (`brand-primary`) usando la paleta de colores de Tailwind CSS.
* **Totalmente Responsive:** Adaptado a dispositivos móviles y de escritorio.
* **Optimización SEO y Social:** Incluye metadatos de SEO (`description`, `canonical`) y Open Graph/Twitter Card para compartir en redes sociales.
* **Formulario de Contacto Funcional:** Utiliza **EmailJS** para el envío de correos sin necesidad de un *backend* propio, facilitando la recepción de consultas directamente en la bandeja de Gmail configurada.
* **Tecnologías:** Construido puramente en HTML, CSS (Tailwind CSS CDN) y JavaScript vanilla.

## 🛠️ Tecnologías Utilizadas

| Tecnología | Descripción | Uso |
| :--- | :--- | :--- |
| **HTML5** | Estructura semántica del contenido. | Base del proyecto. |
| **Tailwind CSS** | Framework CSS utility-first a través de CDN. | Estilizado rápido y diseño responsive. |
| **EmailJS** | Servicio de terceros para el envío de formularios. | Manejo del formulario de contacto sin *backend*. |
| **Font Awesome** | Iconografía (`fa-solid`, `fa-regular`). | Elementos visuales y decorativos. |
| **JavaScript (Vanilla)** | Lógica simple: menú móvil y manejo del formulario. | Interacción y funcionalidad. |

## 📧 Configuración del Formulario (EmailJS)

El formulario de contacto (`#contactoForm`) utiliza la librería **EmailJS** para el envío de datos. Para que funcione correctamente en cualquier entorno (incluyendo producción), debes verificar las siguientes claves en el script al final del `index.html`:

```javascript
const EMAILJS_SERVICE_ID = 'TU_ID_SERVICE'; // Tu ID de Servicio
const EMAILJS_TEMPLATE_ID = 'EMAILJS_TEMPLATE_ID; // Tu ID de Plantilla
const EMAILJS_PUBLIC_KEY = 'EMAILJS_PUBLIC_KEY'; // Tu Public Key (User ID)
```
Asegurar la Recepción en Gmail
Si los correos llegan a la carpeta de Promociones o Spam, sigue estos pasos en tu cuenta de Gmail:

Envía un correo de prueba desde el formulario.

Busca el correo en la pestaña de "Promociones" o "Spam".

Arrastra el correo y suéltalo sobre la pestaña "Principal".

Confirma la acción con "Sí" para crear un filtro de confianza.

⚙️ Estructura del Código
El código está organizado en secciones ancladas para facilitar la navegación interna:

Header (<header>): Sticky navigation con menú principal y menú móvil.

Hero (#contenido): Titular principal y CTA.

Servicios (#servicios): Listado de soluciones ofrecidas.

Misión & Visión (#mision-vision): Objetivos de la compañía.

Proceso (#proceso): Etapas del desarrollo de software.

FAQ (#faq): Preguntas frecuentes con detalles colapsables.

Contacto (#contacto): El formulario de contacto y CTA final.

Footer (<footer>): Información de contacto, enlaces y redes sociales.

📝 Contacto y Licencia
Para cualquier pregunta o sugerencia sobre el código:

Email: ramnelli.software@gmail.com

Website: https://ramnelli.software/

© Ramnelli Software. Todos los derechos reservados.
