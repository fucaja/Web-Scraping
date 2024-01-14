# Web-Scraping

El web scraping, también conocido como extracción de datos web, es una técnica automatizada utilizada para recopilar información de sitios web. Consiste en extraer datos de páginas web, ya sea de manera manual o, más comúnmente, mediante programas informáticos, para luego procesar y analizar esos datos. 

El proceso de web scraping generalmente implica enviar solicitudes HTTP a un sitio web y luego analizar el HTML o XML resultante para extraer la información deseada. Puede ser utilizado para recopilar datos como precios de productos, información de noticias, reseñas de productos, datos meteorológicos y mucho más.

### Web crawling

El web crawling, también conocido como rastreo web o spidering, es el proceso de navegar automáticamente por la World Wide Web y recopilar información sobre sitios web. Estos crawlers siguen enlaces de una página a otra, indexando el contenido de los sitios web que visitan.

El objetivo principal del web crawling es recopilar datos para construir índices de búsqueda utilizados por motores de búsqueda como Google, Bing y otros. Estos índices permiten a los motores de búsqueda ofrecer resultados rápidos y relevantes cuando los usuarios realizan consultas.

El proceso de web crawling implica enviar solicitudes HTTP a las páginas web, recuperar el contenido HTML de esas páginas y luego analizar ese contenido para extraer información relevante. Los crawlers también siguen enlaces dentro de las páginas para descubrir nuevas páginas y ampliar su alcance.

Es importante destacar que el web crawling se realiza de manera automatizada y a gran escala para gestionar el vasto y dinámico contenido de la web. Además, los web crawlers deben seguir las reglas establecidas por los sitios web a través del archivo robots.txt para respetar las políticas de exclusión de rastreo y evitar sobrecargar los servidores de un sitio específico.

# API

Interfaz de Programación de Aplicaciones (API), es un conjunto de reglas y protocolos que permite a una aplicación o servicio comunicarse con otro. En términos simples, una API define la forma en que los componentes de software deben interactuar.

Las API actúan como intermediarios que permiten que diferentes aplicaciones se comuniquen entre sí. Proporcionan un conjunto de funciones, métodos y reglas que permiten a los desarrolladores acceder a ciertas características o datos de una aplicación, servicio o plataforma, sin necesidad de conocer los detalles internos de su implementación. Esto facilita la integración de servicios y la construcción de aplicaciones más complejas a partir de componentes existentes.

Hay varios tipos de API, pero las dos categorías principales son:

- **APIs web (Web APIs):** Estas son APIs que se acceden a través de Internet mediante protocolos como HTTP. Las API web son comunes en el desarrollo de aplicaciones web y móviles. Pueden devolver datos en formatos como JSON (JavaScript Object Notation) o XML (eXtensible Markup Language).

- **APIs de bibliotecas o SDK (Software Development Kit):** Estas son APIs que se proporcionan como parte de una biblioteca o conjunto de herramientas de desarrollo. Los desarrolladores pueden utilizar estas APIs para acceder a funciones específicas o servicios sin tener que escribir todo el código desde cero.

# API vs Web scraping

API y web scraping son enfoques diferentes para obtener datos de la web, y cada uno tiene sus propias características y casos de uso específicos. Las diferencias clave son:

### Acceso a datos:

- **API:** Proporciona un acceso estructurado a datos a través de interfaces predefinidas. Los datos se entregan generalmente en un formato específico, como JSON o XML, facilitando su manipulación.
- **Web scraping:** Involucra extraer datos directamente del HTML de las páginas web. Los datos extraídos pueden requerir un procesamiento adicional para estructurarse de manera útil.

### Integración y automatización:

- **API:** Diseñada para facilitar la integración entre aplicaciones y servicios. Permite la automatización de procesos y la transferencia de datos de manera eficiente.
- **Web scraping:** Puede ser más manual y propenso a cambios en la estructura de la página web. La automatización puede ser más complicada y menos confiable en comparación con el uso de APIs.

### Legalidad y ética:

- **API:** Se utiliza de acuerdo con los términos de servicio proporcionados por el proveedor de la API. Generalmente, el acceso a través de una API es legal y ético, siempre y cuando se respeten las restricciones y políticas establecidas.
- **Web scraping:** Puede estar sujeto a restricciones legales y éticas, ya que algunos sitios web prohíben explícitamente la extracción automatizada de datos en sus términos de servicio.

### Estructura y mantenimiento:

- **API:** Ofrece una interfaz más estable y estructurada. Cambios en la estructura de los datos o en la API se comunican a los desarrolladores de manera controlada.
- **Web scraping:** Puede volverse frágil si hay cambios en la estructura de la página web, ya que depende directamente de la presentación HTML de la página.

### Desempeño:

- **API:** Suele ser más eficiente y rápida, ya que se diseñó para entregar datos de manera optimizada.
- **Web scraping:** Puede ser más lento y demandante de recursos, ya que implica descargar y analizar el contenido completo de las páginas web.

En resumen, mientras que las APIs proporcionan un acceso estructurado y más confiable a datos en línea, el web scraping puede ser una solución cuando no hay una API disponible o para obtener datos específicos de una página web. Sin embargo, es crucial respetar los términos de servicio y las leyes aplicables al realizar web scraping.