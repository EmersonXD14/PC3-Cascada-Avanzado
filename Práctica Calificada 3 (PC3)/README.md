### IngeArq Solutions | Portafolio Interactivo

Repositorio oficial del proyecto desarrollado para la Práctica Calificada 3 (PC3) del curso de especialización. Este proyecto simula la plataforma digital corporativa de IngeArq Solutions, una empresa ficticia enfocada en ingeniería de software, arquitectura web y soluciones tecnológicas avanzadas. 

### Descripción del Proyecto

El portafolio interactivo está construido utilizando HTML5 semántico, CSS3 avanzado (con diseño modular y animaciones personalizadas) y el sistema de diseño responsivo de Bootstrap 5.3.3. La interfaz destaca por su estilo corporativo gerencial, evitando diseños informales o recargados, y ofrece una experiencia de navegación fluida mediante anclas internas (smooth scroll). 

### Transformaciones y Animaciones CSS Aplicadas

Cumpliendo con los estándares de maquetación avanzada, el código fuente implementa las siguientes propiedades geométricas y efectos de dinamismo: 

### 1. Transformaciones 2D y Transiciones

* **Rotación Espacial (rotate):** Aplicada en las tarjetas de la sección de proyectos para inclinar dinámicamente el contenedor al interactuar con el cursor.
* **Escalado Dinámico (scale):** Utilizada para ampliar de forma volumétrica las dimensiones del elemento al recibir el evento de hover.
* **Traslación Vectorial (translateY):** Desplaza verticalmente los bloques para generar un efecto visual de elevación fluida.
* **Laboratorio Interactivo (Skew & Matrix):** Se integraron paneles de prueba que demuestran la deformación de planos mediante skew() y matrices de transformación geométrica con matrix().

### 2. Efecto Visual Tridimensional (3D)

* **Perspectiva Espacial (perspective: 1200px):** Configurada en la escena tridimensional para dotar de profundidad realista a los elementos estructurales.
* **Preservación 3D y Rotación en Ejes (transform-style: preserve-3d y rotateY):** Implementada en la tarjeta interactiva principal que realiza un giro espacial de 180° al colocar el cursor sobre ella, ocultando correctamente las caras posteriores mediante backface-visibility: hidden.

### 3. Animaciones con Fotogramas (@keyframes)

* **Animación de Entrada Suave:** Desplazamiento vertical fluido combinado con opacidad (fadeIn / translateY) para la cabecera principal (Hero).
* **Indicador de Carga Rotativo:** Animación infinita de rotación de 360 grados (rotate) aplicada al componente visual de carga.

### Estructura y Secciones de la Página

* **Barra de Navegación Superior:** Diseño oscuro corporativo con soporte para desplazamiento fluido (Smooth Scroll).
* **Sección Hero:** Presentación institucional con tipografía moderna (*Poppins* e *Inter*) e insignias de ingeniería web.
* **Sección de Transformaciones 2D:** Tarjetas interactivas y un laboratorio visual de pruebas con contenido gráfico real.
* **Sección de Experiencia 3D:** Tarjeta tridimensional interactiva con renderizado de hardware y efectos volumétricos.
* **Dashboard de Métricas Corporativas:** Panel gerencial moderno con indicadores de rendimiento (Proyectos desarrollados, Disponibilidad de servidores y SLA 24/7) acompañados de barras de progreso fluidas.
* **Centro de Operaciones y Contacto:** Formulario corporativo, datos de contacto institucionales, enlaces oficiales a redes sociales (LinkedIn, GitHub, Twitter, Instagram) e integración de un mapa interactivo de Google Maps.

### Tecnologías y Librerías Utilizadas

* **HTML5:** Estructura web semántica.
* **CSS3 Puro:** Transformaciones geométricas, transiciones y animaciones por fotogramas.
* **Bootstrap 5.3.3 (CDN):** Sistema de rejilla responsivo y clases utilitarias corporativas.
* **Bootstrap Icons 1.11.3 (CDN):** Iconografía oficial para redes sociales, indicadores y paneles.
* **Google Fonts:** Fuentes tipográficas institucionales *Inter* y *Poppins*.

### Despliegue y Visualización Local

1. Clona este repositorio o descarga los archivos fuente.
2. Asegúrate de mantener la siguiente estructura en la raíz del proyecto: 

text

├── index.html     # Código de la estructura principal
├── styles.css     # Estilos modulares y transformaciones CSS
└── README.md      # Documentación del proyecto

Usa el código con precaución.
3. Abre el archivo index.html en cualquier navegador moderno. Se requiere conexión a internet para la carga correcta de las librerías alojadas en CDN.