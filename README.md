<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ofertas de Frutas y Verduras</title>
    <style>
        body {
            background-color: green;
            color: black;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #006400;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            color: white;
            margin: 0;
        }
        h2 {
            text-align: center;
            color: white;
            font-size: 24px;
        }
        .container {
            padding: 20px;
        }
        .oferta {
            margin: 15px 0;
            padding: 10px;
            background-color: white;
            color: black;
            border-radius: 5px;
        }
        .frutas, .verduras {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .fruta, .verdura {
            background-color: white;
            color: black;
            padding: 10px;
            margin: 10px;
            border-radius: 5px;
            width: 200px;
            text-align: center;
        }
        .fruta:hover, .verdura:hover {
            background-color: #f1f1f1;
        }
        .oferta .precio {
            font-size: 18px;
            color: green;
            font-weight: bold;
        }
        .oferta .descuento {
            font-size: 16px;
            color: red;
            font-weight: bold;
        }
        .boton-regreso {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #006400;
            color: white;
            text-align: center;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            text-decoration: none;
        }
        .boton-regreso:hover {
            background-color: #004d00;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ofertas de Frutas y Verduras en Línea</h1>
    </header>

    <div class="container">
        <h2>Frutas en Oferta</h2>
        <div class="frutas">
            <div class="fruta oferta">
                <p>Manzanas</p>
                <p class="precio">$20.00/kg</p>
                <p class="descuento">¡Oferta! 15% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Plátanos</p>
                <p class="precio">$15.00/kg</p>
                <p class="descuento">¡Oferta! 10% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Fresas</p>
                <p class="precio">$40.00/kg</p>
                <p class="descuento">¡Oferta! 20% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Ciruela</p>
                <p class="precio">$35.00/kg</p>
                <p class="descuento">¡Oferta! 25% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Durazno</p>
                <p class="precio">$45.00/kg</p>
                <p class="descuento">¡Oferta! 5% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Granada Roja</p>
                <p class="precio">$50.00/kg</p>
                <p class="descuento">¡Oferta! 10% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Limón</p>
                <p class="precio">$12.00/kg</p>
                <p class="descuento">¡Oferta! 30% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Mango</p>
                <p class="precio">$60.00/kg</p>
                <p class="descuento">¡Oferta! 10% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Melón</p>
                <p class="precio">$30.00/kg</p>
                <p class="descuento">¡Oferta! 15% descuento</p>
            </div>
            <div class="fruta oferta">
                <p>Piña</p>
                <p class="precio">$25.00/kg</p>
                <p class="descuento">¡Oferta! 20% descuento</p>
            </div>
         
        </div>

        <h2>Verduras en Oferta</h2>
        <div class="verduras">
            <div class="verdura oferta">
                <p>Lechuga</p>
                <p class="precio">$10.00/kg</p>
                <p class="descuento">¡Oferta! 5% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Tomates</p>
                <p class="precio">$12.00/kg</p>
                <p class="descuento">¡Oferta! 15% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Zanahorias</p>
                <p class="precio">$15.00/kg</p>
                <p class="descuento">¡Oferta! 10% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Acelga</p>
                <p class="precio">$18.00/kg</p>
                <p class="descuento">¡Oferta! 20% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Ajo</p>
                <p class="precio">$22.00/kg</p>
                <p class="descuento">¡Oferta! 25% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Apio</p>
                <p class="precio">$12.00/kg</p>
                <p class="descuento">¡Oferta! 10% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Brócoli</p>
                <p class="precio">$28.00/kg</p>
                <p class="descuento">¡Oferta! 5% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Cebolla</p>
                <p class="precio">$8.00/kg</p>
                <p class="descuento">¡Oferta! 18% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Coliflor</p>
                <p class="precio">$30.00/kg</p>
                <p class="descuento">¡Oferta! 12% descuento</p>
            </div>
            <div class="verdura oferta">
                <p>Espinaca</p>
                <p class="precio">$20.00/kg</p>
                <p class="descuento">¡Oferta! 10% descuento</p>
            </div>
           
        </div>

        <a href="#" class="boton-regreso">Regresar al Inicio</a>
    </div>
</body>
</html>