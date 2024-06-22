# Instrucciones para Proyecto 1
**El diseño debe quedar igual al del PDF las card, navbar,iconos y imagenes en el mismo lugar, en el repositorio se encuentran las imagenes. 
**No se permite usar boostrap

**Entregar antes de las fechas indicadas. No se aceptan tareas despues de la fecha. 
## Parte 1: Crear el Repositorio y Rama

1. **Crear Repositorio en GitHub:**
   - Crear un nuevo repositorio público en GitHub llamado `Proyecto-NoticiasTecnologicas`.
   - Inicializar el repositorio con un archivo `README.md`.

2. **Crear una Rama:**
   - Clonar el repositorio en tu máquina local:
     ```bash
     git clone https://github.com/tu-usuario/Proyecto-NoticiasTecnologicas.git
     ```
   - Crear y cambiar a una nueva rama llamada `FT-Desarrollo`:
     ```bash
     cd Proyecto-NoticiasTecnologicas
     git checkout -b FT-Desarrollo
     ```

## Parte 2: Realizar los Cambios y Commits

1. **Estructura del Proyecto:**
   - Añadir el archivo `index.html` proporcionado al repositorio.
   - Crear un archivo `styles.css` y añadirlo al repositorio.

2. **Diseño con CSS Flex y Grid:**
   - Utilizar CSS Flexbox y Grid para diseñar la página de acuerdo a las siguientes secciones use la fuente   font-family: "Oswald", sans-serif;:
     - **Menú de Navegación:** Diseñar utilizando Flexbox.
     - **Cabecera:** Diseñar utilizando Grid.
     - **Tarjetas de Noticias:** Diseñar utilizando Flexbox para la disposición de las tarjetas.
     - **Banners de Tarjetas:** Diseñar utilizando Grid.
     - **Sección Social y Enlaces de Pie de Página:** Diseñar utilizando Flexbox.
     - **Pie de Página:** Diseñar utilizando Grid.

3. **Commit de los Cambios:**
   - Una vez que tengas los cambios listos, realiza un commit con el siguiente mensaje:
     ```bash
     git add .
     git commit -m "Feat: Entregable 1"
     git push origin FT-Desarrollo
     ```

4. **Fecha de Entrega del Primer Commit:**
   -Puedes Crear los Commits que gustes, sin embargo el commit final debe indicar lo siguiente: 
   - **28 de Junio:** El commit con el mensaje "Feat: Entregable 1" debe estar realizado antes de esta fecha, de lo contrario no sea evaluado .

6. **Segunda Parte del Proyecto:**
   - Continuar con los cambios adicionales y realizar un segundo commit con el mensaje:
     ```bash
     git add .
     git commit -m "Feat: Entregable 2"
     git push origin FT-Desarrollo
     ```

7. **Fecha de Entrega del Segundo Commit:**
   -Puedes Crear los Commits que gustes, sin embargo el commit final debe indicar lo siguiente: 
   - **8 de Julio:** El commit con el mensaje "Feat: Entregable 2" debe estar realizado antes de esta fecha, de lo contrario no sea evaluado .

## Estructura del Proyecto
Proyecto-NoticiasTecnologicas/
│
├── index.html
├── styles.css
├── img/

# Consejos Adicionales
- Asegúrate de probar el diseño en varios navegadores y dispositivos para verificar la responsividad.
- Utiliza herramientas de desarrollo del navegador para depurar y ajustar el diseño según sea necesario.
- Revisa los conceptos de CSS Flexbox y Grid para asegurarte de utilizarlos correctamente.

¡Buena suerte con tu proyecto!
<iframe src="ruta/al/archivo.pdf" width="100%" height="600px">
</iframe>
```HTML
<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NoticiasTecnológicas</title>
  <!-- Fuente -->
  <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;500&display=swap" rel="stylesheet">
  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css">
  <!-- CSS Personalizado -->
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <!-- Entregable 1 28 junio -->
  <div class="boton-menu">
    <i class="fas fa-bars fa-2x"></i>
  </div>

  <div class="contenedor">
    <!-- Navegación -->
    <nav class="navegacion-principal">
      <!-- Aqui va el logo(Marca de la compañia) usar la clase  :  navegacion-principal__marca-->
 
      <!-- Navegación Izquierda -->
      <ul class="navegacion-principal__menu">
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Buscar</a></li>
        <li><a href="#">Tu Biblioteca</a></li>
        <li><a href="#">Crear Playlist</a></li>
        <li><a href="#">Tus Favoritos</a></li>
      </ul>
      <!-- Navegación Derecha -->
      <ul class="navegacion-principal__menu-derecha">
        <li><a href="#"><i class="fas fa-search"></i></a></li>
      </ul>
    </nav>
    <hr>

    <!-- CABECERA -->
    <header class="cabecera">
      <h2>¡Grandes Noticias Hoy!</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Id dolor laudantium rerum, excepturi est praesentium natus qui? Tempora rerum, numquam inventore eligendi in, nostrum reprehenderit, eum cumque fugit eaque similique!</p>
      <a href="#" class="boton">Regístrate <i class="fas fa-chevron-right"></i></a>
    </header>

    <!-- TARJETAS DE NOTICIAS -->
    <div class="tarjetas-noticias">
      <div class="tarjetas-noticias__tarjeta">
     
 
        <h3>Lorem ipsum dolor.</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam dolore fugit esse corporis nesciunt minima doloremque modi mollitia rerum, similique optio eligendi itaque amet qui ullam vel incidunt asperiores fuga?</p>
        <a href="#">Más información <i class="fas fa-angle-double-right"></i></a>
      </div>
      <div class="tarjetas-noticias__tarjeta">
        
        <h3>Lorem ipsum dolor.</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam dolore fugit esse corporis nesciunt minima doloremque modi mollitia rerum, similique optio eligendi itaque amet qui ullam vel incidunt asperiores fuga?</p>
        <a href="#">Más información <i class="fas fa-angle-double-right"></i></a>
      </div>
      <div class="tarjetas-noticias__tarjeta">
     
        <h3>Lorem ipsum dolor.</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam dolore fugit esse corporis nesciunt minima doloremque modi mollitia rerum, similique optio eligendi itaque amet qui ullam vel incidunt asperiores fuga?</p>
        <a href="#">Más información <i class="fas fa-angle-double-right"></i></a>
      </div>
      <div class="tarjetas-noticias__tarjeta">
     
        <h3>Lorem ipsum dolor.</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam dolore fugit esse corporis nesciunt minima doloremque modi mollitia rerum, similique optio eligendi itaque amet qui ullam vel incidunt asperiores fuga?</p>
        <a href="#">Más información <i class="fas fa-angle-double-right"></i></a>
      </div>
    </div>
  <!-- Entregable 2 8 de julio-->
    <!-- Banner de Tarjetas 1-->
    <section class="banner-tarjetas-uno">
      <div class="banner-tarjetas-uno__contenido">
        <h2>Lorem ipsum dolor.</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellat maxime facilis quasi alias illo, fugiat cupiditate porro dolores tenetur delectus!</p>
        <a href="#" class="boton">Más información <i class="fas fa-chevron-right"></i></a>
      </div>
    </section>

    <!-- TARJETAS DE NOTICIAS -->
    <div class="tarjetas-noticias">
      <div class="tarjetas-noticias__tarjeta">
   
        <h3>Lorem ipsum dolor.</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam dolore fugit esse corporis nesciunt minima doloremque modi mollitia rerum, similique optio eligendi itaque amet qui ullam vel incidunt asperiores fuga?</p>
        <a href="#">Más información <i class="fas fa-angle-double-right"></i></a>
      </div>
      <div class="tarjetas-noticias__tarjeta">
    
        <h3>Lorem ipsum dolor.</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam dolore fugit esse corporis nesciunt minima doloremque modi mollitia rerum, similique optio eligendi itaque amet qui ullam vel incidunt asperiores fuga?</p>
        <a href="#">Más información <i class="fas fa-angle-double-right"></i></a>
      </div>
    </div>

    <!-- Banner de Tarjetas 2-->
    <section class="banner-tarjetas-dos">
      <div class="banner-tarjetas-dos__contenido">
        <h2>Lorem ipsum dolor.</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut qui laudantium id quam magni accusantium, veritatis, ipsam labore, reprehenderit dolore repudiandae nemo sint deserunt! Suscipit facilis qui inventore consequatur fugit.</p>
        <a href="#" class="boton">Más información <i class="fas fa-chevron-right"></i></a>
      </div>
    </section>

    <!-- Seguir -->
    <section class="social">
      <p>Sigue a NoticiasTecnológicas</p>
      <div class="social__enlaces">
        <a href="https://facebook.com"><i class="fab fa-facebook-f"></i></a>
       <!-- Aqui va el resto de los iconos-->
 
      </div>
    </section>
  </div>

  <!-- Enlaces de Pie de Página -->
  <div class="enlaces-pie">
    <div class="enlaces-pie__contenedor">
      <ul class="enlaces-pie__lista">
        <li><a href="#"><h3>Título Uno</h3></a></li>
        <li><a href="#">Blockchain</a></li>
      </ul>
      <ul class="enlaces-pie__lista">
        <li><a href="#"><h3>Título Dos</h3></a></li>
        <li><a href="#">Computación Cuántica</a></li>
      </ul>
    </div>
  </div>

  <!-- Pie de Página -->
  <footer class="pie">
    <h3>Derechos de Autor de NoticiasTecnológicas</h3>
  </footer>

 
</body>

</html>
```
