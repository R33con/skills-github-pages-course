<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taiwan Taste Journey | Exploring Taiwan's Culinary Heritage</title>
    <meta property="og:title" content="Taiwan Taste Journey">
    <meta property="og:description" content="Explore Taiwan's vibrant food culture from ancient traditions to bustling night markets">
    <meta property="og:image" content="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=taiwanese food with chopsticks&w=1200&h=630&style=realistic">
    <meta property="og:type" content="website">
    <link rel="icon" href="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=simple taiwanese food icon&w=32&h=32&transparent=true&style=pixel_art">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="/chat/cdn/animate.min.css" rel="stylesheet">
    <link href="/chat/cdn/aos.css" rel="stylesheet">
    <script src="/chat/cdn/aos.js"></script>
    <script src="/chat/cdn/papaparse.min.js"></script>
    
    <!-- Font Awesome -->
    <link href="/chat/cdn/all.min.css" rel="stylesheet">
    <script src="/chat/cdn/all.min.js" crossorigin></script>
    
    <style>
        @font-face {
            font-family: 'Font Awesome 6 Free';
            font-path: '/chat/webfonts/fa-regular-400';
            src: url('/chat/webfonts/fa-regular-400.woff2') format('woff2'),
                url('/chat/webfonts/fa-regular-400.ttf') format('truetype');
        }

        @font-face {
            font-family: 'Font Awesome 6 Free';
            font-path: '/chat/webfonts/fa-solid-900';
            src: url('/chat/webfonts/fa-solid-900.woff2') format('woff2'),
                url('/chat/webfonts/fa-solid-900.ttf') format('truetype');
        }

        @font-face {
            font-family: 'Font Awesome 6 Brands';
            font-path: '/chat/webfonts/fa-brands-400';
            src: url('/chat/webfonts/fa-brands-400.woff2') format('woff2'),
                url('/chat/webfonts/fa-brands-400.ttf') format('truetype');
        }
        
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        
        ::-webkit-scrollbar-thumb {
            background: #d32f2f;
            border-radius: 4px;
        }
        
        ::-webkit-scrollbar-thumb:hover {
            background: #b71c1c;
        }
        
        /* Ink brush effect for headings */
        .ink-brush {
            position: relative;
            display: inline-block;
        }
        
        .ink-brush::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #d32f2f;
            transform: scaleX(0.8) skewX(-12deg);
            transform-origin: bottom left;
        }
        
        /* Ancient scroll paper texture */
        .ancient-paper {
            background-image: url('https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=subtle ancient chinese paper texture light beige&w=800&h=800&style=realistic');
            background-repeat: repeat;
        }
        
        /* Chinese seal stamp effect */
        .seal-stamp {
            position: relative;
            overflow: hidden;
        }
        
        .seal-stamp::before {
            content: '';
            position: absolute;
            bottom: 10px;
            right: 10px;
            width: 80px;
            height: 80px;
            background-image: url('https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=traditional chinese red seal stamp with chinese characters&w=80&h=80&transparent=true&style=realistic');
            background-size: contain;
            background-repeat: no-repeat;
            opacity: 0.8;
            z-index: 10;
        }
    </style>
</head>
<body class="bg-amber-50 font-sans">
    <!-- Navigation -->
    <nav class="bg-red-800 text-white shadow-lg sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=chinese calligraphy brush logo for taiwan food blog&w=40&h=40&transparent=true&style=realistic" alt="Taiwan Taste Journey Logo" class="h-10">
                <span class="text-xl font-bold">Taiwan Taste Journey</span>
            </div>
            <div class="hidden md:flex space-x-8">
                <a href="#" class="hover:text-amber-200 transition duration-300">Home</a>
                <a href="#about" class="hover:text-amber-200 transition duration-300">About</a>
                <a href="#night-markets" class="hover:text-amber-200 transition duration-300">Night Markets</a>
                <a href="#recipes" class="hover:text-amber-200 transition duration-300">Recipes</a>
                <a href="#subscribe" class="hover:text-amber-200 transition duration-300">Subscribe</a>
            </div>
            <button class="md:hidden text-white focus:outline-none">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        <!-- Mobile menu (hidden by default) -->
        <div class="md:hidden hidden bg-red-900 px-4 py-2">
            <a href="#" class="block py-2 hover:text-amber-200 transition duration-300">Home</a>
            <a href="#about" class="block py-2 hover:text-amber-200 transition duration-300">About</a>
            <a href="#night-markets" class="block py-2 hover:text-amber-200 transition duration-300">Night Markets</a>
            <a href="#recipes" class="block py-2 hover:text-amber-200 transition duration-300">Recipes</a>
            <a href="#subscribe" class="block py-2 hover:text-amber-200 transition duration-300">Subscribe</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative h-screen flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 z-0">
            <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=vibrant taiwanese night market with food stalls and lanterns, cinematic lighting&w=1920&h=1080&style=realistic" alt="Taiwan Night Market" class="w-full h-full object-cover">
            <div class="absolute inset-0 bg-black bg-opacity-50"></div>
        </div>
        <div class="container mx-auto px-4 z-10 text-center">
            <h1 class="text-5xl md:text-7xl font-bold text-white mb-6 animate__animated animate__fadeInDown">Taiwan Taste Journey</h1>
            <p class="text-xl md:text-2xl text-amber-100 mb-8 max-w-3xl mx-auto animate__animated animate__fadeInUp">Exploring the rich tapestry of Taiwanese cuisine from ancient traditions to bustling night markets</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4 animate__animated animate__fadeInUp animate__delay-1s">
                <a href="#night-markets" class="bg-red-700 hover:bg-red-800 text-white font-bold py-3 px-6 rounded-lg transition duration-300 shadow-lg">Explore Night Markets</a>
                <a href="#recipes" class="bg-amber-600 hover:bg-amber-700 text-white font-bold py-3 px-6 rounded-lg transition duration-300 shadow-lg">Discover Recipes</a>
            </div>
        </div>
    </header>

    <!-- About Section with Ancient Chinese Art Influence -->
    <section id="about" class="py-16 ancient-paper">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="md:w-1/2" data-aos="fade-right">
                    <div class="relative">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=ancient chinese painting of people eating at a traditional feast&w=600&h=400&style=realistic" alt="Ancient Chinese Food Painting" class="rounded-lg shadow-xl w-full">
                        <div class="absolute -bottom-6 -right-6 w-32 h-32 bg-red-800 rounded-full flex items-center justify-center text-white text-center p-2 shadow-lg">
                            <span class="text-sm">Culinary Traditions Since 1600s</span>
                        </div>
                    </div>
                </div>
                <div class="md:w-1/2" data-aos="fade-left">
                    <h2 class="text-3xl font-bold mb-6 text-red-800 ink-brush">Our Story</h2>
                    <p class="text-lg mb-4 text-gray-800">Taiwan Taste Journey began as a personal exploration of the island's rich culinary heritage. What started as documenting family recipes has evolved into a comprehensive guide to Taiwan's diverse food landscape.</p>
                    <p class="text-lg mb-6 text-gray-800">Our blog celebrates the fusion of ancient Chinese cooking techniques with Japanese, Aboriginal, and modern influences that make Taiwanese cuisine truly unique.</p>
                    <div class="flex items-center space-x-4">
                        <div class="h-0.5 w-12 bg-red-800"></div>
                        <span class="text-red-800 font-semibold">Est. 2018</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Night Markets Section -->
    <section id="night-markets" class="py-16 bg-gray-900 text-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-amber-400 ink-brush" data-aos="fade-up">Famous Night Markets</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Night Market 1 -->
                <div class="rounded-lg overflow-hidden shadow-lg transition-transform duration-300 hover:scale-105" data-aos="fade-up" data-aos-delay="100">
                    <div class="relative h-64">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=shilin night market taipei taiwan with food stalls and crowds&w=600&h=400&style=realistic" alt="Shilin Night Market" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <h3 class="absolute bottom-4 left-4 text-2xl font-bold text-white">Shilin Night Market</h3>
                    </div>
                    <div class="p-6 bg-red-900">
                        <p class="mb-4">Taipei's largest and most famous night market, known for its diverse street food including giant fried chicken steaks and bubble tea.</p>
                        <div class="flex items-center justify-between">
                            <span class="text-amber-300"><i class="fas fa-map-marker-alt mr-2"></i>Taipei City</span>
                            <a href="#" class="text-white hover:text-amber-300 transition duration-300">Explore <i class="fas fa-arrow-right ml-1"></i></a>
                        </div>
                    </div>
                </div>
                
                <!-- Night Market 2 -->
                <div class="rounded-lg overflow-hidden shadow-lg transition-transform duration-300 hover:scale-105" data-aos="fade-up" data-aos-delay="200">
                    <div class="relative h-64">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=raohe street night market taipei with lanterns and food vendors&w=600&h=400&style=realistic" alt="Raohe Street Night Market" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <h3 class="absolute bottom-4 left-4 text-2xl font-bold text-white">Raohe Street Night Market</h3>
                    </div>
                    <div class="p-6 bg-red-900">
                        <p class="mb-4">One of Taipei's oldest night markets, famous for its pepper buns, oyster omelets, and traditional herbal medicine shops.</p>
                        <div class="flex items-center justify-between">
                            <span class="text-amber-300"><i class="fas fa-map-marker-alt mr-2"></i>Taipei City</span>
                            <a href="#" class="text-white hover:text-amber-300 transition duration-300">Explore <i class="fas fa-arrow-right ml-1"></i></a>
                        </div>
                    </div>
                </div>
                
                <!-- Night Market 3 -->
                <div class="rounded-lg overflow-hidden shadow-lg transition-transform duration-300 hover:scale-105" data-aos="fade-up" data-aos-delay="300">
                    <div class="relative h-64">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=liuhe night market kaohsiung taiwan with seafood stalls&w=600&h=400&style=realistic" alt="Liuhe Night Market" class="w-full h-full object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-70"></div>
                        <h3 class="absolute bottom-4 left-4 text-2xl font-bold text-white">Liuhe Night Market</h3>
                    </div>
                    <div class="p-6 bg-red-900">
                        <p class="mb-4">Kaohsiung's premier night market, specializing in fresh seafood dishes and southern Taiwanese delicacies.</p>
                        <div class="flex items-center justify-between">
                            <span class="text-amber-300"><i class="fas fa-map-marker-alt mr-2"></i>Kaohsiung City</span>
                            <a href="#" class="text-white hover:text-amber-300 transition duration-300">Explore <i class="fas fa-arrow-right ml-1"></i></a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="inline-block bg-amber-600 hover:bg-amber-700 text-white font-bold py-3 px-8 rounded-lg transition duration-300 shadow-lg">View All Night Markets</a>
            </div>
        </div>
    </section>

    <!-- Featured Recipes Section with Ancient Chinese Art Elements -->
    <section id="recipes" class="py-16 ancient-paper">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-red-800 ink-brush" data-aos="fade-up">Signature Recipes</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <!-- Recipe 1 -->
                <div class="flex flex-col md:flex-row gap-6 items-center seal-stamp" data-aos="fade-right">
                    <div class="md:w-1/2">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=taiwanese beef noodle soup in traditional bowl&w=500&h=400&style=realistic" alt="Beef Noodle Soup" class="rounded-lg shadow-lg w-full">
                    </div>
                    <div class="md:w-1/2">
                        <h3 class="text-2xl font-bold mb-3 text-red-800">Taiwanese Beef Noodle Soup</h3>
                        <p class="text-gray-700 mb-4">A hearty bowl of tender beef, chewy noodles, and rich broth simmered with spices and aromatics. Taiwan's unofficial national dish.</p>
                        <div class="flex items-center space-x-4 mb-4">
                            <span class="flex items-center"><i class="fas fa-clock text-amber-600 mr-2"></i> 3 hours</span>
                            <span class="flex items-center"><i class="fas fa-signal text-amber-600 mr-2"></i> Medium</span>
                        </div>
                        <a href="#" class="inline-block bg-red-700 hover:bg-red-800 text-white font-bold py-2 px-4 rounded transition duration-300">View Recipe</a>
                    </div>
                </div>
                
                <!-- Recipe 2 -->
                <div class="flex flex-col md:flex-row gap-6 items-center seal-stamp" data-aos="fade-left">
                    <div class="md:w-1/2">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=taiwanese gua bao pork belly bun with peanuts and cilantro&w=500&h=400&style=realistic" alt="Gua Bao" class="rounded-lg shadow-lg w-full">
                    </div>
                    <div class="md:w-1/2">
                        <h3 class="text-2xl font-bold mb-3 text-red-800">Gua Bao (Taiwanese Pork Belly Buns)</h3>
                        <p class="text-gray-700 mb-4">Fluffy steamed buns filled with braised pork belly, pickled mustard greens, crushed peanuts, and fresh cilantro.</p>
                        <div class="flex items-center space-x-4 mb-4">
                            <span class="flex items-center"><i class="fas fa-clock text-amber-600 mr-2"></i> 2 hours</span>
                            <span class="flex items-center"><i class="fas fa-signal text-amber-600 mr-2"></i> Medium</span>
                        </div>
                        <a href="#" class="inline-block bg-red-700 hover:bg-red-800 text-white font-bold py-2 px-4 rounded transition duration-300">View Recipe</a>
                    </div>
                </div>
                
                <!-- Recipe 3 -->
                <div class="flex flex-col md:flex-row gap-6 items-center seal-stamp" data-aos="fade-right">
                    <div class="md:w-1/2">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=taiwanese bubble milk tea with tapioca pearls&w=500&h=400&style=realistic" alt="Bubble Milk Tea" class="rounded-lg shadow-lg w-full">
                    </div>
                    <div class="md:w-1/2">
                        <h3 class="text-2xl font-bold mb-3 text-red-800">Bubble Milk Tea</h3>
                        <p class="text-gray-700 mb-4">The iconic Taiwanese drink featuring strong black tea, creamy milk, and chewy tapioca pearls that has taken the world by storm.</p>
                        <div class="flex items-center space-x-4 mb-4">
                            <span class="flex items-center"><i class="fas fa-clock text-amber-600 mr-2"></i> 30 minutes</span>
                            <span class="flex items-center"><i class="fas fa-signal text-amber-600 mr-2"></i> Easy</span>
                        </div>
                        <a href="#" class="inline-block bg-red-700 hover:bg-red-800 text-white font-bold py-2 px-4 rounded transition duration-300">View Recipe</a>
                    </div>
                </div>
                
                <!-- Recipe 4 -->
                <div class="flex flex-col md:flex-row gap-6 items-center seal-stamp" data-aos="fade-left">
                    <div class="md:w-1/2">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=taiwanese stinky tofu with pickled vegetables&w=500&h=400&style=realistic" alt="Stinky Tofu" class="rounded-lg shadow-lg w-full">
                    </div>
                    <div class="md:w-1/2">
                        <h3 class="text-2xl font-bold mb-3 text-red-800">Stinky Tofu</h3>
                        <p class="text-gray-700 mb-4">A notorious Taiwanese delicacy of fermented tofu, deep-fried until crispy and served with pickled vegetables and spicy sauce.</p>
                        <div class="flex items-center space-x-4 mb-4">
                            <span class="flex items-center"><i class="fas fa-clock text-amber-600 mr-2"></i> 1 hour</span>
                            <span class="flex items-center"><i class="fas fa-signal text-amber-600 mr-2"></i> Medium</span>
                        </div>
                        <a href="#" class="inline-block bg-red-700 hover:bg-red-800 text-white font-bold py-2 px-4 rounded transition duration-300">View Recipe</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Culinary Map Section -->
    <section class="py-16 bg-amber-100">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-red-800 ink-brush" data-aos="fade-up">Taiwan Culinary Map</h2>
            
            <div class="relative" data-aos="zoom-in">
                <div class="bg-white rounded-xl shadow-xl p-6 md:p-10 overflow-hidden">
                    <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=stylized map of taiwan with food icons marking different regions, ancient chinese painting style&w=1000&h=800&style=realistic" alt="Taiwan Culinary Map" class="w-full rounded-lg">
                    
                    <!-- Interactive hotspots would be added here with JavaScript -->
                    <div class="absolute top-1/4 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-red-800 text-white rounded-full w-8 h-8 flex items-center justify-center cursor-pointer shadow-lg hover:bg-red-700 transition duration-300">
                        <i class="fas fa-utensils"></i>
                    </div>
                    
                    <div class="absolute top-2/3 left-1/4 transform -translate-x-1/2 -translate-y-1/2 bg-red-800 text-white rounded-full w-8 h-8 flex items-center justify-center cursor-pointer shadow-lg hover:bg-red-700 transition duration-300">
                        <i class="fas fa-fish"></i>
                    </div>
                    
                    <div class="absolute top-1/2 right-1/4 transform translate-x-1/2 -translate-y-1/2 bg-red-800 text-white rounded-full w-8 h-8 flex items-center justify-center cursor-pointer shadow-lg hover:bg-red-700 transition duration-300">
                        <i class="fas fa-pepper-hot"></i>
                    </div>
                </div>
                
                <div class="mt-8 text-center">
                    <p class="text-gray-700">Explore Taiwan's diverse regional cuisines from north to south</p>
                    <a href="#" class="inline-block mt-4 text-red-800 font-bold hover:text-red-900 transition duration-300">View Interactive Map <i class="fas fa-arrow-right ml-1"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials with Ancient Chinese Scroll Design -->
    <section class="py-16 bg-red-900 text-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-center mb-12 text-amber-300 ink-brush" data-aos="fade-up">What Our Readers Say</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-red-800 rounded-lg p-6 shadow-lg relative" data-aos="fade-up" data-aos-delay="100">
                    <div class="absolute -top-5 left-1/2 transform -translate-x-1/2 bg-amber-500 rounded-full w-10 h-10 flex items-center justify-center">
                        <i class="fas fa-quote-left text-red-900"></i>
                    </div>
                    <p class="mt-4 mb-6 italic">"This blog helped me recreate the authentic flavors of Taiwan at home. The beef noodle soup recipe is exactly like what I had in Taipei!"</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4">
                            <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=profile photo of asian woman smiling&w=100&h=100&style=realistic" alt="Sarah Chen" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold">Sarah Chen</h4>
                            <p class="text-amber-300 text-sm">Food Enthusiast</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-red-800 rounded-lg p-6 shadow-lg relative" data-aos="fade-up" data-aos-delay="200">
                    <div class="absolute -top-5 left-1/2 transform -translate-x-1/2 bg-amber-500 rounded-full w-10 h-10 flex items-center justify-center">
                        <i class="fas fa-quote-left text-red-900"></i>
                    </div>
                    <p class="mt-4 mb-6 italic">"The night market guides are incredibly detailed. I used them on my trip to Taiwan and discovered amazing food stalls I would have otherwise missed!"</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4">
                            <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=profile photo of caucasian man with glasses&w=100&h=100&style=realistic" alt="Michael Johnson" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold">Michael Johnson</h4>
                            <p class="text-amber-300 text-sm">Travel Blogger</p>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-red-800 rounded-lg p-6 shadow-lg relative" data-aos="fade-up" data-aos-delay="300">
                    <div class="absolute -top-5 left-1/2 transform -translate-x-1/2 bg-amber-500 rounded-full w-10 h-10 flex items-center justify-center">
                        <i class="fas fa-quote-left text-red-900"></i>
                    </div>
                    <p class="mt-4 mb-6 italic">"I love how this blog connects modern Taiwanese cuisine with its ancient Chinese roots. The historical context makes the recipes even more special."</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 rounded-full overflow-hidden mr-4">
                            <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=profile photo of latina woman with curly hair&w=100&h=100&style=realistic" alt="Elena Rodriguez" class="w-full h-full object-cover">
                        </div>
                        <div>
                            <h4 class="font-bold">Elena Rodriguez</h4>
                            <p class="text-amber-300 text-sm">Culinary Historian</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Subscribe Section with Chinese Art Elements -->
    <section id="subscribe" class="py-16 ancient-paper">
        <div class="container mx-auto px-4">
            <div class="max-w-3xl mx-auto text-center">
                <h2 class="text-4xl font-bold mb-6 text-red-800 ink-brush" data-aos="fade-up">Join Our Culinary Journey</h2>
                <p class="text-lg mb-8 text-gray-800" data-aos="fade-up" data-aos-delay="100">Subscribe to receive our latest recipes, night market guides, and exclusive cooking tips directly to your inbox.</p>
                
                <div class="bg-white p-8 rounded-lg shadow-xl relative overflow-hidden" data-aos="fade-up" data-aos-delay="200">
                    <!-- Decorative elements -->
                    <div class="absolute top-0 left-0 w-16 h-16">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=chinese brush painting corner decoration with red ink&w=100&h=100&transparent=true&style=realistic" alt="Decoration" class="w-full">
                    </div>
                    <div class="absolute bottom-0 right-0 w-16 h-16">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=chinese brush painting corner decoration with red ink&w=100&h=100&transparent=true&style=realistic" alt="Decoration" class="w-full transform rotate-180">
                    </div>
                    
                    <form class="relative z-10">
                        <div class="flex flex-col sm:flex-row gap-4">
                            <input type="email" placeholder="Your email address" class="flex-grow px-4 py-3 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-red-800">
                            <button type="submit" class="bg-red-800 hover:bg-red-900 text-white font-bold py-3 px-6 rounded-lg transition duration-300 shadow-lg">Subscribe</button>
                        </div>
                        <div class="mt-4 text-left">
                            <label class="flex items-center text-gray-700">
                                <input type="checkbox" class="mr-2">
                                <span>I agree to receive email updates and promotions</span>
                            </label>
                        </div>
                    </form>
                </div>
                
                <div class="mt-8 flex justify-center space-x-6" data-aos="fade-up" data-aos-delay="300">
                    <a href="#" class="text-red-800 hover:text-red-900 transition duration-300">
                        <i class="fab fa-instagram text-3xl"></i>
                    </a>
                    <a href="#" class="text-red-800 hover:text-red-900 transition duration-300">
                        <i class="fab fa-facebook text-3xl"></i>
                    </a>
                    <a href="#" class="text-red-800 hover:text-red-900 transition duration-300">
                        <i class="fab fa-youtube text-3xl"></i>
                    </a>
                    <a href="#" class="text-red-800 hover:text-red-900 transition duration-300">
                        <i class="fab fa-pinterest text-3xl"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer with Chinese Art Elements -->
    <footer class="bg-red-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">Taiwan Taste Journey</h3>
                    <p class="mb-4">Exploring Taiwan's rich culinary heritage through recipes, stories, and guides.</p>
                    <div class="flex items-center">
                        <img src="https://cdn.simulationtheory.ai/gasset/?asset=img&prompt=chinese calligraphy brush logo for taiwan food blog&w=40&h=40&transparent=true&style=realistic" alt="Taiwan Taste Journey Logo" class="h-10 mr-2">
                        <span>Est. 2018</span>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">Explore</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-amber-300 transition duration-300">Home</a></li>
                        <li><a href="#about" class="hover:text-amber-300 transition duration-300">About Us</a></li>
                        <li><a href="#night-markets" class="hover:text-amber-300 transition duration-300">Night Markets</a></li>
                        <li><a href="#recipes" class="hover:text-amber-300 transition duration-300">Recipes</a></li>
                        <li><a href="#" class="hover:text-amber-300 transition duration-300">Travel Guides</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">Categories</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-amber-300 transition duration-300">Street Food</a></li>
                        <li><a href="#" class="hover:text-amber-300 transition duration-300">Traditional Dishes</a></li>
                        <li><a href="#" class="hover:text-amber-300 transition duration-300">Desserts & Drinks</a></li>
                        <li><a href="#" class="hover:text-amber-300 transition duration-300">Vegetarian</a></li>
                        <li><a href="#" class="hover:text-amber-300 transition duration-300">Seafood</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">Contact</h3>
                    <ul class="space-y-2">
                        <li class="flex items-center"><i class="fas fa-envelope mr-2 text-amber-300"></i> info@taiwantastejourney.com</li>
                        <li class="flex items-center"><i class="fas fa-phone mr-2 text-amber-300"></i> +886 2 1234 5678</li>
                        <li class="flex items-center"><i class="fas fa-map-marker-alt mr-2 text-amber-300"></i> Taipei, Taiwan</li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-red-800 mt-8 pt-8 text-center">
                <p>&copy; 2023 Taiwan Taste Journey. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // Initialize AOS animation library
            AOS.init({
                duration: 800,
                once: true
            });
            
            // Mobile menu toggle
            const menuButton = document.querySelector('nav button');
            const mobileMenu = document.querySelector('nav .md\\:hidden');
            
            menuButton.addEventListener('click', function() {
                mobileMenu.classList.toggle('hidden');
            });
            
            // Smooth scrolling for anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function(e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href');
                    if (targetId === '#') return;
                    
                    const targetElement = document.querySelector(targetId);
                    if (targetElement) {
                        window.scrollTo({
                            top: targetElement.offsetTop - 80,
                            behavior: 'smooth'
                        });
                        
                        // Close mobile menu if open
                        if (!mobileMenu.classList.contains('hidden')) {
                            mobileMenu.classList.add('hidden');
                        }
                    }
                });
            });
            
            // Newsletter subscription form handling
            const subscribeForm = document.querySelector('#subscribe form');
            if (subscribeForm) {
                subscribeForm.addEventListener('submit', function(e) {
                    e.preventDefault();
                    
                    const emailInput = this.querySelector('input[type="email"]');
                    const email = emailInput.value.trim();
                    
                    if (!email || !email.includes('@')) {
                        alert('Please enter a valid email address');
                        return;
                    }
                    
                    // Save subscription data
                    const subscriptionData = [
                        {
                            email: email,
                            date: new Date().toISOString(),
                            source: 'website_landing_page'
                        }
                    ];
                    
                    window.save_data_to_csv('newsletter_subscribers.csv', subscriptionData);
                    
                    // Show success message
                    emailInput.value = '';
                    alert('Thank you for subscribing to Taiwan Taste Journey!');
                    
                    // Get personalized welcome message from LLM
                    window.call_llm(
                        'You are a friendly food blog assistant. Create a personalized welcome message for a new subscriber to a Taiwan food blog. Keep it short (2-3 sentences), friendly, and mention one interesting fact about Taiwanese cuisine.',
                        [{"role": "user", "content": `Create welcome message for new subscriber with email ${email}`}],
                        [{"welcome_message": "A personalized welcome message for the new subscriber"}]
                    ).then(response => {
                        if (response && response.welcome_message) {
                            // Display the welcome message
                            const welcomeDiv = document.createElement('div');
                            welcomeDiv.className = 'mt-4 p-3 bg-amber-100 text-red-800 rounded-lg animate__animated animate__fadeIn';
                            welcomeDiv.textContent = response.welcome_message;
                            subscribeForm.parentNode.appendChild(welcomeDiv);
                            
                            // Remove the message after 10 seconds
                            setTimeout(() => {
                                welcomeDiv.classList.add('animate__fadeOut');
                                setTimeout(() => welcomeDiv.remove(), 1000);
                            }, 10000);
                        }
                    }).catch(error => {
                        console.error('Error getting welcome message:', error);
                    });
                });
            }
        });
    </script>
</body>
</html>
