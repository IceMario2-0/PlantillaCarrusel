<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carrusel De Personajes de Videojuegos</title>
    <link rel="stylesheet" href="/animacion.css">
</head>
<body>
<style>
    .carrusel{
        display: flex;
        flex-wrap: nowrap;
        overflow: scroll;
        height: 100vh;
    width: 100%;
    background: linear-gradient(45deg,#000000, #ff0e0e,#00ffc8,#0019fb );
    background-size: 300% 300%;
    animation: color 11s ease-in-out infinite;
    
    }
       
    
    h2{
        color: black;
        text-align: center;
    }
    
    .figura{
        flex: 1 0 auto;
        margin: 0 50px;
        width: 500px; 
        height: 500px;
    }
    
    
    
    @keyframes color{
        0%{
            background-position: 0 50%;
        }
        50%{
            background-position: 100% 50%;
        }
    
        100%{
            background-position: 0 50%;
        }
     
    }
    
   </style>
   
    <div class="carrusel">
        <div class="figura"><img src="./img/WhatsApp Image 2024-11-05 at 22.55.45 (1).jpeg" width="395" ><h2>Megaman X</h2></div>
        <div class="figura"><img src="./img/WhatsApp Image 2024-11-05 at 22.55.45.jpeg" width="500" ><h2>Mario</h2></div>
        <div class="figura"><img src="./img/WhatsApp Image 2024-11-05 at 22.55.46.jpeg" width="551" ><h2>Sonic The Hedgehog</h2></div>
        <div class="figura"><img src="./img/hollow_knight_fanart_by_tomlenook_dft9r85-pre.jpg" width="415"><h2>Hollow Knight</h2></div>
        <div class="figura"><img src="./img/tumblr_00e1d54a7c779601ca8ea1170d115bb9_54c9ce58_1280.jpg" width="449" ><h2>Kratos</h2></div>
        <div class="figura"><img src="./img/halo___master_chief_by_gc_conceptart_df2khjv-414w-2x.jpg" width="445"><h2>Master Chief</h2></div>
        <div class="figura"><img src="./img/04me4pfedbi51.png" width="480"><h2>Doom Slayer</h2></div>
        <div class="figura"><img src="./img/WhatsApp Image 2024-11-05 at 22.55.46 (1).jpeg" width="410"><h2>Mythra</h2></div>
    </div>

    <div class="BG"></div>
</body>
</html>
