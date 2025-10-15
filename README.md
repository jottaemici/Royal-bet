<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cassino Royal - Emoção e Sorte Online</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0F172A; /* Slate 900 */
        }
        .text-gold {
            color: #FFD700;
        }
        .bg-gold {
            background-color: #FFD700;
        }
        .border-gold {
            border-color: #FFD700;
        }
        .btn {
            @apply px-6 py-2 rounded-lg font-bold text-center transition-transform transform hover:scale-105 shadow-lg;
        }
        .btn-primary {
            @apply bg-gold text-gray-900 hover:bg-yellow-400;
        }
        .btn-secondary {
            @apply bg-transparent border-2 border-gold text-gold hover:bg-gold hover:text-gray-900;
        }
        .game-card {
            @apply relative overflow-hidden rounded-lg shadow-xl cursor-pointer transform transition-transform hover:-translate-y-2;
        }
        .game-card-overlay {
            @apply absolute inset-0 bg-black bg-opacity-70 flex flex-col justify-center items-center opacity-0 transition-opacity duration-300;
        }
        .game-card:hover .game-card-overlay {
            opacity: 1;
        }
        .shiny-text {
            background: linear-gradient(90deg, #d4af37, #ffd700, #d4af37);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-fill-color: transparent;
            animation: shine 3s linear infinite;
        }
        @keyframes shine {
            0% { background-position: -200% center; }
            100% { background-position: 200% center; }
        }
    </style>
</head>
<body class="text-white">

    <!-- Cabeçalho -->
    <header class="bg-slate-900/80 backdrop-blur-sm sticky top-0 z-50 shadow-lg">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-3xl font-black shiny-text">
                <i class="fas fa-crown mr-2"></i>RoyalBet
            </a>
            <div class="hidden lg:flex items-center space-x-8 text-lg">
                <a href="#slots" class="hover:text-gold transition-colors">Slots</a>
                <a href="#table-games" class="hover:text-gold transition-colors">Jogos de Mesa</a>
                <a href="#live" class="hover:text-gold transition-colors">Casino ao Vivo</a>
                <a href="#promotions" class="hover:text-gold transition-colors">Promoções</a>
            </div>
            <div class="hidden lg:flex items-center space-x-4">
                <button class="btn btn-secondary">Entrar</button>
                <button class="btn btn-primary">Registrar</button>
            </div>
            <button id="mobile-menu-button" class="lg:hidden text-2xl">
                <i class="fas fa-bars"></i>
            </button>
        </nav>
        <!-- Menu Móvel -->
        <div id="mobile-menu" class="hidden lg:hidden bg-slate-800 px-6 pb-4">
            <a href="#slots" class="block py-2 hover:text-gold transition-colors">Slots</a>
            <a href="#table-games" class="block py-2 hover:text-gold transition-colors">Jogos de Mesa</a>
            <a href="#live" class="block py-2 hover:text-gold transition-colors">Casino ao Vivo</a>
            <a href="#promotions" class="block py-2 hover:text-gold transition-colors">Promoções</a>
            <div class="flex mt-4 space-x-4">
                <button class="btn btn-secondary w-full">Entrar</button>
                <button class="btn btn-primary w-full">Registrar</button>
            </div>
        </div>
    </header>

    <!-- Conteúdo Principal -->
    <main>
        <!-- Seção Herói -->
        <section class="h-[60vh] md:h-[80vh] bg-cover bg-center flex items-center" style="background-image: url('https://placehold.co/1920x1080/0F172A/FFD700?text=Bem-Vindo+ao+RoyalBet&font=inter');">
            <div class="container mx-auto px-6 text-center bg-black/50 p-8 rounded-xl">
                <h1 class="text-4xl md:text-6xl font-extrabold shiny-text mb-4">Sua Aventura Real Começa Aqui</h1>
                <p class="text-lg md:text-xl mb-8 max-w-3xl mx-auto">Receba um bônus de 100% até R$500 + 200 Rodadas Grátis no seu primeiro depósito!</p>
                <button class="btn btn-primary text-xl px-10 py-4">Jogue Agora!</button>
            </div>
        </section>

        <!-- Seção de Jogos -->
        <section id="slots" class="py-16">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold mb-2 text-center">Nossos Caça-Níqueis Populares</h2>
                <p class="text-center text-slate-400 mb-8">Os jogos mais amados pelos nossos jogadores.</p>
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-6 gap-6">
                    <!-- Cards de Jogo -->
                    <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Gates+of+Olympus" alt="Gates of Olympus" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Gates of Olympus</h3>
                            <button class="btn btn-primary">Jogar</button>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Sweet+Bonanza" alt="Sweet Bonanza" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Sweet Bonanza</h3>
                            <button class="btn btn-primary">Jogar</button>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=The+Dog+House" alt="The Dog House" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">The Dog House</h3>
                            <button class="btn btn-primary">Jogar</button>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Big+Bass+Bonanza" alt="Big Bass Bonanza" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Big Bass Bonanza</h3>
                            <button class="btn btn-primary">Jogar</button>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Fortune+Tiger" alt="Fortune Tiger" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Fortune Tiger</h3>
                            <button class="btn btn-primary">Jogar</button>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Sugar+Rush" alt="Sugar Rush" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Sugar Rush</h3>
                            <button class="btn btn-primary">Jogar</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Seção de Jogos de Mesa -->
        <section id="table-games" class="py-16 bg-slate-800">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold mb-8 text-center">Jogos de Mesa</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Card Roleta -->
                    <div class="bg-slate-700 rounded-lg p-6 text-center hover:bg-slate-600 transition-colors">
                        <i class="fas fa-dice text-5xl text-gold mb-4"></i>
                        <h3 class="text-2xl font-bold mb-2">Roleta</h3>
                        <p class="text-slate-400 mb-4">Aposte nos seus números da sorte e sinta a emoção da roda girar.</p>
                        <button class="btn btn-secondary">Ver Mesas</button>
                    </div>
                    <!-- Card Blackjack -->
                    <div class="bg-slate-700 rounded-lg p-6 text-center hover:bg-slate-600 transition-colors">
                        <i class="fas fa-cards text-5xl text-gold mb-4"></i>
                        <h3 class="text-2xl font-bold mb-2">Blackjack</h3>
                        <p class="text-slate-400 mb-4">Desafie o dealer e tente chegar o mais perto possível de 21 sem estourar.</p>
                        <button class="btn btn-secondary">Ver Mesas</button>
                    </div>
                    <!-- Card Poker -->
                    <div class="bg-slate-700 rounded-lg p-6 text-center hover:bg-slate-600 transition-colors">
                        <i class="fas fa-spade text-5xl text-gold mb-4"></i>
                        <h3 class="text-2xl font-bold mb-2">Pôquer</h3>
                        <p class="text-slate-400 mb-4">Mostre sua melhor mão em diversas variantes do jogo de cartas mais famoso.</p>
                        <button class="btn btn-secondary">Ver Mesas</button>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Seção Casino ao Vivo -->
        <section id="live" class="py-16">
            <div class="container mx-auto px-6">
                 <h2 class="text-3xl font-bold mb-2 text-center">Cassino ao Vivo</h2>
                <p class="text-center text-slate-400 mb-8">A experiência de um cassino real, onde quer que você esteja.</p>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                     <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Live+Roulette" alt="Live Roulette" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Roleta ao Vivo</h3>
                            <button class="btn btn-primary">Entrar</button>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Live+Blackjack" alt="Live Blackjack" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Blackjack ao Vivo</h3>
                            <button class="btn btn-primary">Entrar</button>
                        </div>
                    </div>
                    <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Game+Shows" alt="Game Shows" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Game Shows</h3>
                            <button class="btn btn-primary">Entrar</button>
                        </div>
                    </div>
                     <div class="game-card">
                        <img src="https://placehold.co/300x400/1E293B/FFFFFF?text=Live+Baccarat" alt="Live Baccarat" class="w-full h-full object-cover">
                        <div class="game-card-overlay">
                            <h3 class="font-bold text-lg mb-2">Bacará ao Vivo</h3>
                            <button class="btn btn-primary">Entrar</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Seção de Promoções -->
        <section id="promotions" class="py-16 bg-slate-800">
            <div class="container mx-auto px-6 text-center">
                 <h2 class="text-3xl font-bold mb-8 shiny-text">Promoções Imperdíveis</h2>
                 <div class="bg-slate-700/50 border border-gold rounded-lg p-8 max-w-4xl mx-auto">
                     <h3 class="text-2xl font-bold text-gold mb-3">Torneio Semanal de Slots</h3>
                     <p class="text-slate-300 mb-6">Participe do nosso torneio semanal e concorra a um prêmio total de R$25.000! Jogue seus slots favoritos, acumule pontos e suba no ranking.</p>
                     <button class="btn btn-primary">Saiba Mais</button>
                 </div>
            </div>
        </section>

        <!-- Seção Hall da Fama -->
        <section id="members" class="py-16">
            <div class="container mx-auto px-6 text-center">
                 <h2 class="text-3xl font-bold mb-2">Hall da Fama</h2>
                 <p class="text-center text-slate-400 mb-12">Conheça os nossos últimos grandes vencedores!</p>
                 <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Card do Vencedor -->
                    <div class="bg-slate-800 border border-slate-700 rounded-lg p-6 flex flex-col items-center transform transition-transform hover:scale-105 hover:border-gold">
                        <img src="https://placehold.co/100x100/1E293B/FFD700?text=J" alt="Avatar do Jogador" class="w-24 h-24 rounded-full border-4 border-slate-600 mb-4">
                        <h3 class="text-xl font-bold text-white">JogadorX_77</h3>
                        <p class="text-2xl font-black shiny-text my-2">R$ 15.234</p>
                        <p class="text-slate-400">em Gates of Olympus</p>
                    </div>
                    <!-- Card do Vencedor -->
                    <div class="bg-slate-800 border border-slate-700 rounded-lg p-6 flex flex-col items-center transform transition-transform hover:scale-105 hover:border-gold">
                        <img src="https://placehold.co/100x100/1E293B/FFD700?text=A" alt="Avatar do Jogador" class="w-24 h-24 rounded-full border-4 border-slate-600 mb-4">
                        <h3 class="text-xl font-bold text-white">Ana_Sorte</h3>
                        <p class="text-2xl font-black shiny-text my-2">R$ 9.850</p>
                        <p class="text-slate-400">em Sweet Bonanza</p>
                    </div>
                    <!-- Card do Vencedor -->
                    <div class="bg-slate-800 border border-slate-700 rounded-lg p-6 flex flex-col items-center transform transition-transform hover:scale-105 hover:border-gold">
                        <img src="https://placehold.co/100x100/1E293B/FFD700?text=L" alt="Avatar do Jogador" class="w-24 h-24 rounded-full border-4 border-slate-600 mb-4">
                        <h3 class="text-xl font-bold text-white">Lucas_Pro</h3>
                        <p class="text-2xl font-black shiny-text my-2">R$ 21.400</p>
                        <p class="text-slate-400">na Roleta ao Vivo</p>
                    </div>
                    <!-- Card do Vencedor -->
                    <div class="bg-slate-800 border border-slate-700 rounded-lg p-6 flex flex-col items-center transform transition-transform hover:scale-105 hover:border-gold">
                        <img src="https://placehold.co/100x100/1E293B/FFD700?text=M" alt="Avatar do Jogador" class="w-24 h-24 rounded-full border-4 border-slate-600 mb-4">
                        <h3 class="text-xl font-bold text-white">Maria_Bet</h3>
                        <p class="text-2xl font-black shiny-text my-2">R$ 7.777</p>
                        <p class="text-slate-400">em Fortune Tiger</p>
                    </div>
                 </div>
            </div>
        </section>
    </main>

    <!-- Rodapé -->
    <footer class="bg-slate-900 pt-12 pb-8">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 text-slate-400">
                <div>
                    <h3 class="text-xl font-bold text-white mb-4">RoyalBet</h3>
                    <p>RoyalBet é um cassino online licenciado que oferece uma experiência de jogo segura e divertida. Junte-se a nós para a melhor seleção de jogos.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold text-white mb-4">Links Rápidos</h3>
                    <ul>
                        <li class="mb-2"><a href="#" class="hover:text-gold">Sobre Nós</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-gold">Termos e Condições</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-gold">Política de Privacidade</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-gold">Jogo Responsável</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold text-white mb-4">Suporte</h3>
                    <ul>
                        <li class="mb-2"><a href="#" class="hover:text-gold">FAQ</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-gold">Chat ao Vivo</a></li>
                        <li class="mb-2"><a href="#" class="hover:text-gold">suporte@royalbet.com</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold text-white mb-4">Métodos de Pagamento</h3>
                    <div class="flex flex-wrap text-3xl gap-4">
                        <i class="fab fa-cc-visa" title="Visa"></i>
                        <i class="fab fa-cc-mastercard" title="Mastercard"></i>
                        <i class="fa-solid fa-qrcode" title="Pix"></i>
                        <i class="fab fa-bitcoin" title="Bitcoin"></i>
                    </div>
                </div>
            </div>
            <div class="border-t border-slate-700 mt-8 pt-6 text-center text-slate-500">
                <p class="mb-2">&copy; 2024 RoyalBet Casino. Todos os direitos reservados.</p>
                <p class="text-sm">Jogos de azar podem ser viciantes. Jogue com responsabilidade. Este site é destinado a maiores de 18 anos. Este é um site de demonstração e não envolve dinheiro real.</p>
            </div>
        </div>
    </footer>

    <script>
        // Lógica do Menu Móvel
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>

</body>
</html>

