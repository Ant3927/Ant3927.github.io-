# Ant3927.github.io-
# index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AP Computer Science Principles Portfolio</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        forest: '#1b4332',      /* Forest Green */
                        lightgreen: '#d8f3dc',  /* Light Green */
                        orangeAccent: '#f97316', /* Bright Orange */
                        deepblack: '#0b0f19',   /* Rich Black */
                        cardblack: '#161b26'    /* Card Black */
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0b0f19;
        }
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0b0f19;
        }
        ::-webkit-scrollbar-thumb {
            background: #1b4332;
            border-radius: 9999px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #f97316;
        }
    </style>
</head>
<body class="text-gray-100 min-h-screen flex flex-col selection:bg-orangeAccent selection:text-black">

    <!-- Header / Navigation -->
    <header class="sticky top-0 z-50 bg-deepblack/95 backdrop-blur-md border-b border-forest/30">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-forest to-orangeAccent flex items-center justify-center font-bold text-xl text-black shadow-lg">
                    AP
                </div>
                <div>
                    <h1 class="text-lg font-bold tracking-tight text-white">Anthony's Coding Space</h1>
                    <p class="text-xs text-orangeAccent font-medium tracking-wide uppercase">AP CSP Final Portfolio</p>
                </div>
            </div>
            <nav class="hidden md:flex items-center space-x-8">
                <a href="#about" class="text-sm font-medium hover:text-orangeAccent transition duration-200">About Me</a>
                <a href="#projects" class="text-sm font-medium hover:text-orangeAccent transition duration-200">My Apps</a>
                <a href="#standards" class="text-sm font-medium hover:text-orangeAccent transition duration-200">AP CSP Standards</a>
                <a href="#feedback" class="text-sm font-medium hover:text-orangeAccent transition duration-200">Peer Feedback</a>
            </nav>
            <a href="#projects" class="inline-flex items-center justify-center px-4 py-2 text-xs font-semibold tracking-wider text-black bg-orangeAccent hover:bg-orangeAccent/90 rounded-xl transition duration-300 transform hover:-translate-y-0.5">
                LAUNCH APPS
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="about" class="relative py-20 lg:py-28 overflow-hidden border-b border-forest/20">
        <!-- Abstract Background Shapes -->
        <div class="absolute top-1/4 left-1/10 w-96 h-96 bg-forest/20 rounded-full blur-3xl -z-10"></div>
        <div class="absolute bottom-1/4 right-1/10 w-80 h-80 bg-orangeAccent/10 rounded-full blur-3xl -z-10"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-semibold bg-forest/40 text-lightgreen border border-forest">
                        <span class="w-2 h-2 rounded-full bg-orangeAccent mr-2 animate-pulse"></span>
                        College Board Compliant Portfolio
                    </span>
                    <h2 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight text-white leading-none">
                        Building Solutions, <br class="hidden sm:inline">
                        <span class="text-transparent bg-clip-text bg-gradient-to-r from-lightgreen via-orangeAccent to-forest">
                            Line by Line.
                        </span>
                    </h2>
                    <p class="text-gray-300 text-lg max-w-xl mx-auto lg:mx-0">
                        Welcome to my AP Computer Science Principles creative workspace. This portfolio showcases three applications built during the school year, using event-driven programming, data abstraction, and complex algorithmic logic in Code.org's App Lab.
                    </p>
                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-4">
                        <a href="#projects" class="w-full sm:w-auto px-6 py-3 text-center text-sm font-semibold text-black bg-orangeAccent hover:bg-orange-600 rounded-xl transition duration-200 shadow-lg shadow-orangeAccent/20">
                            Explore Apps
                        </a>
                        <a href="#standards" class="w-full sm:w-auto px-6 py-3 text-center text-sm font-semibold text-white bg-cardblack hover:bg-cardblack/80 border border-forest/50 rounded-xl transition duration-200">
                            View Written Responses
                        </a>
                    </div>
                </div>
                
                <!-- Quick Stats / Feature Graphic -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-4">
                    <div class="p-6 rounded-2xl bg-cardblack/50 border border-forest/30 hover:border-forest/70 transition duration-300">
                        <div class="text-orangeAccent font-bold text-4xl mb-2">3</div>
                        <div class="text-white font-semibold text-sm">Working Apps</div>
                        <p class="text-xs text-gray-400 mt-1">Ready to test and play right inside the browser window.</p>
                    </div>
                    <div class="p-6 rounded-2xl bg-cardblack/50 border border-forest/30 hover:border-forest/70 transition duration-300">
                        <div class="text-lightgreen font-bold text-4xl mb-2">100%</div>
                        <div class="text-white font-semibold text-sm">Create Task Ready</div>
                        <p class="text-xs text-gray-400 mt-1">Conforms with College Board's algorithm & abstraction rubrics.</p>
                    </div>
                    <div class="p-6 rounded-2xl bg-cardblack/50 border border-forest/30 hover:border-forest/70 transition duration-300 col-span-2">
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-xs font-semibold text-orangeAccent tracking-wider uppercase">Tech Stack Overview</span>
                            <span class="text-[10px] text-gray-500 bg-black/40 px-2 py-0.5 rounded-md">AP CSP App Lab</span>
                        </div>
                        <div class="flex flex-wrap gap-2">
                            <span class="text-xs px-2.5 py-1 rounded-lg bg-black text-lightgreen border border-forest/40">JavaScript</span>
                            <span class="text-xs px-2.5 py-1 rounded-lg bg-black text-lightgreen border border-forest/40">UI Design</span>
                            <span class="text-xs px-2.5 py-1 rounded-lg bg-black text-lightgreen border border-forest/40">Data Lists</span>
                            <span class="text-xs px-2.5 py-1 rounded-lg bg-black text-lightgreen border border-forest/40">Conditional Logic</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Dynamic Project Section -->
    <main id="projects" class="py-20 bg-deepblack relative flex-grow">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-orangeAccent text-xs font-bold tracking-widest uppercase">The Interactive Showcase</span>
                <h3 class="text-3xl sm:text-4xl font-extrabold text-white mt-2">Check Out My Projects</h3>
                <p class="text-gray-400 mt-3">Select a project below to interact with the emulator, view its core purpose, and study the AP CSP Create Task technical write-up.</p>
            </div>

            <!-- Project Selector Tabs -->
            <div class="flex flex-wrap justify-center gap-2 mb-12 p-1.5 bg-cardblack rounded-2xl border border-forest/30 max-w-3xl mx-auto">
                <button onclick="switchApp(1)" id="tab-btn-1" class="flex-1 min-w-[200px] text-center py-3 px-4 rounded-xl font-semibold text-sm transition-all duration-300 bg-orangeAccent text-black shadow-lg">
                    🇺🇸 National Park Picker
                </button>
                <button onclick="switchApp(2)" id="tab-btn-2" class="flex-1 min-w-[200px] text-center py-3 px-4 rounded-xl font-semibold text-sm transition-all duration-300 text-gray-400 hover:text-white hover:bg-forest/20">
                    🏃‍♂️ Mile Tracker
                </button>
                <button onclick="switchApp(3)" id="tab-btn-3" class="flex-1 min-w-[200px] text-center py-3 px-4 rounded-xl font-semibold text-sm transition-all duration-300 text-gray-400 hover:text-white hover:bg-forest/20">
                    📱 Lock-Screen Gen
                </button>
            </div>

            <!-- Main App Showcase Split Layout -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                
                <!-- LEFT SIDE: Responsive Mobile Device Simulator -->
                <div class="lg:col-span-5 flex flex-col items-center">
                    <div class="relative mx-auto border-[12px] border-cardblack bg-deepblack rounded-[3rem] shadow-2xl shadow-forest/20 overflow-hidden w-[340px] h-[580px] sm:w-[416px] sm:h-[670px] transition-all duration-500 hover:shadow-orangeAccent/15">
                        <!-- Phone Notch Speaker -->
                        <div class="absolute top-0 inset-x-0 h-4 bg-cardblack flex justify-center z-20">
                            <div class="w-24 h-4 bg-black rounded-b-xl"></div>
                        </div>
                        
                        <!-- Embed App Frame Container -->
                        <div class="w-full h-full pt-4 bg-[#1e293b]">
                            <!-- App 1 Embed -->
                            <div id="embed-container-1" class="w-full h-full block">
                                <iframe class="w-full h-full border-0 rounded-b-[2rem]" src="https://studio.code.org/projects/applab/aa157013-9d5c-44bd-ba46-13f385341e1b/embed" allowfullscreen></iframe>
                            </div>
                            <!-- App 2 Embed -->
                            <div id="embed-container-2" class="w-full h-full hidden">
                                <iframe class="w-full h-full border-0 rounded-b-[2rem]" src="https://studio.code.org/projects/applab/0956fdae-f490-44f4-a45a-43dfd28f2ece/embed" allowfullscreen></iframe>
                            </div>
                            <!-- App 3 Embed -->
                            <div id="embed-container-3" class="w-full h-full hidden">
                                <iframe class="w-full h-full border-0 rounded-b-[2rem]" src="https://studio.code.org/projects/applab/24302c69-cdcd-4933-8b3c-45784c37e083/embed" allowfullscreen></iframe>
                            </div>
                        </div>
                    </div>
                    <p class="text-xs text-gray-500 mt-4 italic text-center">
                        🔒 Secure live sandbox compiled and rendered via Code.org App Lab.
                    </p>
                </div>

                <!-- RIGHT SIDE: Information, Documentation, & Written Responses -->
                <div class="lg:col-span-7 space-y-6">
                    
                    <!-- App Metadata Header -->
                    <div class="p-6 rounded-2xl bg-cardblack border border-forest/30">
                        <div class="flex items-center justify-between">
                            <span id="app-tag" class="text-xs font-bold uppercase tracking-wider text-orangeAccent">Interactive Utility</span>
                            <span class="text-xs text-gray-400 flex items-center gap-1">
                                <span class="w-2 h-2 rounded-full bg-emerald-500"></span> Live Emulator Available
                            </span>
                        </div>
                        <h4 id="app-title" class="text-2xl font-bold text-white mt-2">U.S. National Park Picker</h4>
                        <p id="app-desc" class="text-gray-300 mt-2 text-sm leading-relaxed">
                            An easy-to-use directory and planning aid designed to help lovers of the outdoors find national parks suited to their geographical preferences, activities, and seasonal travel goals. It functions, but sadly not fully.
                        </p>
                    </div>

                    <!-- AP CSP WRITTEN RESPONSES ACCORDION -->
                    <div id="standards" class="space-y-4">
                        <h5 class="text-sm font-semibold tracking-wider text-lightgreen uppercase mb-2">AP CSP Create Task Written Responses</h5>
                        
                        <!-- Response 1: Purpose & Function -->
                        <div class="rounded-xl border border-forest/20 bg-cardblack/40 overflow-hidden">
                            <button onclick="toggleAccordion('acc-1')" class="w-full px-5 py-4 flex items-center justify-between text-left font-medium text-sm text-white hover:bg-forest/10 transition">
                                <span class="flex items-center gap-2">
                                    <span class="text-xs font-bold px-2 py-0.5 rounded bg-orangeAccent text-black">3A</span>
                                    Program Purpose and Function
                                </span>
                                <svg id="acc-icon-acc-1" class="w-5 h-5 text-gray-400 transform transition-transform duration-200" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                                </svg>
                            </button>
                            <div id="acc-1" class="hidden px-5 pb-5 pt-1 text-xs text-gray-300 space-y-3 leading-relaxed border-t border-forest/10">
                                <p><strong>Program Purpose:</strong> <span id="writeup-purpose">To streamline the process of finding and researching U.S. National Parks based on localized geographical data and recreation criteria.</span></p>
                                <p><strong>Program Function:</strong> <span id="writeup-function">The program presents the user with state-by-state selection filters. When choices are locked in, the program queries an internal database schema to serve the optimal national park recommendation alongside its key travel details.</span></p>
                                <p><strong>Input & Output:</strong> <span id="writeup-io">The inputs are the user's dropdown and button click selections. The output is a dynamically populated details screen showcasing matching park images, descriptions, and state metadata.</span></p>
                            </div>
                        </div>

                        <!-- Response 2: Data Abstraction -->
                        <div class="rounded-xl border border-forest/20 bg-cardblack/40 overflow-hidden">
                            <button onclick="toggleAccordion('acc-2')" class="w-full px-5 py-4 flex items-center justify-between text-left font-medium text-sm text-white hover:bg-forest/10 transition">
                                <span class="flex items-center gap-2">
                                    <span class="text-xs font-bold px-2 py-0.5 rounded bg-orangeAccent text-black">3B</span>
                                    Data Abstraction & Lists
                                </span>
                                <svg id="acc-icon-acc-2" class="w-5 h-5 text-gray-400 transform transition-transform duration-200" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                                </svg>
                            </button>
                            <div id="acc-2" class="hidden px-5 pb-5 pt-1 text-xs text-gray-300 space-y-3 leading-relaxed border-t border-forest/10">
                                <p><strong>List Structure:</strong> <span id="writeup-list-name">The list is named <code>parkDatabaseList</code> or similar array structures in App Lab.</span></p>
                                <p><strong>List Content:</strong> <span id="writeup-list-content">It contains indices storing detailed objects or arrays mapping park locations, photos, and descriptions.</span></p>
                                <p><strong>Managing Complexity:</strong> <span id="writeup-complexity">Without this list, the program would require dozens of standalone variables to keep track of individual park records, making scaling nearly impossible and causing extreme code duplication across screen states.</span></p>
                            </div>
                        </div>

                        <!-- Response 3: Managing Complexity -->
                        <div class="rounded-xl border border-forest/20 bg-cardblack/40 overflow-hidden">
                            <button onclick="toggleAccordion('acc-3')" class="w-full px-5 py-4 flex items-center justify-between text-left font-medium text-sm text-white hover:bg-forest/10 transition">
                                <span class="flex items-center gap-2">
                                    <span class="text-xs font-bold px-2 py-0.5 rounded bg-orangeAccent text-black">3C</span>
                                    Managing Complexity & Logic
                                </span>
                                <svg id="acc-icon-acc-3" class="w-5 h-5 text-gray-400 transform transition-transform duration-200" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                                </svg>
                            </button>
                            <div id="acc-3" class="hidden px-5 pb-5 pt-1 text-xs text-gray-300 space-y-3 leading-relaxed border-t border-forest/10">
                                <p><strong>Algorithm Mechanics:</strong> <span id="writeup-algorithm">Our algorithms use conditional statements, sequential updates, and iteration to loop through data. It compares the state code matching the user's selector dynamically and isolates matching items.</span></p>
                                <p><strong>Conditional Statements:</strong> <span id="writeup-conditionals">The program relies on <code>if/else</code> logic trees to confirm a match exists before trying to access index-based indices, preventing application crashes.</span></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Project Peer Review & Feedback Section -->
    <section id="feedback" class="py-16 bg-cardblack relative border-t border-forest/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                <!-- Left Side: Interactive Mock Review Form -->
                <div class="lg:col-span-5 space-y-6">
                    <div>
                        <span class="text-xs font-bold tracking-wider text-orangeAccent uppercase">Collaborative Development</span>
                        <h3 class="text-2xl font-bold text-white mt-1">Leave App Peer Feedback</h3>
                        <p class="text-sm text-gray-400 mt-2">
                            In AP Computer Science Principles, collaboration and peer testing are key. Leave your thoughts, bug reports, or feature ideas below!
                        </p>
                    </div>

                    <form id="feedback-form" onsubmit="addFeedback(event)" class="space-y-4">
                        <div>
                            <label class="block text-xs font-medium text-gray-300 mb-1">Your Name</label>
                            <input id="feedback-name" type="text" placeholder="e.g. Mr. Herzek (AP CSP Teacher)" required class="w-full bg-deepblack border border-forest/40 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:ring-2 focus:ring-orangeAccent/50 transition">
                        </div>
                        <div>
                            <label class="block text-xs font-medium text-gray-300 mb-1">Which App did you test?</label>
                            <select id="feedback-app" class="w-full bg-deepblack border border-forest/40 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:ring-2 focus:ring-orangeAccent/50 transition">
                                <option value="U.S. National Park Picker">U.S. National Park Picker</option>
                                <option value="Mile Tracker">Mile Tracker</option>
                                <option value="Phone Lock-Screen Generator">Phone Lock-Screen Generator</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-medium text-gray-300 mb-1">Feedback & Recommendations</label>
                            <textarea id="feedback-text" rows="4" placeholder="Share your suggestions, code analysis, or design critiques..." required class="w-full bg-deepblack border border-forest/40 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:ring-2 focus:ring-orangeAccent/50 transition"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3 bg-forest hover:bg-forest/80 text-lightgreen text-sm font-semibold rounded-xl border border-forest hover:border-lightgreen/30 transition-all duration-200">
                            Submit Peer Review
                        </button>
                    </form>
                </div>

                <!-- Right Side: Recent Peer Reviews List -->
                <div class="lg:col-span-7 flex flex-col justify-between">
                    <div>
                        <h4 class="text-lg font-bold text-white mb-4">Recent Portfolio Reviews</h4>
                        <div id="feedback-list" class="space-y-4 max-h-[350px] overflow-y-auto pr-2">
                            <!-- Preloaded Feedback 1 -->
                         
                    <!-- Tech Standards Footnote -->
                    <div class="mt-8 p-4 rounded-xl bg-forest/10 border border-forest/30 flex items-start space-x-3">
                        <span class="p-2 rounded bg-orangeAccent/20 text-orangeAccent mt-0.5">💡</span>
                        <div>
                            <h5 class="text-xs font-semibold text-white">Development Note</h5>
                            <p class="text-[11px] text-gray-400 mt-1">This portfolio website utilizes semantic HTML5, utility CSS layouts, and adaptive JavaScript to create a premium simulation interface environment suited for standard high-definition screens.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Custom Footer -->
    <footer class="bg-deepblack border-t border-forest/30 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row items-center justify-between gap-6">
            <p class="text-xs text-gray-400">
                &copy; 2026 Alex's AP CSP Project Portfolio. All rights reserved. Built with passion & Code.org tools.
            </p>
            <div class="flex space-x-6 text-xs text-gray-400">
                <a href="#about" class="hover:text-orangeAccent transition">Top</a>
                <a href="#projects" class="hover:text-orangeAccent transition">Apps</a>
                <a href="#standards" class="hover:text-orangeAccent transition">AP Standards</a>
            </div>
        </div>
    </footer>

    <!-- App Dynamic Information Storage & Switching Scripts -->
    <script>
        // App dataset
        const appsData = {
            1: {
                title: "U.S. National Park Picker",
                tag: "Interactive Travel Planner",
                desc: "An easy-to-use directory and planning aid designed to help lovers of the outdoors find national parks suited to their geographical preferences, activities, and seasonal travel goals.",
                writeups: {
                    purpose: "To streamline the process of finding and researching U.S. National Parks based on localized geographical data and recreation criteria.",
                    function: "The program presents the user with state-by-state selection filters. When choices are locked in, the program queries an internal database schema to serve the optimal national park recommendation alongside its key travel details.",
                    io: "The inputs are the user's dropdown and button click selections. The output is a dynamically populated details screen showcasing matching park images, descriptions, and state metadata.",
                    listName: "parkDatabaseList or stateSelectionMap",
                    listContent: "It contains elements structured as indices mapping specific national park name strings, image URL pathing keys, and regional data attributes.",
                    complexity: "Without this centralized list structure, matching specific inputs with state-specific results would require dozens of nested 'if-else' logic chains and redundant variables for every park, yielding messy code that is impossible to expand.",
                    algorithm: "Our algorithm processes a dynamic input query. It initiates a search traversal loop across matching park datasets, compares local characteristics via relational database hooks, and isolates output payloads.",
                    conditionals: "The codebase utilizes condition trees to inspect if a park location matching the user selection possesses active trails or matching seasonal hours, safeguarding screen elements from rendering empty or invalid results."
                }
            },
            2: {
                title: "Mile Tracker",
                tag: "Sports & Fitness Tracker",
                desc: "A personal workout ledger created for high school cross-country runners and hikers to seamlessly document daily mileage, calculate split pace trends, and map visual goals.",
                writeups: {
                    purpose: "To assist athletes and coaches in tracking training progression, logging physical health stats, and managing structural workout targets.",
                    function: "The program prompts users to enter dates, distances, and run times. It logs the entries, processes calculations for average pace, and renders summary stats on a clean, centralized progress monitor.",
                    io: "The input consists of key-in numbers for miles completed, time metrics, and button selections. The output is calculated total running values and progress bars visualizing milestone completion percentages.",
                    listName: "runLogHistoryList",
                    listContent: "This dynamic list tracks sequential running records, capturing distance floats and corresponding speed milestones for consecutive user submissions.",
                    complexity: "The app employs this list to maintain historical trackings across multiple sessions. Without it, the app would only be capable of displaying the single most recent run, losing all historical metrics.",
                    algorithm: "The program implements an iterative summary algorithm that iterates over the runLogHistoryList, tallying total numbers to yield aggregate output stats and average metrics.",
                    conditionals: "Includes conditional checkpoints that trigger visual milestones and alert states once running totals surpass predefined user benchmarks (e.g., 50 miles total goal reached!)."
                }
            },
            3: {
                title: "Phone Lock-Screen Generator",
                tag: "Visual Design Utility",
                desc: "An intuitive graphic maker tool enabling creators to style, colorize, layout, and preview customized phone backgrounds instantly right inside their browser.",
                writeups: {
                    purpose: "To empower students and designers with a layout sandbox to draft and visualize clean phone lock-screens.",
                    function: "Users can tweak background gradients, layer stylized widgets, customize clock placements, and generate dynamic patterns. The app outputs real-time visual previews.",
                    io: "The input spans aesthetic selection buttons, text entry for customize quotes, and color picker dials. The output is the dynamically updated on-screen device wallpaper.",
                    listName: "layoutPresetStyleList",
                    listContent: "Stores a structured array of color palette parameters, layout themes, and default font configuration assets used to quickly swap system-wide looks.",
                    complexity: "Without this database, switching pre-defined style packages would require writing exhaustive line-by-line configuration functions for every single UI widget's size, color, and location properties.",
                    algorithm: "The app relies on a style generator algorithm that loops through configuration options, dynamically maps theme styles, and updates UI properties in real time.",
                    conditionals: "Conditionals check if current theme colors clash with layout elements (such as dark text on dark backgrounds), and dynamically adjust contrast metrics to protect readability."
                }
            }
        };

        // Navigation state controller
        function switchApp(appId) {
            // Update Tab active styling
            for (let i = 1; i <= 3; i++) {
                const btn = document.getElementById(`tab-btn-${i}`);
                const container = document.getElementById(`embed-container-${i}`);
                if (i === appId) {
                    btn.className = "flex-1 min-w-[200px] text-center py-3 px-4 rounded-xl font-semibold text-sm transition-all duration-300 bg-orangeAccent text-black shadow-lg";
                    container.classList.remove('hidden');
                    container.classList.add('block');
                } else {
                    btn.className = "flex-1 min-w-[200px] text-center py-3 px-4 rounded-xl font-semibold text-sm transition-all duration-300 text-gray-400 hover:text-white hover:bg-forest/20";
                    container.classList.remove('block');
                    container.classList.add('hidden');
                }
            }

            // Retrieve selected data
            const app = appsData[appId];

            // Update app header text
            document.getElementById('app-title').textContent = app.title;
            document.getElementById('app-tag').textContent = app.tag;
            document.getElementById('app-desc').textContent = app.desc;

            // Update AP written responses
            document.getElementById('writeup-purpose').textContent = app.writeups.purpose;
            document.getElementById('writeup-function').textContent = app.writeups.function;
            document.getElementById('writeup-io').textContent = app.writeups.io;
            document.getElementById('writeup-list-name').textContent = app.writeups.listName;
            document.getElementById('writeup-list-content').textContent = app.writeups.listContent;
            document.getElementById('writeup-complexity').textContent = app.writeups.complexity;
            document.getElementById('writeup-algorithm').textContent = app.writeups.algorithm;
            document.getElementById('writeup-conditionals').textContent = app.writeups.conditionals;

            // Automatically open the first accordion tab on switch
            openAccordion('acc-1');
        }

        // Accordion functionality for Written Responses
        function toggleAccordion(accId) {
            const acc = document.getElementById(accId);
            const icon = document.getElementById(`acc-icon-${accId}`);
            const isHidden = acc.classList.contains('hidden');
            
            // Close all
            closeAllAccordions();

            if (isHidden) {
                acc.classList.remove('hidden');
                icon.classList.add('rotate-180');
            }
        }

        function openAccordion(accId) {
            closeAllAccordions();
            const acc = document.getElementById(accId);
            const icon = document.getElementById(`acc-icon-${accId}`);
            acc.classList.remove('hidden');
            if (icon) icon.classList.add('rotate-180');
        }

        function closeAllAccordions() {
            const ids = ['acc-1', 'acc-2', 'acc-3'];
            ids.forEach(id => {
                const acc = document.getElementById(id);
                const icon = document.getElementById(`acc-icon-${id}`);
                acc.classList.add('hidden');
                if (icon) icon.classList.remove('rotate-180');
            });
        }

        // Handle Interactive Review Addition (Stored locally in page state)
        function addFeedback(event) {
            event.preventDefault();
            const nameInput = document.getElementById('feedback-name');
            const appSelect = document.getElementById('feedback-app');
            const textInput = document.getElementById('feedback-text');

            const name = nameInput.value;
            const app = appSelect.value;
            const text = textInput.value;

            // Create reviewer container card element
            const wrapper = document.createElement('div');
            wrapper.className = "p-4 rounded-xl bg-deepblack/60 border border-forest/40 animate-fade-in";
            
            // Build card contents
            wrapper.innerHTML = `
                <div class="flex items-center justify-between mb-1">
                    <span class="font-semibold text-xs text-white">${name}</span>
                    <span class="text-[10px] px-2 py-0.5 rounded bg-orangeAccent text-black">${app}</span>
                </div>
                <p class="text-xs text-gray-300">"${text}"</p>
            `;

            // Insert at the top of list
            const list = document.getElementById('feedback-list');
            list.insertBefore(wrapper, list.firstChild);

            // Clean form state
            nameInput.value = '';
            textInput.value = '';

            // Soft feedback confirmation
            const submitBtn = event.target.querySelector('button[type="submit"]');
            const origText = submitBtn.textContent;
            submitBtn.textContent = 'Feedback Added! Thank you ✨';
            submitBtn.className = "w-full py-3 bg-orangeAccent text-black text-sm font-semibold rounded-xl transition-all duration-200";
            setTimeout(() => {
                submitBtn.textContent = origText;
                submitBtn.className = "w-full py-3 bg-forest hover:bg-forest/80 text-lightgreen text-sm font-semibold rounded-xl border border-forest hover:border-lightgreen/30 transition-all duration-200";
            }, 2500);
        }

        // Open first write-up by default when page mounts
        window.addEventListener('DOMContentLoaded', () => {
            openAccordion('acc-1');
        });
    </script>
</body>
</html>
