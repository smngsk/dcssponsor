<!DOCTYPE html>
<html lang="ja" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ダンサーズキャリアサポート 協賛のご案内</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    
    <!-- Chosen Palette: Warm Neutrals & Sophisticated Teal -->
    <!-- Application Structure Plan: A thematic, single-page application with a sticky navigation bar for easy access to key sections. The flow is designed to first establish the problem and market opportunity (課題と可能性), then showcase the value proposition of dancers (ダンサーの価値), followed by the direct benefits to sponsoring companies (企業様のメリット), concrete action plans (協賛プラン), and finally building trust (私たちについて) before the final call to action. This structure guides corporate decision-makers logically from understanding the issue to seeing the value and taking action, which is more effective than a simple linear document. -->
    <!-- Visualization & Content Choices: 
        - Dance Population Growth: Report Info("日本のダンス人口は2025年で1000万人超と急増中") -> Goal(Show market change) -> Viz(Bar Chart - Chart.js) -> Interaction(Tooltips) -> Justification(Visually demonstrates the growing talent pool).
        - Dancer Unemployment Rate: Report Info("プロダンサーの10年以内の失業率は90〜95%") -> Goal(Show urgency/problem) -> Viz(Donut Chart - Chart.js) -> Interaction(Tooltips, central label) -> Justification(Highlights the severity of the career transition issue).
        - Dancer's Potential: Report Info("伝える力", "創る力", etc.) -> Goal(Organize/Inform) -> Viz(Interactive Cards - HTML/Tailwind) -> Interaction(Hover effects) -> Justification(Encourages engagement and makes skills tangible).
        - Sponsorship Tiers: Report Info(Bronze/Silver/Gold plans) -> Goal(Compare/Guide Action) -> Viz(Styled Pricing Cards - HTML/Tailwind) -> Interaction(Hover effects, clear CTA) -> Justification(Clearly presents options and facilitates decision-making).
        - Our Activities: Report Info(Seminars, Counseling, etc.) -> Goal(Build Trust/Organize) -> Viz(Accordion - HTML/Tailwind/JS) -> Interaction(Click to expand) -> Justification(Presents detailed information cleanly without cluttering the page).
        - All choices are made to be interactive, visually appealing, and guide the user through a compelling narrative.
    -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->

    <style>
        body {
            font-family: 'Noto Sans JP', sans-serif;
            background-color: #FDFCF8;
            color: #383838;
        }
        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 40vh;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
        .accordion-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.5s ease-in-out;
        }
        .accordion-button.active + .accordion-content {
            max-height: 500px; /* Adjust as needed */
        }
        .nav-link::after {
            content: '';
            display: block;
            width: 0;
            height: 2px;
            background: #004d40;
            transition: width .3s;
        }
        .nav-link:hover::after {
            width: 100%;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header & Navigation -->
    <header class="bg-white/80 backdrop-blur-md sticky top-0 z-50 shadow-sm">
        <div class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#" class="text-xl font-bold text-gray-800">DCS</a>
            <nav class="hidden md:flex space-x-8 items-center">
                <a href="#problem" class="nav-link text-gray-600 hover:text-gray-900">課題と可能性</a>
                <a href="#potential" class="nav-link text-gray-600 hover:text-gray-900">ダンサーの価値</a>
                <a href="#benefits" class="nav-link text-gray-600 hover:text-gray-900">企業様のメリット</a>
                <a href="#plans" class="nav-link text-gray-600 hover:text-gray-900">協賛プラン</a>
                <a href="#about" class="nav-link text-gray-600 hover:text-gray-900">私たちについて</a>
                <a href="#contact" class="bg-[#004d40] text-white px-4 py-2 rounded-full hover:bg-[#00382e] transition-colors">お問い合わせ</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden text-2xl font-bold p-2 -mr-2 text-gray-800">
                ☰
            </button>
        </div>
        <div id="mobile-menu" class="hidden md:hidden">
             <a href="#problem" class="block py-2 px-4 text-sm hover:bg-gray-200">課題と可能性</a>
             <a href="#potential" class="block py-2 px-4 text-sm hover:bg-gray-200">ダンサーの価値</a>
             <a href="#benefits" class="block py-2 px-4 text-sm hover:bg-gray-200">企業様のメリット</a>
             <a href="#plans" class="block py-2 px-4 text-sm hover:bg-gray-200">協賛プラン</a>
             <a href="#about" class="block py-2 px-4 text-sm hover:bg-gray-200">私たちについて</a>
             <a href="#contact" class="block py-2 px-4 text-sm hover:bg-gray-200">お問い合わせ</a>
        </div>
    </header>

    <!-- Main Content -->
    <main>

        <!-- Hero Section -->
        <section class="min-h-[60vh] flex items-center bg-cover bg-center bg-gray-700" style="background-image: url('https://images.unsplash.com/photo-1524721696987-b9527df9e512?q=80&w=2070&auto=format&fit=crop');">
            <div class="bg-black/50 w-full h-full min-h-[60vh] flex items-center">
                <div class="container mx-auto px-6 text-center text-white">
                    <h1 class="text-4xl md:text-6xl font-bold leading-tight mb-4">ダンサーの経験を、社会の力に。</h1>
                    <p class="text-lg md:text-xl">ダンサーのキャリアトランジションを支援し、<br class="md:hidden">その才能と可能性を、ビジネスの未来へ。</p>
                </div>
            </div>
        </section>

        <!-- Section 1: The Challenge & Opportunity -->
        <section id="problem" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">課題と可能性</h2>
                    <p class="max-w-3xl mx-auto text-gray-600">ダンサーの多くはキャリアの岐路で大きな課題に直面しています。しかし、その背景には企業にとって未開拓の、大きな可能性を秘めた人材市場が広がっています。</p>
                </div>
                <div class="grid md:grid-cols-2 gap-8 lg:gap-16 items-center">
                    <div class="space-y-6">
                        <h3 class="text-2xl font-bold text-gray-800">キャリアの現実</h3>
                        <p class="text-gray-600">心身を捧げた長年の訓練にもかかわらず、多くのダンサーは<strong class="text-[#004d40]">20代後半という若さで第一線を退く</strong>のが現実です。社会経験やキャリアに関する知識が乏しいまま転換期を迎え、その才能や経験が社会で活かされないままになっています。</p>
                        <div class="bg-amber-50 border-l-4 border-amber-400 p-4 rounded-r-lg">
                            <p class="font-semibold">ダンサー専門のキャリア支援制度は海外には存在しますが、現在の日本にはありません。私たちが、その架け橋となります。</p>
                        </div>
                    </div>
                    <div>
                        <div class="chart-container">
                            <canvas id="unemploymentChart"></canvas>
                        </div>
                        <p class="text-center text-sm text-gray-500 mt-2">プロダンサーの10年以内の失業率（米国調べ）</p>
                    </div>
                </div>
                <div class="grid md:grid-cols-2 gap-8 lg:gap-16 items-center mt-16">
                    <div class="order-2 md:order-1">
                        <div class="chart-container">
                            <canvas id="populationChart"></canvas>
                        </div>
                        <p class="text-center text-sm text-gray-500 mt-2">日本のダンス人口推移予測</p>
                    </div>
                    <div class="space-y-6 order-1 md:order-2">
                        <h3 class="text-2xl font-bold text-gray-800">急増するダンス市場</h3>
                        <p class="text-gray-600">中学での体育必修化やSNSでのブームを背景に、日本のダンス人口は急増。2025年には<strong class="text-[#004d40]">1000万人を超える</strong>と予測されています。このうち、プロまたはプロ志望者は<strong class="text-[#004d40]">推定21万～28万人</strong>。これは、才能と情熱にあふれた、巨大な人材の宝庫です。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 2: Dancer's Potential -->
        <section id="potential" class="py-16 md:py-24">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">ダンサーは "未発掘の宝"</h2>
                    <p class="max-w-3xl mx-auto text-gray-600">長年の厳しい訓練と舞台経験は、ビジネスの世界でも高く評価されるべきポータブルスキルを育みます。これらは、貴社の成長を加速させる貴重な人的資源です。</p>
                </div>
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-2 transition-all duration-300">
                        <h3 class="text-xl font-bold mb-2 text-[#004d40]">伝える力・創る力</h3>
                        <p class="text-gray-600">観客を魅了する表現力と、ゼロから価値を生み出す創造力。</p>
                    </div>
                    <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-2 transition-all duration-300">
                        <h3 class="text-xl font-bold mb-2 text-[#004d40]">やり抜く力・精神力</h3>
                        <p class="text-gray-600">高い集中力、自己管理力、多様な仲間との協調性。</p>
                    </div>
                    <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-2 transition-all duration-300">
                        <h3 class="text-xl font-bold mb-2 text-[#004d40]">本番で成果を出す力</h3>
                        <p class="text-gray-600">強いプレッシャー下で最高の結果を出す勝負強さ。</p>
                    </div>
                    <div class="bg-white p-8 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-2 transition-all duration-300">
                        <h3 class="text-xl font-bold mb-2 text-[#004d40]">人間的魅力</h3>
                        <p class="text-gray-600">人の心を動かし、自身と向き合い続ける探求心。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 3: Benefits for Companies -->
        <section id="benefits" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">企業様のメリット</h2>
                    <p class="max-w-3xl mx-auto text-gray-600">ダンサー支援は、社会貢献活動に留まらず、企業の未来を創る「人的資本への投資」です。具体的なメリットをご紹介します。</p>
                </div>
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="text-center p-8 border border-gray-200 rounded-lg">
                        <div class="text-4xl text-[#004d40] mb-4">✓</div>
                        <h3 class="text-xl font-bold mb-2">先進的なブランディング</h3>
                        <p class="text-gray-600">「人の可能性を信じ、育てる企業」としての先進的な企業イメージを社会に発信できます。</p>
                    </div>
                    <div class="text-center p-8 border border-gray-200 rounded-lg">
                        <div class="text-4xl text-[#004d40] mb-4">✓</div>
                        <h3 class="text-xl font-bold mb-2">優秀な人材の獲得</h3>
                        <p class="text-gray-600">ポテンシャルの高い新たな労働市場へいち早くアプローチし、多様な人材を獲得できます。</p>
                    </div>
                    <div class="text-center p-8 border border-gray-200 rounded-lg">
                        <div class="text-4xl text-[#004d40] mb-4">✓</div>
                        <h3 class="text-xl font-bold mb-2">効果的なIR/PR活動</h3>
                        <p class="text-gray-600">SDGsレポート等に人的資本投資のユニークな事例として掲載し、企業価値を高めます。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 4: Sponsorship Plans -->
        <section id="plans" class="py-16 md:py-24">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">協賛プラン</h2>
                    <p class="max-w-3xl mx-auto text-gray-600">ダンサーの未来を共に創るための、3つの賛助会員プランをご用意しました。貴社のニーズに合わせてお選びいただけます。</p>
                </div>
                <div class="grid lg:grid-cols-3 gap-8 max-w-5xl mx-auto">
                    <!-- Bronze Plan -->
                    <div class="bg-white rounded-lg shadow-lg p-8 border-t-4 border-amber-600 flex flex-col">
                        <h3 class="text-2xl font-bold text-center mb-2">ブロンズ会員</h3>
                        <p class="text-center text-4xl font-bold my-4">10<span class="text-xl">万円/年</span></p>
                        <ul class="space-y-4 text-gray-600 mb-8 flex-grow">
                            <li class="flex items-start"><span class="text-green-500 mr-2 mt-1">✓</span>公式サイトでの企業情報・求人情報の紹介</li>
                            <li class="flex items-start"><span class="text-green-500 mr-2 mt-1">✓</span>当法人ロゴの使用権</li>
                        </ul>
                        <a href="#contact" class="w-full text-center bg-gray-200 text-gray-800 font-bold py-3 rounded-lg hover:bg-gray-300 transition-colors">詳しく聞く</a>
                    </div>

                    <!-- Silver Plan -->
                    <div class="bg-white rounded-lg shadow-xl p-8 border-t-4 border-gray-400 transform lg:scale-110 flex flex-col">
                        <p class="text-center font-bold bg-gray-400 text-white py-1 px-4 rounded-full w-fit mx-auto -mt-12 mb-4">一番人気</p>
                        <h3 class="text-2xl font-bold text-center mb-2">シルバー会員</h3>
                        <p class="text-center text-4xl font-bold my-4">20<span class="text-xl">万円/年</span></p>
                        <ul class="space-y-4 text-gray-600 mb-8 flex-grow">
                             <li class="flex items-start"><span class="text-green-500 mr-2 mt-1">✓</span>ブロンズ会員の全メリット</li>
                            <li class="flex items-start"><span class="text-green-500 mr-2 mt-1">✓</span>登録ダンサーへのDM発信（年2回）</li>
                            <li class="flex items-start"><span class="text-green-500 mr-2 mt-1">✓</span>求職希望ダンサーのご紹介・ご推薦</li>
                        </ul>
                        <a href="#contact" class="w-full text-center bg-[#004d40] text-white font-bold py-3 rounded-lg hover:bg-[#00382e] transition-colors">詳しく聞く</a>
                    </div>
                    
                    <!-- Gold Plan -->
                    <div class="bg-white rounded-lg shadow-lg p-8 border-t-4 border-yellow-500 flex flex-col">
                        <h3 class="text-2xl font-bold text-center mb-2">ゴールド会員</h3>
                        <p class="text-center text-4xl font-bold my-4">50<span class="text-xl">万円/年</span></p>
                        <ul class="space-y-4 text-gray-600 mb-8 flex-grow">
                             <li class="flex items-start"><span class="text-green-500 mr-2 mt-1">✓</span>シルバー会員の全メリット</li>
                            <li class="flex items-start"><span class="text-green-500 mr-2 mt-1">✓</span>貴社とダンサーの共同イベント企画・実施</li>
                            <li class="flex items-start"><span class="text-green-500 mr-2 mt-1">✓</span>ダンサー市場に関する共同アンケート調査</li>
                        </ul>
                        <a href="#contact" class="w-full text-center bg-gray-200 text-gray-800 font-bold py-3 rounded-lg hover:bg-gray-300 transition-colors">詳しく聞く</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 5: About Us -->
        <section id="about" class="py-16 md:py-24 bg-white">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-800 mb-4">私たちについて</h2>
                     <p class="max-w-3xl mx-auto text-gray-600">私たちは、国際NGOの呼びかけと支援を受けて設立された、日本初のダンサー専門キャリア支援団体です。「ダンサーの人生に寄り添い、その経験を社会へとつなげる」ことを使命としています。</p>
                </div>
                <div class="max-w-3xl mx-auto">
                    <div class="border-b">
                        <button class="accordion-button w-full flex justify-between items-center py-5 text-left text-xl font-semibold">
                            <span>キャリアセミナーの開催</span>
                            <span class="accordion-icon transition-transform duration-300">▶</span>
                        </button>
                        <div class="accordion-content">
                            <p class="py-4 text-gray-600">自己分析、キャリアデザイン、PCスキル、税務の基礎知識など、ダンサーが社会で活躍するための実践的な学びの場を提供します。</p>
                        </div>
                    </div>
                    <div class="border-b">
                        <button class="accordion-button w-full flex justify-between items-center py-5 text-left text-xl font-semibold">
                            <span>個別キャリアカウンセリング</span>
                            <span class="accordion-icon transition-transform duration-300">▶</span>
                        </button>
                        <div class="accordion-content">
                            <p class="py-4 text-gray-600">専門のカウンセラーが一人ひとりと向き合い、適性や希望に合わせた進路選択や転職活動を丁寧にサポートします。</p>
                        </div>
                    </div>
                    <div class="border-b">
                        <button class="accordion-button w-full flex justify-between items-center py-5 text-left text-xl font-semibold">
                            <span>大学・企業・団体との連携支援</span>
                             <span class="accordion-icon transition-transform duration-300">▶</span>
                        </button>
                        <div class="accordion-content">
                            <p class="py-4 text-gray-600">ダンサーの経験が活きる多様な道筋を創出するため、企業研修や交流会、採用マッチングの機会を積極的に開拓します。</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer & Contact -->
    <footer id="contact" class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-16 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-4">ダンサーの可能性を、共に社会へ。</h2>
            <p class="max-w-3xl mx-auto mb-8">貴社からのご支援が、一人のダンサーの人生を支え、その才能を社会の力へと変える大きな一歩となります。持続可能な芸術社会の実現に向け、ご協力を心よりお願い申し上げます。</p>
            <div class="bg-white text-gray-800 rounded-lg p-8 max-w-2xl mx-auto">
                <h3 class="text-2xl font-bold mb-4">ご興味のある企業様は、まずはお気軽にご連絡ください。</h3>
                <p class="text-lg mb-2">一般社団法人ダンサーズキャリアサポート（DCS）</p>
                <p class="mb-4">
                    <a href="mailto:info@dancerscareer.jp" class="text-blue-600 hover:underline">info@dancerscareer.jp</a>
                </p>
                <a href="http://www.dancerscareer.jp" target="_blank" rel="noopener noreferrer" class="inline-block bg-[#004d40] text-white font-bold py-3 px-8 rounded-lg hover:bg-[#00382e] transition-colors">
                    公式サイトへ
                </a>
            </div>
        </div>
        <div class="bg-gray-900 py-4">
            <p class="text-center text-sm text-gray-400">&copy; 2025 Dancer's Career Support. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Mobile menu toggle
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });

            // Accordion functionality
            const accordionButtons = document.querySelectorAll('.accordion-button');
            accordionButtons.forEach(button => {
                button.addEventListener('click', () => {
                    const currentlyActive = document.querySelector('.accordion-button.active');
                    if (currentlyActive && currentlyActive !== button) {
                        currentlyActive.classList.remove('active');
                        currentlyActive.querySelector('.accordion-icon').style.transform = 'rotate(0deg)';
                    }

                    button.classList.toggle('active');
                    const icon = button.querySelector('.accordion-icon');
                    if (button.classList.contains('active')) {
                        icon.style.transform = 'rotate(90deg)';
                    } else {
                        icon.style.transform = 'rotate(0deg)';
                    }
                });
            });

            // Chart.js Implementations
            const unemploymentCtx = document.getElementById('unemploymentChart')?.getContext('2d');
            if (unemploymentCtx) {
                new Chart(unemploymentCtx, {
                    type: 'doughnut',
                    data: {
                        labels: ['キャリア転換が必要', '現役継続'],
                        datasets: [{
                            data: [92.5, 7.5], // 90-95%の中間値
                            backgroundColor: ['#004d40', '#E5E7EB'],
                            borderColor: ['#FFFFFF'],
                            borderWidth: 4
                        }]
                    },
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        cutout: '70%',
                        plugins: {
                            legend: {
                                position: 'bottom',
                            },
                            tooltip: {
                                callbacks: {
                                    label: function(context) {
                                        return `${context.label}: ${context.raw}%`;
                                    }
                                }
                            }
                        }
                    }
                });
            }

            const populationCtx = document.getElementById('populationChart')?.getContext('2d');
            if (populationCtx) {
                new Chart(populationCtx, {
                    type: 'bar',
                    data: {
                        labels: ['2015', '2020', '2025 (予測)'],
                        datasets: [{
                            label: 'ダンス人口（万人）',
                            data: [600, 850, 1000],
                            backgroundColor: '#004d40',
                            borderRadius: 4
                        }]
                    },
                    options: {
                        responsive: true,
                        maintainAspectRatio: false,
                        plugins: {
                            legend: {
                                display: false
                            }
                        },
                        scales: {
                            y: {
                                beginAtZero: true,
                                title: {
                                    display: true,
                                    text: '人口（万人）'
                                }
                            }
                        }
                    }
                });
            }
        });
    </script>
</body>
</html>
