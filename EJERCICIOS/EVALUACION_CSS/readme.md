## 5. LENGUAJE CSS

Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de
una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que
consideren correcta.

Preguntas:

1. ¿Qué significa CSS? (valor 0.25)

          a) Cascading Style Sheets
                   
2. ¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa?
(valor 0.25)

          b) <link rel="stylesheet" type="text/css" href="style.css">
          
          
3. ¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a
una hoja de estilo externa? (valor 0.25)

          a) En la sección <head>
                  
 4. ¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)
 
          a) <css>
                    
 5. ¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)

         b) styles
                 
 6. ¿Cuál es la sintaxis CSS correcta? (valor 0.25)

         b) body {color: black;}
          
          
 7. ¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

          a) /* esto es un comentario */
                   
8. ¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)

         b) background-color
                    
9. ¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)
  
          b) h1 {background-color:#FFFFFF;}
           
10. ¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)
  
          c) color
  
 11. ¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25
  
         c) font-size
            
 12. ¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)
  
           c) p {font-weight:bold;}
            
13. ¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)
  
          b) text-transform:capitalize
            
14. ¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)
  
          b) font-family
           
15. ¿Cómo pones el texto en negrita? (valor 0.25)
  
          c) font-weight:bold;
  
16. ¿Cómo se muestra un borde como este? (valor 0.25)

El borde superior = 10 píxeles

El borde inferior = 5 píxeles

El borde izquierdo = 20 píxeles

El borde derecho = 1 píxel
  
           d) border-width:10px 5px 20px 1px; (valor 0.25)
          
17. ¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

           b) margin-left
          
18. Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)

            b) Sí
                        
 19. ¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)
 
            b) #demo
                       
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)

             c) #test
                        
21. ¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)

             b) div p
                        
22.¿Cómo se agrupan los selectores? (valor 0.25)

             c) Separe cada selector con una coma
            
23. ¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

            d) static
            
 24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)
 
             c) list-style-type: square;
            
Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la
maquetación en código html y css, valor 36)

![image](https://user-images.githubusercontent.com/91554777/166742177-b3cc2bfc-7768-42e4-b4f0-dcc2a1473935.png)


![image](https://user-images.githubusercontent.com/103137328/171925651-651bfb10-d8cd-4f1f-9ff6-7bccf41f9aa2.png)

● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

-Hay tres imágenes que utilizarás para realizar esta actividad:
Imagen del logo institucional.
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

Imagen paisaje de la Ciudad de México
https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

-El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”


          INGRESA AQUI EL CÓDIGO HTML
          
          
          <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css\estil.css">
    <title>EXAMEN</title>
</head>
            <body>
                    <head>
                        <img src="E:\EXAMEN CCS\IMG\logo.svg"><hr>
                                <nav>
                                        <ul>
                                                    <li>Residentes</li>
                                                    <li>Negocios</li>
                                                    <li>Visitantes</li>  
                                                    <li>Gobierno</li> 
                                        </ul>
                                </nav>
                             

                    </head>
                    

                            <main>
                                    <div class="logo">
                                        <img src="E:\EXAMEN CCS\IMG\CDMX.png" alt="">
                                        
                                            <div class="texto">

                                                    <img src="E:\EXAMEN CCS\IMG\hero-vector.svg" alt="">

                                            </div>


                                     </div>

                            </main>
    


                            <footer>

                                    <h3>¿Quien se puede inscribir?</h3>

                                        <p>Cualquier persona que quiera aprender codigo y cuente con 4-8 horas disponibles a la semana.</p>
                                        <br>
                                        <p>"Menores de edad deberan entrar a las instalaciones acompañados de un adulto.</p>


                            </footer>













            </body>

</html>
          
          INGRESA AQUI EL CSS
          
          
         *{
    padding: 0;
    margin: 0;
}

header{
    height: 100vh;
    background: url(https://th.bing.com/th/id/R.7049f96a7ab04d4ffe56f6b7a180dd31?rik=KXuBl64z1lEW%2fw&riu=http%3a%2f%2fwww.solofondos.com%2fwp-content%2fuploads%2f2015%2f11%2fFondos-para-paginas-web-profesionales-3D.jpg&ehk=lWv3MXhrf5twGIElvqeFkf1879q3Y4fb8nZFCm8U5hQ%3d&risl=&pid=ImgRaw&r=0);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    padding: 50px;
    
}

.logo{
    font-size: 100px;
    text-shadow: 5px 5px 5px magenta;
    color: rgb(4, 0, 255);
    
    
}


nav{

    display: flex;
    justify-content: space-between; 
    
}


ul{
    display: flex;
    list-style: none;
}


li{
    background: linear-gradient(rgba(255,0,0,.5),rgba(5, 5, 245,.5));
    margin-left: 40px;
    color: rgb(248, 245, 241);
    border-radius: 30px;
    padding: 10px;
}


.caja{
        height: 80vh;
        width: 100%;
        display: flex; align-items: flex-end;
}

.cajita{
    border-radius: 20px;
    background:linear-gradient(rgba(255,0,0,.5),rgba(5, 5, 245,.5));
    text-transform: capitalize;
    
}

.whatsapp{
    position: fixed;
    bottom: 370px;
    left: 90px;
}

main{
    height: 100vh;
    background-color: rgb(114, 243, 237);
    align-items: center;
    display: flex;
}

.paralax{
    height: 50vh;
    width:  80%;
    margin: auto;
    background: url(https://i.blogs.es/acd781/mario-kart-8-deluxe/1366_2000.jpg);
    background-repeat: no-repeat;
    background-size:cover;
    background-position: center;
    background-attachment: fixed;
    display: flex;
    align-items: center;
    justify-content: center;
    

}
.paralax p{
    color: bisque;
    text-size-adjust: 30px;
    padding: 20px;
    }
