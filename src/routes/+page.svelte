<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gepi Global Hub - Apps Inteligentes para el Futuro</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-bg: #0a0a0a;
            --secondary-bg: #111111;
            --card-bg: #1a1a1a;
            --text-color: #e2e8f0;
            --primary-accent: #6366f1;
            --secondary-accent: #8b5cf6;
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--primary-bg);
            color: var(--text-color);
        }
        h1, h2, h3 { font-family: 'Plus Jakarta Sans', sans-serif; color: white; }
        .hover-card {
            transition: transform 0.35s cubic-bezier(0.4,0,0.2,1), box-shadow 0.35s cubic-bezier(0.4,0,0.2,1);
        }
        .hover-card:hover {
            transform: translateY(-12px) scale(1.03);
            box-shadow: 0 25px 50px rgba(0,0,0,0.3);
        }
        .gradient-text {
            background: linear-gradient(90deg, var(--primary-accent), var(--secondary-accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #1f1f2b, #2c2252);
        }
        .fade-in { animation: fadeIn 1s ease forwards; opacity: 0; }
        @keyframes fadeIn { to { opacity: 1; } }
        .delay-200 { animation-delay: 0.2s; }
        .delay-400 { animation-delay: 0.4s; }
        .delay-600 { animation-delay: 0.6s; }
        .particles {
            position: absolute; width: 100%; height: 100%; top: 0; left: 0;
            background: url('https://www.transparenttextures.com/patterns/cubes.png');
            opacity: 0.05; pointer-events: none;
        }
    </style>
</head>
<body class="antialiased relative">

<section class="gradient-bg py-48 text-center relative overflow-hidden">
    <div class="particles"></div>
    <div class="container mx-auto px-6 max-w-5xl relative z-10">
        <h1 class="text-5xl md:text-7xl font-extrabold mb-6 fade-in">
            Llevamos tus ideas al futuro con <span class="gradient-text">Apps Inteligentes</span>
        </h1>
        <p class="text-xl md:text-2xl mb-10 text-gray-300 fade-in delay-200 max-w-3xl mx-auto">
            Gepi Global Hub es el motor de innovación para tu próximo proyecto, diseñando y construyendo aplicaciones móviles inteligentes que superan expectativas.
        </p>
        <a href="#contact" class="inline-block bg-white text-gray-900 font-bold px-12 py-4 rounded-full shadow-lg hover:bg-gray-200 transition fade-in delay-400 transform hover:scale-110">
            Transforma tu idea ahora
        </a>
    </div>
</section>

<section class="py-28 bg-gray-950 text-center">
    <div class="container mx-auto px-6">
        <h2 class="text-4xl md:text-5xl font-bold mb-16 fade-in">Nuestro Enfoque</h2>
        <div class="grid md:grid-cols-3 gap-12">
            <div class="bg-gray-800 p-10 rounded-3xl shadow-2xl hover-card text-left transition fade-in">
                <div class="text-primary-accent text-5xl mb-6">🧠</div>
                <h3 class="text-2xl font-bold mb-2">Innovación Constante</h3>
                <p class="text-gray-400 leading-relaxed">
                    Aplicamos las últimas tecnologías para crear soluciones inteligentes que se adaptan a cualquier sector y necesidad.
                </p>
            </div>
            <div class="bg-gray-800 p-10 rounded-3xl shadow-2xl hover-card text-left transition fade-in delay-200">
                <div class="text-primary-accent text-5xl mb-6">🚀</div>
                <h3 class="text-2xl font-bold mb-2">Desarrollo Ágil</h3>
                <p class="text-gray-400 leading-relaxed">
                    Nuestro proceso optimizado convierte rápidamente tus conceptos en productos digitales funcionales y listos para el mercado.
                </p>
            </div>
            <div class="bg-gray-800 p-10 rounded-3xl shadow-2xl hover-card text-left transition fade-in delay-400">
                <div class="text-primary-accent text-5xl mb-6">📈</div>
                <h3 class="text-2xl font-bold mb-2">Escalabilidad Total</h3>
                <p class="text-gray-400 leading-relaxed">
                    Construimos soluciones robustas que crecen a la par de tu negocio, preparadas para futuros desafíos y expansiones.
                </p>
            </div>
        </div>
    </div>
</section>

<section class="py-28 bg-gray-900 text-center">
    <div class="container mx-auto px-6">
        <h2 class="text-4xl md:text-5xl font-bold mb-16 fade-in">Qué nos Distingue</h2>
        <div class="grid md:grid-cols-3 gap-12">
            <div class="bg-gray-800 p-10 rounded-3xl shadow-2xl hover-card text-left transition fade-in">
                <div class="text-primary-accent text-5xl mb-6">🎨</div>
                <h3 class="text-2xl font-bold mb-2 text-white">Diseño Funcional</h3>
                <p class="text-gray-400 leading-relaxed">
                    Creamos interfaces intuitivas y minimalistas que garantizan una experiencia de usuario inigualable.
                </p>
            </div>
            <div class="bg-gray-800 p-10 rounded-3xl shadow-2xl hover-card text-left transition fade-in delay-200">
                <div class="text-primary-accent text-5xl mb-6">🛠️</div>
                <h3 class="text-2xl font-bold mb-2 text-white">Tecnología de Vanguardia</h3>
                <p class="text-gray-400 leading-relaxed">
                    Utilizamos las herramientas más avanzadas para desarrollar aplicaciones seguras, rápidas y eficientes.
                </p>
            </div>
            <div class="bg-gray-800 p-10 rounded-3xl shadow-2xl hover-card text-left transition fade-in delay-400">
                <div class="text-primary-accent text-5xl mb-6">🔮</div>
                <h3 class="text-2xl font-bold mb-2 text-white">Visión de Futuro</h3>
                <p class="text-gray-400 leading-relaxed">
                    Tu proyecto estará listo para adaptarse a las nuevas tendencias del mercado y a los avances tecnológicos.
                </p>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="py-28 bg-gray-950 text-center">
    <div class="container mx-auto px-6 max-w-6xl">
        <h2 class="text-4xl md:text-5xl font-bold mb-6 fade-in">Conversemos</h2>
        <p class="mb-12 text-lg text-gray-400 fade-in">
            Déjanos tus datos para agendar una sesión y descubrir cómo podemos impulsar tu proyecto.
        </p>

        <div class="grid md:grid-cols-2 gap-12 items-center">
            <form class="grid gap-6 bg-gray-900 p-10 rounded-3xl shadow-2xl fade-in" action="#" method="POST">
                <h3 class="text-2xl font-bold text-center text-white mb-4">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 inline-block mr-2 text-primary-accent" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                    </svg>
                    Contáctanos
                </h3>
                <input type="text" name="name" placeholder="Tu Nombre" required class="p-4 rounded-lg bg-gray-800 text-gray-200 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-blue-500 transition">
                <input type="email" name="email" placeholder="Correo Electrónico" required class="p-4 rounded-lg bg-gray-800 text-gray-200 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-blue-500 transition">
                <textarea name="message" placeholder="Describe tu proyecto o consulta..." required class="p-4 rounded-lg bg-gray-800 text-gray-200 border border-gray-700 focus:outline-none focus:ring-2 focus:ring-blue-500 transition h-36 resize-none"></textarea>
                <button type="submit" class="bg-blue-600 text-white font-bold px-8 py-4 rounded-full shadow-lg hover:bg-blue-700 transition transform hover:scale-105">
                    Enviar Mensaje
                </button>
            </form>

            <div class="fade-in">
                <iframe
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d38191.71179615929!2d-93.12944406445314!3d16.75308370687146!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85ed5cb9f353bbbd%3A0x8f1e8a13b8e912f8!2sTuxtla%20Guti%C3%A9rrez%2C%20Chiapas%2C%20M%C3%A9xico!5e0!3m2!1ses-419!2smx!4v1692216364312!5m2!1ses-419!2smx"
                        width="100%" height="450" style="border:0; border-radius: 1.5rem;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                </iframe>
            </div>
        </div>
    </div>
</section>

<footer class="bg-gray-900 text-center py-8">
    <div class="flex justify-center space-x-8 mb-4">
        <a href="#" class="text-gray-400 hover:text-white transition transform hover:scale-110">Twitter</a>
        <a href="#" class="text-gray-400 hover:text-white transition transform hover:scale-110">LinkedIn</a>
        <a href="#" class="text-gray-400 hover:text-white transition transform hover:scale-110">Instagram</a>
    </div>
    <p class="text-gray-500 text-sm">© 2025 Gepi Global Hub. Todos los derechos reservados.</p>
</footer>

</body>
</html>
