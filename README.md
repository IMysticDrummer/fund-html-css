# FUNDAMENTOS HTML-CSS
## PRÁCTICA WEB PORTFOLIO

**Autor:** Iván García Rodríguez (*IMysticDrummer*).

## IMysticDrummer (Iván García Rodríguez)

Soy un experimentado programador *web full stack*, preparado para hacer frente a todos los retos que se me plantéen.

### Notas previas
> He arriesgado haciendo una web con colores complejos, derivados del logo elegido, un fénix.  

> La paleta de colores, a partir del logo, la he obtenido de la web [coolors](https://coolors.co/).  

> La página personalizada error 500 se obtiene cuando se envía el formulario.  

# UTILIZACIÓN DE LA WEB
- Opción 1:
> Lanzar la web desde la dirección [imysticdrummer.github.io/fund-html-css/](imysticdrummer.github.io/fund-html-css/).  

- Opción 2:
> Clonar el repositorio. Después arrancar el archivo index.html en un navegador  

> `git clone https://github.com/IMysticDrummer/fund-html-css.git`.  

## REQUISITOS DE LA PRÁCTICA
> **Mobile First**
>> *Web diseñada primero para pantalla móvil* --> Sí.  
>> *Web adaptada para pantallas intermedias* --> Sí.  
> **Una o varias hojas de estilos** --> Sí:
>> Hoja de estilos para resetear CSS.  
>> Hoja de estilos para normalizar CSS en distintos navegadores.  
>> Hoja Style para las condiciones básicas y paleta de colores de la web.  
>> Hoja Header para el CSS de la cabecera.  
>> Hoja Main para el CSS de la parte central.  
>> Hoja Footer para el CSS del pie de página.  
>> Hojas CSS propias para las páginas personalizadas error 404 y error 500.  

> **Barra de navegación**
>> *Links a cada sección del portfolio* --> Sí.  
>> *Estado hover suavizado con transición* --> Sí para pantallas a partir de 1024px.  
>> *Header con imagen de fondo que cambie según las resoluciones* --> Sí.  
>>> Se ha establecido una imagen de logo (no está de fondo), pero carga a diferentes resoluciones (menos de 600px, menos de 1024px y de 1024px en adelante).  

>> *(Opcional) Menú burger en mobile* --> Sí, transformable en entorno tablet o laptop.  

> **Elemento central**
>> *Carrousel con nuestros trabajos* --> Sí.  
>>> Introducidos tres trabajos. Uno con texto. otro con imagen y enlace externo y otro con imagen.  

---
>>> **Nota:** Se produjo un problema al trabajar con `scroll-behavour:smooth` en el `:root` del CSS y
>>> en el carousel. Dicho error afectaba a los navegadores Chrome y Edge. Por dicha razón he decicido
>>> *quitar el desplazamiento suave cuando se pincha en un enlace de la navbar, y dejar el desplazamiento*
>>> *suave y funcionando en el carousel.*
---  

>> *Skills de programación* --> Si.  
>>> *Barras de progreso animadas* --> Si.  
>>> Para un mejor efecto, se van rellenando de manera secuencial.  
>> *Formulario* --> Sí.  
>>> Nombre, Apellidos, Teléfono --> Sí.  
>>> Radiobutton --> Sí.  
>>> Tag de github con el pattern según regex --> Sí.  
>>> Descripción con textarea --> Sí.  
>>> Botón de guardado --> Sí (método post)  
>>>> Enviar el formulario lleva a la página de error 500 personalizada.  

> **Footer**
>> *Links a redes sociales, con noopenner y noreferrer* --> Sí.  

> **Página de proyectos diseñada en grid**
>> Página realizada.  
>> Accesible a través del enlace *Works* del menu de navegación.  
>> Diseño en grid para 8 proyectos.
>>> **Nota:** Sólo he rellenado 3 proyectos, y he dejado preparados
>>> los huecos para el resto.

> **Otros elementos opcionales**
> *Menu hamburguesa para pantallas pequeñas* --> Sí.  
> *Despliege en Github Pages* --> Si.  
> *Página 404 personalizada* --> Si:  
>> Creado un enlace en la barra de navegación para probarla.  
> *Página 500 personalizada* --> Realizado.  
>> Para probarla, rellena el formulario y envíalo.  
>> Te llevará a la página de error del sevidor.  

## WEBSITE MAP
~~~
|- README.md --> Este archivo
|- index.html --> Página principal
|- /src
|  |- 404.html --> Página de error 404
|  |- 500.html --> Página de error 500
|  |- works.html --> Página de proyectos en grid
|
|- /css --> Directorio con los archivos CSS de formato
|- /img --> Directorio de imágenes de la web
|- /video --> Directorio con el video de uso en la página works.html
~~~

**index.html**  
Secciones:
> **Header**  
>> Incluye logo, nombre, nick y navbar.  
>> La navbar tiene formato hamburguesa desplegable para pantallas pequeñas.  
>> La navbar se despiega entera para pantallas a partir de 768px.  
>> La navbar contiene un enlace a la página 404 para su prueba.
> **Caorusel Proyectos importantes**.  
>> Deplazable a través de los puntos en la parte inferior.    
> **SKills** con animación en serie.  
> **Contacto**:  
>> Fomulario con campos requeridos y con validaciones. Contiene:
>>> Nombre, Apellidos, Teléfono y Descripción, como campos requeridos.  
>>> Radiobutton de selección sobre como conociste al autor del portfolio.
>>> Campo de texto con el tag de github, requerido y con validación regexp.
>>> Botón de submit. Este botón tiene estado hover suavizado para pantallas
>>> de 1024px o más.  
>>> El envío del formulario lleva a la página de error 500 (server error).  
> **Footer** con los enlaces a las redes sociales.  

**works.html**  
> Página que muestra los trabajos realizados.  
> Realizada con grid y ajustada a los diferentes tamaños de pantalla.  

# RECURSOS UTILIZADOS
**Deposit photos** --> Obtención del logo del fénix.  
**Web [Coolors](https://coolors.co/)** --> obtención de la paleta de colores a partir del logo (*fénix*).  

**Recursos de internet varios** para la obtención de los logos de redes sociales en png.

