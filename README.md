<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instalações & Projetos Técnicos</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .glass-card { background: rgba(255, 255, 255, 0.9); backdrop-filter: blur(10px); transition: all 0.3s ease; }
        .glass-card:hover { transform: translateY(-5px); box-shadow: 0 10px 20px rgba(0,0,0,0.1); }
        .gradient-bg { background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); }
    </style>
</head>
<body class="bg-gray-50 text-gray-900">

    <section class="gradient-bg text-white min-h-[60vh] flex items-center justify-center px-6 py-20">
        <div class="max-w-4xl text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-6 animate-pulse">Soluções Técnicas em Instalações</h1>
            <p class="text-xl text-gray-300 mb-8 font-light">Elétrica, Hidráulica e Projetos de Segurança para sua residência ou condomínio.</p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="https://wa.me/5562999999999" class="bg-green-500 hover:bg-green-600 px-8 py-4 rounded-full font-bold flex items-center gap-2 transition-all">
                    <i class="fab fa-whatsapp"></i> Orçamento Rápido
                </a>
            </div>
        </div>
    </section>

    <section class="max-w-6xl mx-auto px-6 py-20">
        <h2 class="text-3xl font-bold text-center mb-12">Nossas Especialidades</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="glass-card p-8 border border-gray-100 rounded-2xl">
                <div class="text-blue-600 text-4xl mb-4"><i class="fas fa-bolt"></i></div>
                <h3 class="text-xl font-bold mb-2">Instalações Elétricas</h3>
                <p class="text-gray-600">Troca de quadros, fiação, instalação de chuveiros e automação residencial.</p>
            </div>
            <div class="glass-card p-8 border border-gray-100 rounded-2xl">
                <div class="text-blue-600 text-4xl mb-4"><i class="fas fa-droplet"></i></div>
                <h3 class="text-xl font-bold mb-2">Manutenção Hidráulica</h3>
                <p class="text-gray-600">Reparos em geral, instalação de louças e metais com precisão técnica.</p>
            </div>
            <div class="glass-card p-8 border border-gray-100 rounded-2xl">
                <div class="text-blue-600 text-4xl mb-4"><i class="fas fa-shield-halved"></i></div>
                <h3 class="text-xl font-bold mb-2">Segurança & Projetos</h3>
                <p class="text-gray-600">Projetos de segurança do trabalho e instalações de alarmes e CFTV.</p>
            </div>
        </div>
    </section>

    <section class="bg-white py-16 border-t border-gray-100">
        <div class="max-w-4xl mx-auto text-center px-6">
            <h2 class="text-2xl font-bold mb-8">Conecte-se Conosco</h2>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-6">
                <a href="https://instagram.com/seuusuario" class="flex items-center justify-center gap-3 p-4 border border-pink-200 rounded-xl text-pink-600 hover:bg-pink-50 transition-colors">
                    <i class="fab fa-instagram text-2xl"></i> @seuusuario
                </a>
                <a href="mailto:contato@seuemail.com" class="flex items-center justify-center gap-3 p-4 border border-gray-200 rounded-xl text-gray-700 hover:bg-gray-50 transition-colors">
                    <i class="far fa-envelope text-2xl"></i> E-mail Direto
                </a>
                <a href="tel:5562999999999" class="flex items-center justify-center gap-3 p-4 border border-blue-200 rounded-xl text-blue-600 hover:bg-blue-50 transition-colors">
                    <i class="fas fa-phone text-2xl"></i> Ligar Agora
                </a>
            </div>
        </div>
    </section>

    <footer class="py-10 text-center text-gray-400 text-sm">
        <p>© 2026 - Serviços de Engenharia e Manutenção. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
