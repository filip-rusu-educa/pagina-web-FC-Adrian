<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Compra de Entradas de Fútbol</title>
    <link rel="stylesheet" href="styles.css">
 <script>
        // Función que muestra un mensaje de compra exitosa
        function notificarCompra(evento) {
            const partido = evento.target.getAttribute('data-partido');
            alert(`¡Compra efectiva! Entrada para el partido "${partido}" ha sido adquirida.`);
        }
    </script>
</head>
<body>

<header>
    <h1>Compra Entradas para los Partidos de Fútbol</h1>
</header>

<div class="container">
    <!-- Eventos de fútbol -->
    <h2>Partidos de la Semana</h2>
    <div class="event-card">
        <div class="event-details">
            <h3>Real Madrid vs Barcelona</h3>
            <p>Estadio: Santiago Bernabéu</p>
            <p>Fecha: 1 de Diciembre, 2024</p>
        </div>
        <div class="event-price">
            <p>€90</p>
            <button data-partido="Real Madrid vs Barcelona" onclick="notificarCompra(event)">Comprar Entrada</button>
        </div>
    </div>

    <div class="event-card">
        <div class="event-details">
            <h3>Atlético de Madrid vs Sevilla</h3>
            <p>Estadio: Wanda Metropolitano</p>
            <p>Fecha: 2 de Diciembre, 2024</p>
        </div>
        <div class="event-price">
            <p>€75</p>
            <button data-partido="Atlético de Madrid vs Sevilla" onclick="notificarCompra(event)">Comprar Entrada</button>
        </div>
    </div>

    <div class="event-card">
        <div class="event-details">
            <h3>FC Barcelona vs Real Sociedad</h3>
            <p>Estadio: Camp Nou</p>
            <p>Fecha: 3 de Diciembre, 2024</p>
        </div>
        <div class="event-price">
            <p>€85</p>
            <button data-partido="FC Barcelona vs Real Sociedad" onclick="notificarCompra(event)">Comprar Entrada</button>
        </div>
    </div>

    <div class="event-card">
        <div class="event-details">
            <h3>Milan vs Juventus</h3>
            <p>Estadio: San Siro</p>
            <p>Fecha: 4 de Diciembre, 2024</p>
        </div>
        <div class="event-price">
            <p>€100</p>
            <button data-partido="Milan vs Juventus" onclick="notificarCompra(event)">Comprar Entrada</button>
        </div>
    </div>

    <div class="event-card">
        <div class="event-details">
            <h3>Chelsea vs Manchester United</h3>
            <p>Estadio: Stamford Bridge</p>
            <p>Fecha: 5 de Diciembre, 2024</p>
        </div>
        <div class="event-price">
            <p>€95</p>
            <button data-partido="Chelsea vs Manchester United" onclick="notificarCompra(event)">Comprar Entrada</button>
        </div>
    </div>
</div>

<footer>
    <p>Visita las páginas oficiales de los equipos:</p>
    <a href="https://www.realmadrid.com" target="_blank">Real Madrid</a>
    <a href="https://www.fcbarcelona.com" target="_blank">FCBarcelona</a>
    <a href="https://www.acmilan.com" target="_blank">MilanFC</a>
    <a href="https://www.chelseafc.com" target="_blank">ChelseaFC</a>
    <a href="https://www.sevillafc.es" target="_blank">SevillaFC</a>
    <a href="https://www.atleticodemadrid.com" target="_blank">Atlético de Madrid</a>
</footer>

</body>
</html>
