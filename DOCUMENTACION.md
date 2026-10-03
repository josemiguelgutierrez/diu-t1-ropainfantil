# Documentación de la interfaz – **ClothesKids**

## 1. Justificación del diseño
### 1.1 Importancia del diseño centrado en el usuario
El diseño centrado en el usuario es muy importante, ya que esto va a determinar si la aplicación va a ser más o menos usada. En nuestro caso es una aplicación que la van a utilizar especialmente las madres, padres, abuelos y abuelas para comprar ropa de niños pequeños, entonces lo ideal es crear la aplicación pensando en esas personas que usarán nuestra app, para satisfacer su uso con nuestra aplicación. Una de las cosas que implementamos es una interfaz sencilla donde todo se ve claro ya sea la ropa, la talla, para que tengan claro cual es la correcta y no se equivoquen, con los botones fáciles de pulsar, para que así no les resulte difícil y lento de comprar, y así puedan seguir usando nuestra app.
### 1.2 Objetivos y metas del proyecto
- **Compras rápidas:** Que los usuarios desde que entren en nuestra aplicación y estén en la pantalla de inicio, puedan realizar una compra en poco tiempo, por ejemplo que realicen una compra en menos de 3 minutos.

- **Tallas claras:** Cuando los usuarios seleccionen un producto, queremos que tengan un selector de tallas que se vea claro para que no haya fallos y una guía de talla que se pueda acceder fácil y la puedan encontrar sin ayuda, en la que por cada talla haya características de medida de las distintas tallas de la ropa.

- **Búsqueda fácil:** Lo que queremos en este objetivo es que los usuarios puedan llegar al carito en un máximo de 5 toques, para que así les sea más fácil comprar y encuentren los productos por categorías de edad y filtrándolos por precio o por la talla.
### 1.3 Beneficios esperados
**Para el usuario:**
- Elegir la talla con claridad para hacer las compras más seguras.
- Que tarden menos en hacer las compras.
- Navegación sencilla para el uso de una mano.

**Para la empresa:**
- Que haya menos devoluciones porque se hayan equivocado con la talla.
- Más fidelización de madres, padres, abuelas y abuelos con la aplicación.
- Que se realicen más compras a través de la aplicación y que no dejen a medias los pedidos.
## 2. Investigación y análisis de usuarios
### 2.1 Datos demográficos y segmentación
Los usuarios que usan nuestra aplicación, están divididos en dos grupos: 
- Los padres y madres de entre 25-50 años de edad, que usan nuestra aplicación para comprar ropa y calzado frecuentemente para sus hijos de 0 a 14 años. 
- Los abuelos y abuelas de entre 55-70 años de edad, que usan nuestra aplicación para comprar regalos en ocasiones especiales.
Nuestros usuarios compran desde nuestra apicación utilizando un teléfono móvil y con una mano, en períodos de tiempo breve.
### 2.2 Personas
#### Persona 1: Mónica
- **Edad:** 35 años.
- **Contexto:** Es una madre que trabaja como contable en una oficina a jornada completa y vive con su marido. Tiene dos hijos, uno pequeño de 5 años y otra hija de 11 años. Ella suele comprar ropa frecuentemente ya que sus hijos crecen y necesita más ropa. No tiene mucho tiempo libre así que lo hace en ratos libres, como cuando tiene un pequeño descanso en el trabajo, o por la noche un rato antes de dormir, ella lo suele hacer con una mano.
- **Objetivos:** Comprar rápido y seleccionar la talla correcta para no devolver la ropa.
- **Frustraciones:** Que la aplicación sea lenta, que no haya claridad con la selección de las tallas y abandona la compra si hay que dar muchos pasos, o si la aplicación no es fácil de usar.
#### Persona 2: Paco
- **Edad:** 65 años.
- **Contexto:** Es un abuelo que vive con su mujer. Tiene tres nietos con edades de 5, 7 y 9 años, y de vez en cuando en los cumpleaños de cada uno o en ocasiones especiales decide comprarles ropa o calzado para una sorpresa, aunque no sabe sus tallas con seguridad. Al estar jubilado tiene más tiempo para realizar la compra, pero realiza la compra con ayuda ya que no sabe manejarse mucho con el móvil.
- **Objetivos:** Ver todo en la aplicación con claridad y que sea sencillo realizar la compra sin muchos pasos.
- **Frustraciones:** Que no entienda el funcionamiento de la aplicación, y que los botones de la aplicación sean chicos y no los vea.
### 2.3 Análisis de la competencia

Las aplicaciones que he analizado son las siguientes:

| App | Qué hace bien | Qué hace mal | Qué me llevo |
|-----|---------------|--------------|--------------|
| **Zara** | En cada producto tiene una guía de tallas para facilitar al usuario elegir la talla correctamente, cuenta con una sección de niños y puedes seguir tus pedidos fácilmente. | Tarda en cargar las imágenes de los productos o a veces la aplicación se cierra sola por una mala optimización. | Poner la guía de tallas dentro del detalle del producto, con medidas del niño y usar imágenes más ligeras para que cargue más ráìdo. |
| **H&M** | Guía de tallas accesible desde cada producto, con versión para bebé y niños y medidas como la altura. | El proceso para realizar una compra desde el inicio hasta realizar el pago es largo, ya que su checkout es largo. | Que el proceso para realizar una compra sea breve y tarde poco tiempo. |
| **Shein** | Recomendaciones personalizadas y tiene reseñas de otros compradores que facilita para decidir la talla. | Interfaz muy saturada de productos, sin que se vea limpia y puede llevar a confundir al usuario. | Evitar el exceso de animaciones y productos, y priorizar una interfaz más limpia para un uso más fácil. |
### 2.4 Insights y hallazgos clave
1. **Insight:** Los usuarios dudan con las tallas porque cada marca usa unas medidas distintas.
   
   **Decisión:** Poner en cada producto un selector de talla, con un botón de guía de tallas que abre un bottom sheet con las medidas.

2. **Insight:** Los usuarios compran con una mano y con poco tiempo.
   
   **Decisión:** Los botones principales como los de comprar o añadir al carrito, ponerlos más grandes con área táctil de 48x48 dp y implementar una navegación con navigation bar para que se muevan más rápido por la aplicación.

3. **Insight:** Una interfaz saturada de productos hace que el usuario se confunda.
   
   **Decisión:** Implementar una interfaz con las categorías claras con filter chips y con pantallas más limpias.

4. **Insight:** Un checkout largo hace que los usuarios abandonen la compra.
   **Decisión:** Implementar un checkout corto, con pocos campos y mensajes de ayuda claros si hay un error.

## 3. Diseño de la interfaz
### 3.1 Mapa de navegación (bloque ```mermaid```)
### 3.2 Wireframes
### 3.3 Guía de estilo Material Design 3
### 3.4 Prototipo de alta fidelidad

## 4. Validación y pruebas
### 4.1 Metodología (mín. 3 tareas y métricas)
### 4.2 Resultados (tabla con mín. 2 participantes)
### 4.3 Iteraciones y mejoras (antes/después)

## 5. Entrega y documentación final
### 5.1 Justificación del diseño propuesto
### 5.2 Recomendaciones y pasos a seguir

## 6. Referencias bibliográficas (mín. 4, APA 7, exportadas desde Zotero)

Palabra del día: **29**
