<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mockup App de Votación Blockchain</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      // CONFIGURACIÓN PARA ACTIVAR EL MODO OSCURO MANUALMENTE
      tailwind.config = {
        darkMode: 'class',
      }
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .animate-fade-in {
            animation: fadeIn 0.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Estilos para Botones 3D */
        .btn-3d {
            position: relative;
            border: none;
            transition: all 0.1s ease-in-out;
            border-bottom-width: 5px;
        }
        .btn-3d:hover {
            transform: translateY(-2px);
            filter: brightness(1.1);
        }
        .btn-3d:active {
            transform: translateY(2px);
            border-bottom-width: 2px;
            filter: brightness(0.9);
        }
        .btn-indigo {
             border-color: #312e81; /* indigo-900 */
        }
        .btn-red {
            border-color: #7f1d1d; /* red-900 */
        }
        .btn-gray {
            border-color: #374151; /* gray-700 */
        }

        /* Animación para el modal */
        .animate-pop-in {
            animation: popIn 0.5s cubic-bezier(0.68, -0.55, 0.27, 1.55) forwards;
        }
        @keyframes popIn {
            0% {
                opacity: 0;
                transform: scale(0.7) translateY(-20px);
            }
            100% {
                opacity: 1;
                transform: scale(1) translateY(0);
            }
        }
        
        /* Estilos para el interruptor de tema */
        #theme-toggle:checked ~ .dot {
            transform: translateX(100%);
        }

        .filter-btn.active {
            --tw-bg-opacity: 1;
            background-color: rgb(79 70 229 / var(--tw-bg-opacity));
            color: white;
            border-color: #312e81;
        }
    </style>
</head>
<body class="bg-gray-100 dark:bg-gray-900 text-gray-800 dark:text-gray-200 transition-colors duration-300">

    <!-- Vista de Login -->
    <div id="login-view" class="min-h-screen flex items-center justify-center p-4 animate-fade-in">
        <div class="w-full max-w-md bg-white dark:bg-gray-800 rounded-2xl shadow-xl p-8">
            <div class="text-center mb-8">
                <h1 class="text-3xl font-bold text-indigo-600 dark:text-indigo-400">Voto Electrónico Ciudadano</h1>
                <p class="text-gray-500 dark:text-gray-400 mt-2">Inicia sesión para participar en la revocatoria.</p>
            </div>
            <form id="login-form">
                <div class="mb-4">
                    <label for="dni" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-2">Documento de Identidad (DNI)</label>
                    <input type="text" id="dni" name="dni" placeholder="Ej: 12345678" class="w-full px-4 py-2 bg-gray-100 dark:bg-gray-700 border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 outline-none transition" required>
                </div>
                <div class="mb-6">
                    <label for="password" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-2">Clave Digital / PIN</label>
                    <input type="password" id="password" name="password" placeholder="••••••••" class="w-full px-4 py-2 bg-gray-100 dark:bg-gray-700 border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 outline-none transition" required>
                </div>
                <button type="submit" class="w-full bg-indigo-600 hover:bg-indigo-500 text-white font-bold py-3 px-4 rounded-lg focus:outline-none focus:ring-4 focus:ring-indigo-300 dark:focus:ring-indigo-800 btn-3d btn-indigo">
                    Ingresar de forma segura
                </button>
            </form>
            <div class="text-center mt-6">
                <a href="#" class="text-sm text-indigo-500 hover:underline">¿Problemas para ingresar?</a>
            </div>
        </div>
    </div>

    <!-- Vista Principal de la App -->
    <div id="dashboard-view" class="hidden min-h-screen animate-fade-in">
        <!-- Header -->
        <header class="bg-white dark:bg-gray-800 shadow-md sticky top-0 z-10">
            <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
                <h1 class="text-2xl font-bold text-indigo-600 dark:text-indigo-400">Portal de Revocatoria</h1>
                <div class="flex items-center space-x-4">
                     <!-- Interruptor de Tema -->
                    <label for="theme-toggle" class="flex items-center cursor-pointer">
                        <div class="relative">
                            <input type="checkbox" id="theme-toggle" class="sr-only">
                            <div class="block bg-gray-200 dark:bg-gray-700 w-14 h-8 rounded-full"></div>
                            <div class="dot absolute left-1 top-1 bg-white dark:bg-indigo-400 w-6 h-6 rounded-full transition-transform"></div>
                        </div>
                    </label>
                    <span class="hidden sm:block font-medium">Bienvenido, Juan Pérez</span>
                    <button id="logout-btn" class="bg-red-600 hover:bg-red-500 text-white font-semibold py-2 px-4 rounded-lg text-sm btn-3d btn-red">
                        Salir
                    </button>
                </div>
            </nav>
        </header>

        <!-- Contenido Principal -->
        <main class="container mx-auto p-4 sm:p-6 lg:p-8">
            <!-- Filtros -->
            <section id="filters" class="mb-8">
                <div class="bg-white dark:bg-gray-800 p-6 rounded-xl shadow-md">
                    <h2 class="text-xl font-semibold mb-4">Filtrar por Nivel</h2>
                    <div class="grid grid-cols-3 gap-4">
                        <button id="filter-regional" class="filter-btn active w-full bg-white dark:bg-gray-700 dark:hover:bg-gray-600 hover:bg-gray-200 font-bold py-3 px-4 rounded-lg focus:outline-none focus:ring-4 focus:ring-indigo-300 dark:focus:ring-indigo-800 btn-3d" style="border-color: #ccc;">
                            Regional
                        </button>
                        <button id="filter-provincial" class="filter-btn w-full bg-white dark:bg-gray-700 dark:hover:bg-gray-600 hover:bg-gray-200 font-bold py-3 px-4 rounded-lg focus:outline-none focus:ring-4 focus:ring-indigo-300 dark:focus:ring-indigo-800 btn-3d" style="border-color: #ccc;">
                            Provincial
                        </button>
                        <button id="filter-distrital" class="filter-btn w-full bg-white dark:bg-gray-700 dark:hover:bg-gray-600 hover:bg-gray-200 font-bold py-3 px-4 rounded-lg focus:outline-none focus:ring-4 focus:ring-indigo-300 dark:focus:ring-indigo-800 btn-3d" style="border-color: #ccc;">
                            Distrital
                        </button>
                    </div>
                </div>
            </section>

            <!-- Lista de Autoridades -->
            <section id="authorities-section">
                <h2 id="authorities-title" class="text-xl font-semibold mb-4"></h2>
                <div id="authorities-list" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
                    <!-- Las tarjetas de autoridad se generarán aquí con JavaScript -->
                </div>
            </section>
        </main>
    </div>

    <!-- Modal de Confirmación -->
    <div id="confirmation-modal" class="fixed inset-0 bg-black bg-opacity-60 flex items-center justify-center p-4 hidden z-50">
        <div class="bg-white dark:bg-gray-800 rounded-2xl shadow-xl p-8 text-center max-w-sm w-full animate-pop-in">
            <div id="modal-content-vote">
                <svg class="w-20 h-20 mx-auto text-green-500 dark:text-green-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                <h3 class="text-2xl font-bold mt-4">¡Voto Registrado!</h3>
                <p class="text-gray-600 dark:text-gray-300 my-2">Tu voto ha sido emitido y registrado de forma segura en la blockchain.</p>
            </div>
             <div id="modal-content-unvote" class="hidden">
                <svg class="w-20 h-20 mx-auto text-amber-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                <h3 class="text-2xl font-bold mt-4">Voto Retirado</h3>
                <p class="text-gray-600 dark:text-gray-300 my-2">Has retirado tu voto para esta autoridad.</p>
            </div>
            <button id="close-modal-btn" class="mt-6 w-full bg-indigo-600 hover:bg-indigo-500 text-white font-bold py-2 px-4 rounded-lg btn-3d btn-indigo">
                Entendido
            </button>
        </div>
    </div>


    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // --- ELEMENTOS DEL DOM ---
            const loginView = document.getElementById('login-view');
            const dashboardView = document.getElementById('dashboard-view');
            const loginForm = document.getElementById('login-form');
            const logoutBtn = document.getElementById('logout-btn');
            const confirmationModal = document.getElementById('confirmation-modal');
            const closeModalBtn = document.getElementById('close-modal-btn');
            const themeToggle = document.getElementById('theme-toggle');
            const htmlEl = document.documentElement;
            const authoritiesListContainer = document.getElementById('authorities-list');
            const authoritiesTitle = document.getElementById('authorities-title');
            const filterButtons = document.querySelectorAll('.filter-btn');
            const modalContentVote = document.getElementById('modal-content-vote');
            const modalContentUnvote = document.getElementById('modal-content-unvote');

            // --- BASE DE DATOS SIMULADA ---
            const authoritiesData = {
                regional: [
                    { id: 'reg-gov', name: 'Luis Gonzales', position: 'Gobernador Regional', currentVotes: 149999, requiredVotes: 150000, isVoted: false, imgInitial: 'LG' },
                    ...Array.from({ length: 7 }, (_, i) => ({ id: `reg-r${i+1}`, name: `Regidor Regional ${i+1}`, position: 'Regidor Regional', currentVotes: Math.floor(Math.random() * 8000), requiredVotes: 10000, isVoted: false, imgInitial: `R${i+1}` }))
                ],
                provincial: [
                    { id: 'pro-may', name: 'Maria Flores', position: 'Alcaldesa Provincial', currentVotes: 15300, requiredVotes: 25000, isVoted: false, imgInitial: 'MF' },
                    ...Array.from({ length: 7 }, (_, i) => ({ id: `pro-r${i+1}`, name: `Regidor Provincial ${i+1}`, position: 'Regidor Provincial', currentVotes: Math.floor(Math.random() * 5000), requiredVotes: 8000, isVoted: false, imgInitial: `R${i+1}` }))
                ],
                distrital: [
                    { id: 'dis-may', name: 'Ana Paredes', position: 'Alcaldesa Distrital', currentVotes: 2450, requiredVotes: 5000, isVoted: false, imgInitial: 'AP' },
                    ...Array.from({ length: 7 }, (_, i) => ({ id: `dis-r${i+1}`, name: `Regidor Distrital ${i+1}`, position: 'Regidor Distrital', currentVotes: Math.floor(Math.random() * 2000), requiredVotes: 2500, isVoted: false, imgInitial: `R${i+1}` }))
                ]
            };

            // --- FUNCIONES ---
            function renderAuthorities(level) {
                authoritiesListContainer.innerHTML = '';
                authoritiesTitle.textContent = `Autoridades de Nivel ${level.charAt(0).toUpperCase() + level.slice(1)}`;
                
                const authorities = authoritiesData[level];
                
                authorities.forEach(auth => {
                    const percentage = Math.round((auth.currentVotes / auth.requiredVotes) * 100);
                    const card = document.createElement('div');
                    card.className = "bg-white dark:bg-gray-800 rounded-xl shadow-lg p-6 flex flex-col items-center text-center transition-transform transform hover:-translate-y-2";
                    card.innerHTML = `
                        <img class="w-24 h-24 rounded-full object-cover mb-4 border-4 border-indigo-200 dark:border-indigo-700" src="https://placehold.co/100x100/E2E8F0/4A5568?text=${auth.imgInitial}" alt="Foto de ${auth.name}">
                        <h3 class="text-lg font-bold">${auth.name}</h3>
                        <p class="text-gray-500 dark:text-gray-400 text-sm">${auth.position}</p>
                        <div class="w-full my-4">
                            <div class="flex justify-between items-center text-sm mb-1">
                                <span>Votos para revocar</span>
                                <span class="font-semibold" id="votes-${auth.id}">${auth.currentVotes.toLocaleString()} / ${auth.requiredVotes.toLocaleString()}</span>
                            </div>
                            <div class="w-full bg-gray-200 dark:bg-gray-700 rounded-full h-2.5">
                                <div id="progress-${auth.id}" class="bg-red-500 h-2.5 rounded-full transition-all duration-500" style="width: ${percentage}%"></div>
                            </div>
                            <p class="text-xs text-gray-500 mt-1">${percentage}% del umbral alcanzado</p>
                        </div>
                        <button data-id="${auth.id}" data-level="${level}" class="vote-btn mt-auto w-full font-bold py-2 px-4 rounded-lg btn-3d ${auth.isVoted ? 'bg-gray-500 hover:bg-gray-400 btn-gray' : 'bg-red-600 hover:bg-red-500 btn-red'}">
                            ${auth.isVoted ? 'Quitar Voto' : 'Votar para Revocar'}
                        </button>
                    `;
                    authoritiesListContainer.appendChild(card);
                });
            }
            
            function handleVote(e) {
                if (!e.target.classList.contains('vote-btn')) return;

                const button = e.target;
                const { id, level } = button.dataset;
                const authority = authoritiesData[level].find(auth => auth.id === id);

                if (authority.isVoted) {
                    authority.currentVotes--;
                    authority.isVoted = false;
                    modalContentVote.classList.add('hidden');
                    modalContentUnvote.classList.remove('hidden');
                } else {
                    authority.currentVotes++;
                    authority.isVoted = true;
                    modalContentVote.classList.remove('hidden');
                    modalContentUnvote.classList.add('hidden');
                }
                
                // Actualizar la UI de la tarjeta específica
                updateCardUI(authority, button);
                confirmationModal.classList.remove('hidden');
            }

            function updateCardUI(authority, button) {
                const percentage = Math.round((authority.currentVotes / authority.requiredVotes) * 100);
                
                // Actualizar contador de votos
                document.getElementById(`votes-${authority.id}`).textContent = `${authority.currentVotes.toLocaleString()} / ${authority.requiredVotes.toLocaleString()}`;
                
                // Actualizar barra de progreso
                const progressBar = document.getElementById(`progress-${authority.id}`);
                progressBar.style.width = `${percentage}%`;
                
                // Actualizar texto y estilo del botón
                button.textContent = authority.isVoted ? 'Quitar Voto' : 'Votar para Revocar';
                button.classList.toggle('bg-red-600', !authority.isVoted);
                button.classList.toggle('hover:bg-red-500', !authority.isVoted);
                button.classList.toggle('btn-red', !authority.isVoted);
                button.classList.toggle('bg-gray-500', authority.isVoted);
                button.classList.toggle('hover:bg-gray-400', authority.isVoted);
                button.classList.toggle('btn-gray', authority.isVoted);
            }

            // --- EVENT LISTENERS ---
            if (localStorage.getItem('theme') === 'dark') {
                htmlEl.classList.add('dark');
                themeToggle.checked = true;
            }
            themeToggle.addEventListener('change', () => {
                htmlEl.classList.toggle('dark');
                localStorage.setItem('theme', htmlEl.classList.contains('dark') ? 'dark' : 'light');
            });

            loginForm.addEventListener('submit', (e) => {
                e.preventDefault();
                loginView.classList.add('hidden');
                dashboardView.classList.remove('hidden');
            });

            logoutBtn.addEventListener('click', () => {
                dashboardView.classList.add('hidden');
                loginView.classList.remove('hidden');
            });

            closeModalBtn.addEventListener('click', () => confirmationModal.classList.add('hidden'));
            confirmationModal.addEventListener('click', (e) => {
                if (e.target === confirmationModal) confirmationModal.classList.add('hidden');
            });

            filterButtons.forEach(button => {
                button.addEventListener('click', () => {
                    filterButtons.forEach(btn => btn.classList.remove('active'));
                    button.classList.add('active');
                    const level = button.id.split('-')[1];
                    renderAuthorities(level);
                });
            });

            authoritiesListContainer.addEventListener('click', handleVote);

            // --- INICIALIZACIÓN ---
            renderAuthorities('regional');
        });
    </script>

</body>
</html>

