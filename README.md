<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tunisco | Project Documentation</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body { background-color: #f8fafc; }
        .tunisia-gradient { background: linear-gradient(135deg, #e11d48 0%, #fb7185 100%); }
    </style>
</head>
<body class="text-gray-800 font-sans">

    <header class="tunisia-gradient text-white py-16 px-4 shadow-lg">
        <div class="max-auto max-w-4xl text-center">
            <h1 class="text-5xl font-extrabold mb-4">🇹🇳 Tunisco</h1>
            <p class="text-xl opacity-90">The Ultimate Digital Gateway to Tunisia's Cities, Hotels, and Culture.</p>
            <div class="mt-8 flex justify-center gap-4">
                <a href="#setup" class="bg-white text-rose-600 px-6 py-2 rounded-full font-bold hover:bg-gray-100 transition">Get Started</a>
                <a href="https://github.com/your-username/tunisco" class="border border-white px-6 py-2 rounded-full font-bold hover:bg-white hover:text-rose-600 transition">View on GitHub</a>
            </div>
        </div>
    </header>

    <main class="max-w-4xl mx-auto py-12 px-6">
        
        <section class="mb-12">
            <h2 class="text-3xl font-bold border-b-2 border-rose-500 pb-2 mb-6">📖 About the Project</h2>
            <p class="text-lg leading-relaxed text-gray-600">
                Tunisco is a full-stack platform built to solve the fragmentation of Tunisian travel data. 
                It empowers tourists to explore 24+ governorates, discover top-rated local businesses, 
                and book reservations through a custom-built PHP backend.
            </p>
        </section>

        <section class="mb-12">
            <h2 class="text-3xl font-bold border-b-2 border-rose-500 pb-2 mb-8">✨ Key Features</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-rose-500">
                    <i class="fa-solid fa-city text-rose-500 text-2xl mb-4"></i>
                    <h3 class="font-bold text-xl mb-2">City Exploration</h3>
                    <p class="text-gray-500 text-sm">Rich profiles for Tunis, Sousse, Djerba, and more with historical insights.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-rose-500">
                    <i class="fa-solid fa-calendar-check text-rose-500 text-2xl mb-4"></i>
                    <h3 class="font-bold text-xl mb-2">PHP Reservation Engine</h3>
                    <p class="text-gray-500 text-sm">Dynamic table and room booking logic with real-time MySQL validation.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-rose-500">
                    <i class="fa-solid fa-utensils text-rose-500 text-2xl mb-4"></i>
                    <h3 class="font-bold text-xl mb-2">Curated Directory</h3>
                    <p class="text-gray-500 text-sm">Filtered lists of premium hotels and authentic Tunisian restaurants.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-sm border-l-4 border-rose-500">
                    <i class="fa-solid fa-mobile-screen-button text-rose-500 text-2xl mb-4"></i>
                    <h3 class="font-bold text-xl mb-2">Responsive UI</h3>
                    <p class="text-gray-500 text-sm">Modern CSS3 Grid/Flexbox design optimized for travelers on mobile devices.</p>
                </div>
            </div>
        </section>

        
        <section class="mb-12 bg-white rounded-xl shadow-sm p-8">
            <h2 class="text-3xl font-bold mb-6">🛠️ Technical Stack</h2>
            <table class="w-full text-left border-collapse">
                <thead>
                    <tr class="border-b text-rose-600">
                        <th class="py-3 px-2">Layer</th>
                        <th class="py-3 px-2">Technology</th>
                    </tr>
                </thead>
                <tbody class="text-gray-600">
                    <tr class="border-b">
                        <td class="py-3 px-2 font-semibold">Frontend</td>
                        <td class="py-3 px-2 text-sm">HTML5, CSS3, JavaScript (ES6+)</td>
                    </tr>
                    <tr class="border-b">
                        <td class="py-3 px-2 font-semibold">Backend</td>
                        <td class="py-3 px-2 text-sm">PHP 8.x (Procedural & OOP)</td>
                    </tr>
                    <tr class="border-b">
                        <td class="py-3 px-2 font-semibold">Database</td>
                        <td class="py-3 px-2 text-sm">MySQL (Relational Schema)</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section id="setup" class="mb-12">
            <h2 class="text-3xl font-bold border-b-2 border-rose-500 pb-2 mb-6">🚀 Local Installation</h2>
            <div class="bg-gray-900 text-gray-300 p-6 rounded-lg font-mono text-sm leading-relaxed">
                <p class="text-rose-400 mb-2"># Clone the repo</p>
                <p class="mb-4 text-white">git clone https://github.com/user/tunisco.git</p>
                
                <p class="text-rose-400 mb-2"># Import Database</p>
                <p class="mb-4 text-white">Import /db/tunisco_db.sql in PHPMyAdmin</p>

                <p class="text-rose-400 mb-2"># Run Server</p>
                <p class="text-white">Move to htdocs & open http://localhost/tunisco</p>
            </div>
        </section>

    </main>

    <footer class="bg-gray-800 text-gray-400 py-8 text-center border-t border-gray-700">
        <p>Developed with ❤️ for Tunisian Tourism</p>
        <p class="text-xs mt-2 uppercase tracking-widest">&copy; 2026 Tunisco Project</p>
    </footer>

</body>
</html>
