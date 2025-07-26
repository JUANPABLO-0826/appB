<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Insight - Boyacá y Cundinamarca</title>
    <style>
        /* --- ESTILOS GENERALES --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            color: #333;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 40px;
            color: white;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* --- ESTRUCTURA PRINCIPAL --- */
        .main-content {
            display: grid;
            grid-template-columns: 1fr 2.5fr; /* Dando más espacio al contenido */
            gap: 30px;
            margin-bottom: 40px;
        }

        .sidebar, .content-area {
            background: rgba(255, 255, 255, 0.98);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 8px 32px rgba(0,0,0,0.1);
            backdrop-filter: blur(10px);
        }

        .sidebar {
             height: fit-content;
        }

        /* --- SECCIONES Y FORMULARIOS --- */
        .search-section, .form-section {
            margin-bottom: 25px;
        }
        
        .form-section {
            border-top: 2px solid #e2e8f0;
            padding-top: 20px;
        }

        h2 {
            color: #4a5568;
            margin-bottom: 15px;
            font-size: 1.3rem;
        }

        .search-form, .travel-form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
        }

        label {
            margin-bottom: 5px;
            font-weight: 600;
            color: #2d3748;
        }

        input, select {
            padding: 12px;
            border: 2px solid #e2e8f0;
            border-radius: 8px;
            font-size: 14px;
            transition: all 0.3s ease;
            background-color: white;
        }

        input:focus, select:focus {
            outline: none;
            border-color: #667eea;
            box-shadow: 0 0 10px rgba(102, 126, 234, 0.2);
        }

        .btn {
            background: linear-gradient(135deg, #667eea, #764ba2);
            color: white;
            border: none;
            padding: 12px 24px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s ease;
            font-size: 14px;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
        }

        /* --- RESULTADOS Y TARJETAS --- */
        .results-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .result-card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            transition: all 0.3s ease;
            border: 1px solid #e2e8f0;
            display: flex;
            flex-direction: column;
        }

        .result-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.12);
        }

        .card-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 15px;
        }

        .card-title {
            font-weight: 700;
            color: #2d3748;
            font-size: 1.1rem;
            margin-bottom: 5px;
        }

        .card-subtitle {
            color: #718096;
            font-size: 0.9rem;
        }

        .card-info {
            display: flex;
            flex-direction: column;
            gap: 10px; /* Más espacio entre items */
            flex-grow: 1; /* Permite que la tarjeta crezca */
        }

        .info-item {
            display: flex;
            align-items: center;
            gap: 8px;
            font-size: 0.9rem;
        }

        .icon {
            width: 16px;
            height: 16px;
            fill: #667eea;
            flex-shrink: 0;
        }

        /* --- ESTADÍSTICAS --- */
        .stats-section {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            margin-top: 20px;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin-top: 15px;
        }

        .stat-item {
            text-align: center;
            padding: 15px;
            background: #f7fafc;
            border-radius: 8px;
        }

        .stat-number {
            font-size: 2rem;
            font-weight: 700;
            color: #667eea;
        }

        .stat-label {
            color: #718096;
            font-size: 0.9rem;
            margin-top: 5px;
        }

        #top-municipios-list {
            list-style-position: inside;
            text-align: left;
            margin-top: 10px;
            padding-left: 10px;
        }
        
        #top-municipios-list li {
            padding: 5px;
            border-bottom: 1px solid #eee;
        }

        /* --- ESTADOS Y MENSAJES --- */
        .loading, .empty-state {
            text-align: center;
            padding: 40px;
            color: #718096;
        }

        .spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid #667eea;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 1s linear infinite;
            margin: 0 auto 15px;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .error, #form-message {
            padding: 15px;
            border-radius: 8px;
            margin: 15px 0;
            text-align: center;
        }
        
        .error, #form-message.error {
            background: #fed7d7;
            color: #c53030;
        }
        
        #form-message {
            display: none; /* Oculto por defecto */
        }
        #form-message.success {
            background-color: #c6f6d5;
            color: #22543d;
        }

        .category-badge {
            background: #e2e8f0;
            color: #4a5568;
            padding: 4px 8px;
            border-radius: 12px;
            font-size: 0.8rem;
            font-weight: 500;
        }

        .status-badge {
            padding: 4px 10px;
            border-radius: 12px;
            font-size: 0.8rem;
            font-weight: 600;
            align-self: flex-start;
        }

        .status-active {
            background: #c6f6d5;
            color: #22543d;
        }

        .status-inactive {
            background: #fed7d7;
            color: #c53030;
        }

        /* --- RESPONSIVE DESIGN --- */
        @media (max-width: 992px) {
            .main-content {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            .results-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🌄 Travel Insight</h1>
            <p class="subtitle">Conectando viajeros con Boyacá y Cundinamarca</p>
        </header>

        <div class="main-content">
            <aside class="sidebar">
                <div class="search-section">
                    <h2>🔍 Buscar Destinos</h2>
                    <div id="search-form" class="search-form">
                        <div class="form-group">
                            <label for="municipio">Municipio:</label>
                            <input type="text" id="municipio" list="municipios-list" placeholder="Ej: Tunja, Chía, Girardot...">
                            <datalist id="municipios-list"></datalist>
                        </div>
                        
                        <div class="form-group">
                            <label for="categoria">Categoría:</label>
                            <select id="categoria">
                                <option value="">Todas las categorías</option>
                            </select>
                        </div>
                        
                        <button class="btn" id="search-button">Buscar</button>
                        <button class="btn" id="clear-button" style="background: #e2e8f0; color: #4a5568;">Limpiar Filtros</button>
                    </div>
                </div>

                <div class="form-section">
                    <h2>📝 Planifica tu Viaje</h2>
                    <form id="travel-form" class="travel-form">
                        <div class="form-group">
                            <label for="viajas_con">¿Con quién viajas?</label>
                            <select id="viajas_con" name="viajas_con">
                                <option value="Solo">Solo</option>
                                <option value="Pareja">Pareja</option>
                                <option value="Familia">Familia</option>
                                <option value="Amigos">Amigos</option>
                                <option value="Negocios">Negocios</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="interes_viaje">Interés principal:</label>
                            <select id="interes_viaje" name="interes_viaje">
                                <option value="Naturaleza">Naturaleza</option>
                                <option value="Historia-Cultura">Historia-Cultura</option>
                                <option value="Gastronomia">Gastronomía</option>
                                <option value="Relajacion">Relajación</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="duracion_viaje">Duración del viaje:</label>
                            <select id="duracion_viaje" name="duracion_viaje">
                                <option value="Escapada de Fin de Semana (1-3 días)">Fin de Semana (1-3 días)</option>
                                <option value="Vacaciones Cortas (4-7 días)">Vacaciones Cortas (4-7 días)</option>
                                <option value="Vacaciones Largas (Más de 7 días)">Vacaciones Largas (+7 días)</option>
                            </select>
                        </div>
                        <div class="form-group">
                            <label for="clima_preferencia">Clima de preferencia:</label>
                            <select id="clima_preferencia" name="clima_preferencia">
                                <option value="Clima Cálido (Tierra caliente)">Cálido</option>
                                <option value="Clima Templado (Tierra templada, Bogotá/Duitama)">Templado</option>
                                <option value="Clima Frío (Páramo, alta montaña)">Frío</option>
                                <option value="No tengo preferencia">Indiferente</option>
                            </select>
                        </div>
                        <button type="submit" class="btn">Enviar Preferencias</button>
                        <div id="form-message"></div>
                    </form>
                </div>
            </aside>

            <main class="content-area">
                <section class="results-section">
                    <h2>🏨 Establecimientos Turísticos</h2>
                    <div id="results-container">
                        <div class="empty-state">
                            <p>Usa los filtros para encontrar tu próximo destino.</p>
                        </div>
                    </div>
                </section>

                <section class="stats-section">
                    <h2>📊 Estadísticas</h2>
                     <div id="top-municipios-container" class="stat-item" style="grid-column: 1 / -1; text-align: left; padding: 20px;">
                        <h3 style="text-align: center; margin-bottom: 10px;">🏆 Top 5 Municipios con más registros</h3>
                        <div id="top-municipios-content">
                            <div class="spinner"></div>
                        </div>
                    </div>
                    <div class="stats-grid" id="stats-container">
                        <div class="stat-item">
                            <div class="stat-number" id="total-results">0</div>
                            <div class="stat-label">Total Encontrados</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number" id="hoteles-count">0</div>
                            <div class="stat-label">Hoteles</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number" id="agencias-count">0</div>
                            <div class="stat-label">Agencias</div>
                        </div>
                        <div class="stat-item">
                            <div class="stat-number" id="otros-count">0</div>
                            <div class="stat-label">Otros Servicios</div>
                        </div>
                    </div>
                </section>
            </main>
        </div>
    </div>

    <script>
        // --- CONFIGURACIÓN Y VARIABLES GLOBALES ---
        const API_BASE_URL = 'https://travelinsight.onrender.com/api';

        // --- INICIALIZACIÓN DE LA APLICACIÓN ---
        document.addEventListener('DOMContentLoaded', initializeApp);

        async function initializeApp() {
            setupEventListeners();
            // Cargar datos para los menús desplegables y las estadísticas
            await Promise.all([
                populateDropdowns(),
                loadTopMunicipios(),
                loadInitialData() // Cargar los primeros 10 destinos
            ]);
        }
        
        function setupEventListeners() {
            document.getElementById('search-button').addEventListener('click', buscarEstablecimientos);
            document.getElementById('clear-button').addEventListener('click', limpiarBusqueda);
            document.getElementById('travel-form').addEventListener('submit', handleFormSubmit);
        }

        // --- FUNCIONES DE CARGA DE DATOS (API) ---

        /**
         * CORRECCIÓN: Carga los primeros 10 destinos por defecto al iniciar.
         * Ya no carga toda la base de datos en memoria.
         */
        async function loadInitialData() {
            showLoading("Cargando destinos iniciales...");
            try {
                const response = await fetch(`${API_BASE_URL}/destinos`);
                if (!response.ok) throw new Error(`Error HTTP: ${response.status}`);
                const data = await response.json();
                displayResults(data);
                updateStats(data);
            } catch (error) {
                console.error('Error al cargar datos iniciales:', error);
                showError(`No se pudieron cargar los destinos: ${error.message}`);
            }
        }

        /**
         * CORRECCIÓN: Esta es la función principal y ha sido reescrita por completo.
         * Ahora construye la URL de la API dinámicamente basada en los filtros
         * y le pide los datos filtrados al servidor, en lugar de hacerlo en el navegador.
         */
        async function buscarEstablecimientos() {
            const municipio = document.getElementById('municipio').value.trim();
            const categoria = document.getElementById('categoria').value;
            
            let url = '';
            
            // Lógica para construir la URL correcta según los filtros
            if (municipio && categoria) {
                url = `${API_BASE_URL}/filtrar?municipio=${encodeURIComponent(municipio)}&categoria=${encodeURIComponent(categoria)}`;
            } else if (municipio) {
                url = `${API_BASE_URL}/destinos/${encodeURIComponent(municipio)}`;
            } else if (categoria) {
                url = `${API_BASE_URL}/categoria/${encodeURIComponent(categoria)}`;
            } else {
                // Si no hay filtros, muestra los 10 destinos iniciales de nuevo.
                url = `${API_BASE_URL}/destinos`;
            }

            showLoading("Buscando destinos...");

            try {
                const response = await fetch(url);
                if (!response.ok) {
                    const errorData = await response.json().catch(() => null);
                    throw new Error(errorData?.error || `Error del servidor: ${response.status}`);
                }
                const data = await response.json();
                displayResults(data);
                updateStats(data);
            } catch (error) {
                console.error('Error en la búsqueda:', error);
                showError(`Ocurrió un error al buscar: ${error.message}`);
                updateStats([]); // Reinicia las estadísticas en caso de error
            }
        }

        async function populateDropdowns() {
            // Cargar Municipios
            try {
                const response = await fetch(`${API_BASE_URL}/municipios`);
                if (!response.ok) throw new Error('No se pudieron cargar los municipios.');
                const municipios = await response.json();
                document.getElementById('municipios-list').innerHTML = municipios.map(m => `<option value="${m}"></option>`).join('');
            } catch (error) {
                console.error('Error al poblar municipios:', error);
            }

            // Cargar Categorías
            try {
                const response = await fetch(`${API_BASE_URL}/categorias`);
                if (!response.ok) throw new Error('No se pudieron cargar las categorías.');
                const categorias = await response.json();
                const categoriaSelect = document.getElementById('categoria');
                // Limpiamos opciones viejas, excepto la primera ("Todas las categorías")
                categoriaSelect.innerHTML = '<option value="">Todas las categorías</option>';
                categoriaSelect.innerHTML += categorias.map(c => `<option value="${c}">${c}</option>`).join('');
            } catch (error) {
                console.error('Error al poblar categorías:', error);
            }
        }

        async function loadTopMunicipios() {
            const container = document.getElementById('top-municipios-content');
            try {
                const response = await fetch(`${API_BASE_URL}/top-municipios`);
                if (!response.ok) throw new Error('No se pudo cargar el top 5.');
                const topMunicipiosData = await response.json();
                
                // CORRECCIÓN: La API devuelve un objeto, lo convertimos a un array para mostrarlo.
                const listHTML = Object.entries(topMunicipiosData)
                    .map(([municipio, count]) => `<li><strong>${municipio}</strong>: ${count} registros</li>`)
                    .join('');
                
                container.innerHTML = `<ol id="top-municipios-list">${listHTML}</ol>`;
            } catch (error) {
                console.error('Error al cargar top municipios:', error);
                container.innerHTML = `<p class="error" style="margin:0; text-align:center;">${error.message}</p>`;
            }
        }

        async function handleFormSubmit(event) {
            event.preventDefault();
            const form = event.target;
            const messageDiv = document.getElementById('form-message');
            const submitButton = form.querySelector('button[type="submit"]');
            
            const formData = new FormData(form);
            const data = Object.fromEntries(formData.entries());

            submitButton.disabled = true;
            submitButton.textContent = 'Enviando...';
            
            try {
                const response = await fetch(`${API_BASE_URL}/formulario`, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(data),
                });

                const result = await response.json();

                if (!response.ok) {
                    throw new Error(result.error || 'Error en el servidor');
                }
                
                // CORRECCIÓN: Se busca la propiedad "mensaje" en la respuesta, como define la API.
                messageDiv.textContent = result.mensaje || '¡Preferencias guardadas con éxito!';
                messageDiv.className = 'success';
                messageDiv.style.display = 'block';
                form.reset();

            } catch (error) {
                messageDiv.textContent = `Error: ${error.message}`;
                messageDiv.className = 'error';
                messageDiv.style.display = 'block';
            } finally {
                submitButton.disabled = false;
                submitButton.textContent = 'Enviar Preferencias';
                setTimeout(() => {
                    messageDiv.style.display = 'none';
                }, 5000);
            }
        }
        
        function limpiarBusqueda() {
            document.getElementById('municipio').value = '';
            document.getElementById('categoria').value = '';
            loadInitialData(); // Vuelve a cargar los datos iniciales
        }

        // --- FUNCIONES DE RENDERIZADO Y UI ---

        function displayResults(data) {
            const container = document.getElementById('results-container');
            if (!data || data.length === 0) {
                container.innerHTML = '<div class="empty-state"><p>No se encontraron establecimientos con los criterios seleccionados.</p></div>';
                return;
            }

            // CORRECCIÓN: Se limita la visualización a 150 resultados para no sobrecargar el navegador.
            const dataToShow = data.slice(0, 150);
            const resultsHTML = dataToShow.map(item => {
                const email = item.CORREO_ESTABLECIMIENTO ? item.CORREO_ESTABLECIMIENTO.split(';')[0].toLowerCase() : '';
                return `
                <div class="result-card">
                    <div class="card-header">
                        <div>
                            <div class="card-title">${item.RAZON_SOCIAL_ESTABLECIMIENTO || 'Sin nombre'}</div>
                            <div class="card-subtitle">${item.CATEGORIA || 'Categoría no especificada'}</div>
                        </div>
                        <span class="status-badge ${item.ESTADO_RNT === 'ACTIVO' ? 'status-active' : 'status-inactive'}">${item.ESTADO_RNT || 'Sin estado'}</span>
                    </div>
                    <div class="card-info">
                        <div class="info-item">
                            <svg class="icon" viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
                            <span>${item.MUNICIPIO || 'N/A'}, ${item.DEPARTAMENTO || 'N/A'}</span>
                        </div>
                        <div class="info-item">
                             <svg class="icon" viewBox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z"/></svg>
                            <span class="category-badge">${item.SUB_CATEGORIA || 'Tipo no especificado'}</span>
                        </div>
                        ${item.HABITACIONES && parseInt(item.HABITACIONES) > 0 ? `<div class="info-item"><svg class="icon" viewBox="0 0 24 24"><path d="M7 14c1.66 0 3-1.34 3-3S8.66 8 7 8s-3 1.34-3 3 1.34 3 3 3zm0-4c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zm12-3h-8v8h8V7zm-2 6h-4V9h4v4z"/></svg><span>${item.HABITACIONES} habs.</span></div>` : ''}
                        ${item.CAMAS && parseInt(item.CAMAS) > 0 ? `<div class="info-item"><svg class="icon" viewBox="0 0 24 24"><path d="M21 10.78V8c0-1.65-1.35-3-3-3h-4c-.77 0-1.47.3-2 .78-.53-.48-1.23-.78-2-.78H6C4.35 5 3 6.35 3 8v2.78c-.61.55-1 1.34-1 2.22v6h2v-2h16v2h2v-6c0-.88-.39-1.67-1-2.22z"/></svg><span>${item.CAMAS} camas</span></div>` : ''}
                        ${email ? `<div class="info-item"><svg class="icon" viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg><span style="font-size: 0.8rem; word-break: break-all;">${email}</span></div>` : ''}
                        <div class="info-item">
                            <svg class="icon" viewBox="0 0 24 24"><path d="M9 11H7v2h2v-2zm4 0h-2v2h2v-2zm4 0h-2v2h2v-2zm2-7h-1V2h-2v2H8V2H6v2H5c-1.1 0-1.99.9-1.99 2L3 20c0 1.1.89 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.08-.9-2-2-2zm0 16H5V9h14v11z"/></svg>
                            <span>RNT: ${item.CODIGO_RNT || 'N/A'}</span>
                        </div>
                    </div>
                </div>
            `}).join('');
            container.innerHTML = `<div class="results-grid">${resultsHTML}</div>${data.length > 150 ? `<p style="text-align: center; margin-top: 20px; color: #718096;">Mostrando los primeros 150 de ${data.length} resultados.</p>` : ''}`;
        }

        function updateStats(data) {
            const dataLength = data ? data.length : 0;
            document.getElementById('total-results').textContent = dataLength;
            if (dataLength === 0) {
                document.getElementById('hoteles-count').textContent = 0;
                document.getElementById('agencias-count').textContent = 0;
                document.getElementById('otros-count').textContent = 0;
                return;
            }
            const hoteles = data.filter(item => item.SUB_CATEGORIA && item.SUB_CATEGORIA.toUpperCase().includes('HOTEL')).length;
            const agencias = data.filter(item => item.CATEGORIA && item.CATEGORIA.includes('AGENCIAS DE VIAJES')).length;
            const otros = dataLength - hoteles - agencias;
            document.getElementById('hoteles-count').textContent = hoteles;
            document.getElementById('agencias-count').textContent = agencias;
            document.getElementById('otros-count').textContent = otros > 0 ? otros : 0;
        }

        function showLoading(message = "Cargando...") {
            document.getElementById('results-container').innerHTML = `<div class="loading"><div class="spinner"></div><p>${message}</p></div>`;
        }

        function showError(message) {
            document.getElementById('results-container').innerHTML = `<div class="error"><strong>Error:</strong> ${message}</div>`;
        }
    </script>
</body>
</html>
