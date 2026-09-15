
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tritech - Estudio de Lubricación Interactivo | Bimbo</title>
    <style>
        :root {
            --primary-color: #003366;
            --accent-color: #ff6600;
            --bg-color: #f4f7f6;
            --card-bg: #ffffff;
            --text-color: #333333;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: var(--card-bg);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }
        header {
            border-bottom: 3px solid var(--accent-color);
            padding-bottom: 15px;
            margin-bottom: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
        }
        header h1 {
            color: var(--primary-color);
            font-size: 24px;
            margin: 0;
        }
        header p {
            margin: 5px 0 0 0;
            color: #666;
            font-size: 14px;
        }
        .badge {
            background-color: var(--accent-color);
            color: white;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: bold;
        }
        /* Barra de búsqueda interactiva */
        .search-bar {
            margin-bottom: 20px;
        }
        .search-bar input {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 8px;
            font-size: 14px;
            box-sizing: border-box;
        }
        .section-title {
            color: var(--primary-color);
            border-left: 4px solid var(--accent-color);
            padding-left: 10px;
            margin-top: 25px;
            margin-bottom: 15px;
            font-size: 18px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 15px;
            margin-bottom: 20px;
        }
        .card-field {
            background: #fafafa;
            border: 1px solid #e0e0e0;
            padding: 12px 15px;
            border-radius: 8px;
        }
        .card-field label {
            display: block;
            font-size: 12px;
            color: #777;
            margin-bottom: 4px;
            text-transform: uppercase;
        }
        .card-field span {
            font-weight: 600;
            color: #222;
            font-size: 14px;
        }
        .alert-box {
            background-color: #fff3cd;
            border: 1px solid #ffeeba;
            color: #856404;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 15px;
        }
        .success-box {
            background-color: #d4edda;
            border: 1px solid #c3e6cb;
            color: #155724;
            padding: 15px;
            border-radius: 8px;
        }
        /* Simulador interactivo */
        .interactive-tool {
            background: #e8f4fd;
            border: 1px solid #bbeecc;
            padding: 15px;
            border-radius: 8px;
            margin-top: 20px;
        }
        .interactive-tool select, .interactive-tool button {
            padding: 8px 12px;
            margin-top: 8px;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 14px;
        }
        .interactive-tool button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            cursor: pointer;
            font-weight: bold;
        }
        .interactive-tool button:hover {
            background-color: #002244;
        }
        ul {
            margin: 0;
            padding-left: 20px;
        }
        li {
            margin-bottom: 8px;
            line-height: 1.5;
        }
        footer {
            margin-top: 30px;
            text-align: center;
            font-size: 12px;
            color: #aaa;
            border-top: 1px solid #eee;
            padding-top: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .btn-action {
            background-color: var(--accent-color);
            color: white;
            border: none;
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <div>
            <h1>Tritech - Lubricación de Alto Rendimiento</h1>
            <p>Estudio de Lubricación AB | Alimentos y Bebidas</p>
        </div>
        <div class="badge">Reporte No. 901593</div>
    </header>

    <!-- Barra de Búsqueda Interactiva -->
    <div class="search-bar">
        <input type="text" id="searchInput" placeholder="🔍 Buscar dentro del reporte (ej. Bimbo, Castrol, 300°C)..." onkeyup="filterReport()">
    </div>

    <div id="reportContent">
        <!-- Información General -->
        <div class="section-title">Datos Generales del Reporte</div>
        <div class="grid">
            <div class="card-field search-item">
                <label>UUID</label>
                <span>1449EB15-DA49-48CE-ACAF-0CF2B0D327E0</span>[span_3](start_span)[span_3](end_span)
            </div>
            <div class="card-field search-item">
                <label>Cliente</label>
                <span>Bimbo de El Salvador, S. A. de C. V.</span>[span_4](start_span)[span_4](end_span)
            </div>
            <div class="card-field search-item">
                <label>Usuario Responsable</label>
                <span>Arevalo, David (darevalo@grupotritech.com)</span>[span_5](start_span)[span_5](end_span)
            </div>
            <div class="card-field search-item">
                <label>Área / Mecanismo</label>
                <span>Elaboración / Rodamientos (Cadenas de Horno)</span>[span_6](start_span)[span_6](end_span)
            </div>
            <div class="card-field search-item">
                <label>Fecha y Hora Inicio / Cierre</label>
                <span>24/08/2026 09:54 - 21:51</span>[span_7](start_span)[span_7](end_span)
            </div>
        </div>

        <!-- Contenido del Reporte -->
        <div class="section-title">Diagnóstico y Hallazgos (Planta BIMBO Merliot)</div>
        <div class="alert-box search-item">
            <strong>Problema Detectado:</strong>
            <ul>
                <li>Visita realizada para levantamiento de datos en la línea de comal de tortillas (cadenas a 300°C, tres niveles)[span_8](start_span)[span_8](end_span).</li>
                <li>Lubricante actual: Aceite <strong>Castrol Obtileb GT</strong> aplicado con sistema automático Quik Lube marca Graco[span_9](start_span)[span_9](end_span).</li>
                <li>El aceite Castrol no soporta los 300°C y se carboniza[span_10](start_span)[span_10](end_span).</li>
                <li>Las cadenas se ponen rígidas por el carbón acumulado, provocando descarrilamientos y paradas de hasta 3 horas (esperando enfriamiento)[span_11](start_span)[span_11](end_span).</li>
                <li>Aplicación temporal correctiva: Aplicación manual de aceite <strong>Sentinel S 1000 HT</strong>[span_12](start_span)[span_12](end_span).</li>
            </ul>
        </div>

        <!-- Recomendaciones e Interactividad -->
        <div class="section-title">Recomendaciones y Siguientes Pasos</div>
        <div class="success-box search-item">
            <strong>Plan de Acción:</strong>
            <ul>
                <li>Se estará presentando propuesta comercial del aceite de alto rendimiento <strong>CASSIDA XTE</strong> especializado para alta temperatura[span_13](start_span)[span_13](end_span).</li>
            </ul>
            
            <!-- Gestor Interactivo de Estado -->
            <div class="interactive-tool">
                <label for="statusSelect"><strong>Estado del Plan de Acción:</strong></label><br>
                <select id="statusSelect" onchange="saveStatus()">
                    <option value="Pendiente">Pendiente de enviar propuesta</option>
                    <option value="Enviado">Propuesta CASSIDA XTE Enviada al Cliente</option>
                    <option value="Aprobado">¡Propuesta Aprobada!</option>
                </select>
                <p id="saveFeedback" style="font-size: 12px; color: #2e7d32; margin-top: 5px; display: none;">✔ Estado guardado localmente.</p>
            </div>
        </div>
    </div>

    <footer>
        <span>Tritech Lubricación de Alto Rendimiento © 2026</span>
        <button class="btn-action" onclick="copySummary()">📋 Copiar Resumen</button>
    </footer>
</div>

<script>
    // Función de Búsqueda Interactiva
    function filterReport() {
        let input = document.getElementById('searchInput').value.toLowerCase();
        let items = document.querySelectorAll('.search-item');
        
        items.forEach(item => {
            let text = item.textContent.toLowerCase();
            if(text.includes(input)) {
                item.style.display = "";
            } else {
                item.style.display = "none";
            }
        });
    }

    // Guardar Estado en LocalStorage
    function saveStatus() {
        let status = document.getElementById('statusSelect').value;
        localStorage.setItem('tritech_status_901593', status);
        let feedback = document.getElementById('saveFeedback');
        feedback.style.display = "block";
        setTimeout(() => { feedback.style.display = "none"; }, 2000);
    }

    // Cargar Estado al abrir la app
    window.onload = function() {
        let savedStatus = localStorage.getItem('tritech_status_901593');
        if(savedStatus) {
            document.getElementById('statusSelect').value = savedStatus;
        }
    }

    // Copiar Resumen Ejecutivo al Portapapeles
    function copySummary() {
        let summaryText = "REPORTE TRITECH - BIMBO DE EL SALVADOR\n" +
                          "Reporte No: 901593\n" +
                          "Problema: Carbonización de aceite Castrol Obtileb GT a 300°C en comal de tortillas, paradas de 3 horas.\n" +
                          "Solución Propuesta: Aceite CASSIDA XTE para alta temperatura.\n" +
                          "Responsable: David Arevalo";
        navigator.clipboard.writeText(summaryText).then(() => {
            alert("¡Resumen copiado al portapapeles con éxito!");
        });
    }
</script>

</body>
</html>
