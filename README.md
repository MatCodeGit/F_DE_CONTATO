# F_DE_CONTATO
Com CSS
<!DOCTYPE html>
<html lang="en">
<head> <link rel="stylesheet" href="speed2.CSS">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contato</title>
</head>
<body>
    <div class="container">
    <h1>Formulario de contato</h1>
    <input id="nome" class="campo" type="text" placeholder="Nome do contato">
    <input id="email" class="campo" type="email" placeholder="E-mail do contato">
    <button>Enviar</button>


    =======================================================================================================================
    *{
    margin: 0;
    padding: 0;
}
body{
    width: 100vw;
    height: 100vw;
    display: grid;
    align-items: center;
    justify-content: center;
}
.container{
    border: 1px solid rgb(2, 2, 2); 
    width: 600px;
    height: 500px;
    display: grid;
    grid-template-rows: 1fr 0,5tr 0,5fr 0,5fr;
    background-color:cadetblue ;
    border-radius: 10px;
    overflow: hidden;
}
.container h1{
    text-align: center;
    color:black;

}
button:hover{
    background-color: green;
    transition: 2s;    
}
