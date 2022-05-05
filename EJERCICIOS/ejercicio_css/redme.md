5. LENGUAJE CSS
Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que consideren correcta.

Preguntas:

¿Qué significa CSS? (valor 0.25)

     a) Cascading Style Sheets
    
   
¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa? (valor 0.25)

     
     b) <link rel="stylesheet" type="text/css" href="style.css">
    
     
¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a una hoja de estilo externa? (valor 0.25)

     a) En la sección <head>
    
  
¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)

    
    c) <style>
  
¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)

    
    b) styles
   
    
¿Cuál es la sintaxis CSS correcta? (valor 0.25)

    
    b) body {color: black;}
  
  
¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

    a) /* esto es un comentario */
    
¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)

   
     b) background-color
   

¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)

    
     b) h1 {background-color:#FFFFFF;}
    
   
¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)

    
    c) color
  
¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25

    
     c) font-size
    
 
¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)

     c) p {font-weight:bold;}
  
   
¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)

    
    b) text-transform:capitalize
    

¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)

  
    b) font-family
    
¿Cómo pones el texto en negrita? (valor 0.25)

   
    c) font-weight:bold;

¿Cómo se muestra un borde como este? (valor 0.25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel

        a) border-width:10px 1px 5px 20px;
         (valor 0.25)
      
¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

   
    b) margin-left

Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)

      a) No
      
¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)

    
     b) #demo
     
   
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)

          
          b) .test
          

¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)

     
      b) div p
    
    
22.¿Cómo se agrupan los selectores? (valor 0.25)

          
          c) Separe cada selector con una coma
        
¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

     
      d) static

24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)

          a) list-type: square;
         
        
Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la maquetación en código html y css, valor 36)

![image](https://user-images.githubusercontent.com/101900664/166944372-352b9c68-60dc-4fff-8f9c-2d63b30c1c7c.png)


![image](https://user-images.githubusercontent.com/101900664/166953698-0b982036-d922-4a85-a696-1952c93eff8f.png)


● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizarás para realizar esta actividad: Imagen del logo institucional. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”

            INGRESA AQUI EL CÓDIGO HTML
          <!DOCTYPE html>
          <html lang="en">
          <head>
              <title>Document</title>
              <link rel="stylesheet" href="estilos.css">
          </head>
          <body>
          <header>
          <img src="logo.png" alt="icon gobierno">
          <hr>
          <nav>
          <div>


          </div>
          <div>
          <b><a href="">Residentes</a> 
          <a href="">Negocios</a> 
          <a href="">Visitantes</a> 
          <a href="">Gobierno</a> </b>
          </div>

          </nav>
          </header>
          <section>

          <div class="cuadro">
          <div id="cuadro1">

          <h1>
          <span>></span> APRENDE A PROGRAMAR <br><span>EN LAS ESCUELAS <br>DE CÓDIGO </span><br>DE LA CDMX
          </h1>
          </div>

          <div id="cuadro2">
          </div>
          </div>
          </section>

          <footer>
          <h2><b>
          ¿Quién se puede inscribir?
          </h2></b>
          <p> 
          Cualquier persona que aprende a programar codigo y cuente con 4-8 horas disponibles. a la semana
          </p>
          <p>
          *Menores de edad deberán entrar a las instalaciones acompanados de un adulto.
          </p>
          </footer>
          </body>
          </html>



            INGRESA AQUI EL CSS
                           a{
               text-decoration: none;
               color: green;

               }
               nav{

                   display: flex;
                   justify-content: space-between;

               }
               .cuadro{
               width:100%;
                display: flex;
                   justify-content: space-between;
               }

               section{
                   background: url("hero.jpg");
                height: 70vh;
               background-repeat: no-repeat;
                   background-position: center;
                   background-size: cover;
               }
               #cuadro1{
               color: white;
                font-size: 1cm;
               width:40%;
               text-align: end;
               }
               span{
               font-weight: bold;
               }



               footer{
               text-align: center;
               justify-content: center;
               }
               footer h2{
                color: rgb(95, 83, 12);
               }
               
               
               
  ![logo](https://user-images.githubusercontent.com/101900664/166970731-686777c9-1f21-41f6-ae0a-0e307d0f5611.png)

  ![hero](https://user-images.githubusercontent.com/101900664/166970779-cac9099e-fd80-496d-8afa-b40a9e6d1648.jpg)
        
               
Ingresa el link a tu página del proyecto final
