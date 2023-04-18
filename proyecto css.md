html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evaluación CSS</title>
    <link rel="stylesheet" href="css/estilos.css">


</head>
<body>
    <header>
        <img src="img/logo.svg" alt="logo de pagina"> <hr>
        <nav>
            
            <ul>

                <li><a href="">Recidentes</a></li>
                <li><a href="">Negocios</a></li>
                <li><a href="">Visitantes</a></li>
                <li><a href="">Gobierno</a></li>


            </ul>

        </nav>

    </header>
    <main>
        <p><img src="img/hero-vector.svg" alt=""> <span class="aprende"> APRENDE A PROGRAMAR </span>EN LAS <span class="escuela">ESCUELAS DE CODIGO</span>  DE LA CDMX</p>
        

    </main>
    <footer>
        <p class="quien">¿Quien se puede inscribir?</p>
        <p class="p2">Cualquier persona que quiera aprender a programar codigo y cuente con 4 - 8 horas disponibles a la semana</p>
        <p class="p3">*Menores de edad deberan entrar a las instalaciones acompañados de un adulto</p>
        

    </footer>
</body>
</html>


estilos css

* {
    padding: 0;
    margin: 0;
}
header{
    width: 100%;
    height: 15vh;
    

}

ul{
    display: flex;
    justify-content: right;
    align-items: center;
}
li{
    margin:20px;
    list-style-type: none;
}


main{
    width: 100%;
    height: 70vh;
    background: url(..//img/hero.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover ;
    display: flex;
    align-items: center;
    
}
  main p{
    color: #fff;
    font-size: 2.5em;
    text-align: right;
    width: 60%;
}
.aprende{
    color: rgb(236, 236, 236);
    font-weight: bold;
    

}
.escuela{
    color: rgb(255, 255, 255);
    font-size: 3em;
    font-weight: bold;

}

footer{
    width: 100%;
    height: 15vh;
    text-align: center;

}
 .quien{
    font-size: 2em;
    color: rgb(145, 136, 5);
    align-items: center;
    font-weight: bold;
}

.cualquier{
    font-size: 1em;
    color: rgb(0, 0, 0);
    align-items: center;
    font-weight: bold;
}

.menores{
    color: rgb(0, 0, 0);
    align-items: center;
    font-weight: bold;

}


a{
    color: green;
    text-decoration: none;
    font-weight: bold;
}







