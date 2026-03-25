<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MDA Engenharia | Projetos e Instalações</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .glass-card { background: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); }
        .glass-card:hover { transform: translateY(-8px); box-shadow: 0 15px 30px rgba(0,0,0,0.1); }
        .gradient-bg { background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); }
    </style>
</head>
<body class="bg-gray-50 text-gray-900">

    <section class="gradient-bg text-white min-h-[70vh] flex items-center justify-center px-6 py-20">
        <div class="max-w-4xl text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-6 tracking-tight">Projetos, Instalações e Manutenção</h1>
            <p class="text-xl text-gray-300 mb-10 font-light leading-relaxed">Engenharia, Vistorias, Elétrica, Hidráulica e Acompanhamento de Obras em Anápolis e Região.</p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="https://wa.me/5562999999999" class="bg-green-500 hover:bg-green-600 px-10 py-4 rounded-full font-bold flex items-center gap-3 transition-all shadow-lg hover:shadow-green-500/20">
                    <i class="fab fa-whatsapp text-xl"></i> Orçamento Rápido
                </a>
            </div>
        </div>
    </section>

    <section class="max-w-7xl mx-auto px-6 py-24">
        <h2 class="text-3xl font-bold text-center mb-16 text-slate-800">Nossas Especialidades</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            <div class="glass-card p-8 border border-gray-100 rounded-3xl">
                <div class="text-blue-600 text-4xl mb-6"><i class="fas fa-bolt"></i></div>
                <h3 class="text-lg font-bold mb-3">Instalações Elétricas</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Serviços elétricos, CFTV, alarmes e manutenção técnica especializada.</p>
            </div>
            <div class="glass-card p-8 border border-gray-100 rounded-3xl">
                <div class="text-blue-600 text-4xl mb-6"><i class="fas fa-droplet"></i></div>
                <h3 class="text-lg font-bold mb-3">Instalações Hidráulicas</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Reparos, instalações e manutenção com precisão técnica e sem desperdício.</p>
            </div>
            <div class="glass-card p-8 border border-gray-100 rounded-3xl">
                <div class="text-blue-600 text-4xl mb-6"><i class="fas fa-shield-halved"></i></div>
                <h3 class="text-lg font-bold mb-3">Segurança & Projetos</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Projetos de Engenharia, Incêndio (PPCI) e Segurança do Trabalho.</p>
            </div>
            <div class="glass-card p-8 border border-gray-100 rounded-3xl">
                <div class="text-blue-600 text-4xl mb-6"><i class="fas fa-clipboard-check"></i></div>
                <h3 class="text-lg font-bold mb-3">Vistoria e Obras</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Consultoria predial, vistorias técnicas e acompanhamento rigoroso de cronograma.</p>
            </div>
        </div>
    </section>

    <section class="bg-white py-20 border-t border-gray-100">
        <div class="max-w-5xl mx-auto text-center px-6">
            <h2 class="text-2xl font-bold mb-10">Fale com um Especialista</h2>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-6">
                <a href="https://instagram.com/seuusuario" class="flex items-center justify-center gap-3 p-5 border border-pink-100 rounded-2xl text-pink-600 hover:bg-pink-50 transition-all font-semibold">
                    <i class="fab fa-instagram text-2xl"></i> Instagram
                </a>
                <a href="mailto:contato@seuemail.com" class="flex items-center justify-center gap-3 p-5 border border-gray-100 rounded-2xl text-gray-700 hover:bg-gray-50 transition-all font-semibold">
                    <i class="far fa-envelope text-2xl"></i> E-mail
                </a>
                <a href="tel:5562999999999" class="flex items-center justify-center gap-3 p-5 border border-blue-100 rounded-2xl text-blue-600 hover:bg-blue-50 transition-all font-semibold">
                    <i class="fas fa-phone text-2xl"></i> Ligar Agora
                </a>
            </div>
        </div>
    </section>

    <footer class="py-12 text-center text-gray-400 text-xs tracking-widest uppercase">
        <p>© 2026 MDA Engenharia & Instalações. Qualidade e Segurança.</p>
    </footer>

</body>
</html>
