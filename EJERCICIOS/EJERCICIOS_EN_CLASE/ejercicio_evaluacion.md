![image](https://user-images.githubusercontent.com/91554777/165175601-f95d8714-091a-4687-a21b-70a75beae3ea.png)

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Título de página</title>
    </head>
    <body>

        <header>
            <h1>ENCABEZADO NIVEL 1</h1>
            <nav>
                <ul>
                    <li><a href="">ENLACE 1</a></li>
                    <li><a href="">ENLACE 2</a></li>
                    <li><a href="">ENLACE 3</a></li>
                    <li><a href="">ENLACE 4</a></li>
                </ul>
            </nav>
        </header>


        <main>

            <article>
                <h2>Encabezado nivel 2</h2>
                <p>Aqui va el texto del primer <b>Párrafo</b></p>
                <p>Aqui va el texto del segundo párrafo</p>
            </article>

            <aside>
                <h2>Apartado</h2>
                <p>Elige una opción</p>
                <form action="">
                    <input type="radio" name="opcion">Opción 1 <br>
                    <input type="radio" name="opcion">Opción 2 <br>
                    <input type="radio" name="opcion">Opción 3 <br>
                    <input type="submit" value="Enviar">
                </form>
            </aside>

        </main>


        <footer>
            <p>Sección de información de contacto, derechos de autor, etc</p>

        </footer>

    </body>
    </html>


## AGREGA EL CSS NECESARIO A LA PÁGINA.


            <!DOCTYPE html>
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <meta http-equiv="X-UA-Compatible" content="IE=edge">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>Titulo de página</title>
                <link rel="stylesheet" href="estilos.css">
            </head>
            <body>
                <header>
                    <h1>ENCABEZADO NIVEL 1</h1><br>
                    <nav>
                        <a href="url">ENLACE 1        </a>
                        <a href="url">ENLACE 2        </a>
                        <a href="url">ENLACE 3        </a>
                        <a href="url">ENLACE 4        </a>
                    </nav>
                </header>
                <main>
                    <article>
                        <h2><b>Encabezado nivel 2</b></h2> <br>
                        <p>Aquí va texto del primer <b>párrafo</b></p><br>
                        <p >Aquí va texto del segundo párrafo</p>
                    </article>
                    <aside>
                        <h2> <b>Apartado</b></h2>
                        <form>
                            <form>
                                Elije una opcion<br>

                                <input type="radio" id="gender" name="gender" value="opcion1"/>Opción 1 <br>
                                <input type="radio" id="gender" name="gender" value="opcion2"/>Opción 2 <br>
                                <input type="radio" id="gender" name="gender" value="opcion3"/>Opción 3 <br/>
                                <br><input type="submit" value="Enviar">
                            </form>

                        </aside>
                </main>
                <footer>
                    <p>Sección de informacion de contacto,derechos de autor, etc.</p>
                </footer>
            </body>

            </html>






            body{
                background-color: rgb(94, 143, 94);
            }
            header 


                    h1{
                    color: rgb(185, 238, 185);
                    }
                 header {
                     background-color: rgb(10, 32, 10);
                 }
                nav {
                    background-color: rgb(188, 228, 188);
                }
                header{
                    text-align: center;
                }

            main article{

                background-color: rgba(71, 163, 216, 0.466);

            }    
            main aside {
                background-color: rgb(128, 12, 128);
            }
            article p,h2 {
                text-align: center;

            }
            aside {
                text-align: center;
            }
            aside form {
                text-align: center;
            }
            footer {
                background-color: rgb(199, 199, 25);
                text-align: center;
            }
