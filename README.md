<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dev Menthors</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<section class="one">
    <div class="topo">
        <div ><img src="image.png" class="image" alt="imagem"></div>
        <div class="sobre">
            <a href="">Home</a>
            <a href="">Sobre</a>
            <a href="">Blog</a>
        </div>
        <button class="button">Login</button>
        
    </div>

    <div class="meio">
        <div class="titulo"><h1 style="position: relative; margin: 0px;">Dev <br>Menthors</h1> <h2 style="padding: 0px; margin: 0px; text-align: right;">Unimar</h2> </div>
        
        <img src="image copy.png" class="imagem2">
    </div>
    </section>
    
    <section>
        <div class="two"><h1 class="inicie">Inicie sua história na área da tecnologia com  Dev</h1>
        <p class="trila">um pouco de cada uma das trilhas disponíveis.</p>
        </div>
    </section>
</body>
</html>







body{
    padding: 15px;
}

.topo{
    justify-content: space-between;
    align-items: center;
    display: flex;
}

.meio{
    justify-content: space-between;
    display: flex;
}

.login{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
button{

    padding: 10px;
    background-color: #3C96FF;
    color: white;
    border: none;
    font-size: 15px ;
    border-radius: 10px;
    width: 100px;
}

.image{
    width: 30px;
    height: 30px;   

}
.imagem2{
    margin-right: 100px;
    width: 500px;
    height: 600x;   

}

.titulo{
    margin-top: 100px;
    margin-left: 120px;
    font-size: 70px;
    color: #2B2B33;

}
C:\Users\Aula\Downloads\aula\image copy.png
C:\Users\Aula\Downloads\aula\image.png
.sobre{
    justify-content: space-between;
    display: flex;
    gap: 50px;
}
.two{
    justify-content: center;
    display: block;
    align-items: center;
}

a{
    color: black;
    text-decoration: none;
    font-family: Arial, Helvetica, sans-serif;
}
h2{
    font-style: none;
    font-size: 40px;
    margin-left: 0px;
    font-size: 50px;
}
.inicie{
    font-size: 30px;
    align-items: center;
    justify-content: center;
}
.trila{
    font-size: 30px;
}
