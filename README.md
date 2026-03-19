<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PUNTO DIGITAL | Estructura Estratégica para Empresas</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .bg-dark { background-color: #0a0a0a; }
        .text-accent { color: #d97706; } /* Un naranja quemado/bronce elegante */
        .border-accent { border-color: #d97706; }
        .bg-accent { background-color: #d97706; }
    </style>
</head>
<body class="bg-dark text-gray-300 antialiased">

    <nav class="fixed w-full z-50 bg-dark/80 backdrop-blur-md border-b border-white/5">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <div class="w-8 h-8 border-2 border-accent rounded-full flex items-center justify-center">
                    <div class="w-2 h-2 bg-accent rounded-full"></div>
                </div>
                <span class="text-white font-bold tracking-tighter text-xl uppercase">Punto Digital</span>
            </div>
            <div class="hidden md:flex space-x-10 text-sm uppercase tracking-widest font-medium">
                <a href="#servicios" class="hover:text-accent transition">Servicios</a>
                <a href="#metodo" class="hover:text-accent transition">Método</a>
                <a href="#contacto" class="hover:text-accent transition">Contacto</a>
            </div>
            <a href="#contacto" class="border border-white/20 px-5 py-2 text-xs uppercase tracking-widest hover:bg-white hover:text-black transition duration-500">
                Empezar Proyecto
            </a>
        </div>
    </nav>

    <section class="relative min-h-screen flex items-center pt-20 overflow-hidden">
        <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-12 items-center">
            <div class="z-10">
                <span class="text-accent uppercase tracking-[0.3em] text-xs font-bold mb-4 block">Arquitectura de Negocios</span>
                <h1 class="text-5xl md:text-7xl font-bold text-white leading-tight mb-8">
                    Estructura digital para tu crecimiento <span class="text-accent">empresarial.</span>
                </h1>
                <p class="text-lg text-gray-400 max-w-lg mb-10 leading-relaxed">
                    No diseñamos sitios web; construimos activos digitales diseñados para convertir visitas en clientes de alto valor y escalar tu facturación.
                </p>
                <div class="flex flex-col sm:flex-row gap-4">
                    <a href="#contacto" class="bg-accent text-white px-8 py-4 rounded-sm font-bold uppercase text-xs tracking-widest hover:brightness-110 transition shadow-xl shadow-accent/20 text-center">
                        Solicitar Propuesta Estratégica
                    </a>
                </div>
            </div>
            
            <div class="relative flex justify-center items-center">
                <div class="w-80 h-80 border border-white/10 rounded-full absolute animate-pulse"></div>
                <div class="w-[30rem] h-[30rem] border border-accent/20 rounded-full absolute"></div>
                <div class="grid grid-cols-3 gap-4 relative">
                    <div class="w-24 h-24 bg-white/5 backdrop-blur-xl border border-white/10 flex items-center justify-center transform hover:scale-110 transition duration-500">
                        <span class="text-accent text-2xl font-bold">+45%</span>
                    </div>
                    <div class="w-24 h-24 bg-accent/10 backdrop-blur-xl border border-accent/30 flex items-center justify-center mt-8 transform hover:scale-110 transition duration-500">
                        <span class="text-white text-xs uppercase tracking-tighter text-center">ROI<br>Optimizado</span>
                    </div>
                    <div class="w-24 h-24 bg-white/5 backdrop-blur-xl border border-white/10 flex items-center justify-center transform hover:scale-110 transition duration-500">
                        <svg class="w-8 h-8 text-accent" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-12 border-y border-white/5 bg-white/[0.02]">
        <div class="max-w-7xl mx-auto px-6 flex flex-wrap justify-between items-center opacity-40 grayscale gap-8">
            <span class="font-bold text-xl uppercase tracking-tighter">Fintech solutions</span>
            <span class="font-bold text-xl uppercase tracking-tighter">Global Logistics</span>
            <span class="font-bold text-xl uppercase tracking-tighter">Nexus Corp</span>
            <span class="font-bold text-xl uppercase tracking-tighter">Elite Real Estate</span>
        </div>
    </section>

    <section id="servicios" class="py-32">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-24">
                <h2 class="text-3xl md:text-5xl font-bold text-white mb-6">Soluciones de Ingeniería Digital</h2>
                <div class="w-20 h-1 bg-accent mx-auto"></div>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <div class="group p-10 bg-white/[0.03] border border-white/5 hover:border-accent/50 transition duration-500">
                    <div class="mb-8 text-accent group-hover:scale-110 transition duration-500">
                        <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M9.75 17L9 21h6l-.75-4M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-4 italic">Web Corporativa de Autoridad</h3>
                    <p class="text-sm leading-relaxed">No es un folleto. Es una plataforma optimizada para SEO y autoridad que posiciona a tu empresa como líder del sector.</p>
                </div>

                <div class="group p-10 bg-white/[0.03] border border-white/5 hover:border-accent/50 transition duration-500">
                    <div class="mb-8 text-accent group-hover:scale-110 transition duration-500">
                        <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-4 italic">E-Commerce de Alto Rendimiento</h3>
                    <p class="text-sm leading-relaxed">Sistemas transaccionales fluidos centrados en la experiencia de usuario (UX) para maximizar el ticket promedio.</p>
                </div>

                <div class="group p-10 bg-white/[0.03] border border-white/5 hover:border-accent/50 transition duration-500">
                    <div class="mb-8 text-accent group-hover:scale-110 transition duration-500">
                        <svg class="w-10 h-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-4 italic">Social Strategy & IG Funnels</h3>
                    <p class="text-sm leading-relaxed">Convertimos tu Instagram en una entrada de embudo. Estrategia visual y funcional para captar leads cualificados.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contacto" class="py-32 bg-accent">
        <div class="max-w-4xl mx-auto px-6 text-center text-white">
            <h2 class="text-4xl md:text-6xl font-bold mb-8 italic italic">¿Listo para escalar tu presencia?</h2>
            <p class="text-xl mb-12 opacity-90">Analizamos tu modelo de negocio y diseñamos la solución digital que necesitas, no la que te quieren vender.</p>
            <form class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <input type="text" placeholder="Nombre de Empresa" class="bg-white/10 border border-white/20 p-4 rounded-sm placeholder:text-white/60 focus:outline-none focus:bg-white/20">
                <input type="email" placeholder="Email Profesional" class="bg-white/10 border border-white/20 p-4 rounded-sm placeholder:text-white/60 focus:outline-none focus:bg-white/20">
                <button class="md:col-span-2 bg-white text-accent font-bold py-5 uppercase tracking-widest hover:bg-gray-100 transition">Agendar Auditoría Gratuita</button>
            </form>
        </div>
    </section>

    <footer class="py-12 border-t border-white/5">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:row justify-between items-center text-xs tracking-widest text-gray-500 uppercase">
            <p>© 2026 PUNTO DIGITAL. Todos los derechos reservados.</p>
            <div class="flex space-x-6 mt-4 md:mt-0">
                <a href="#" class="hover:text-white">LinkedIn</a>
                <a href="#" class="hover:text-white">Instagram</a>
                <a href="#" class="hover:text-white">Dribbble</a>
            </div>
        </div>
    </footer>

</body>
</html>
