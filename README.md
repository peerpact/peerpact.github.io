# peerpact.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PeerPact - Build Trust, Settle Agreements</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            color: #f8fafc;
        }
        .hero-bg {
            background-image: linear-gradient(to top right, #1e293b, #0f172a);
        }
    </style>
</head>
<body class="hero-bg min-h-screen flex flex-col items-center justify-center p-4">

    <!-- Header with Name -->
    <header class="w-full max-w-6xl mx-auto py-6 px-4 md:px-8 text-left absolute top-0 left-0">
        <h1 class="text-3xl font-bold text-white tracking-tight ml-4 md:ml-8">PeerPact</h1>
    </header>

    <!-- Main Content & Logo -->
    <main class="flex-grow flex items-center justify-center w-full">
        <div class="container mx-auto max-w-6xl px-4 py-16 md:py-24 text-center flex flex-col items-center">
            <!-- Central Logo -->
            <div class="mb-8">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-32 h-32 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M12 2L2 7l10 5 10-5-10-5z"></path>
                    <path d="M2 17l10 5 10-5"></path>
                    <path d="M2 12l10 5 10-5"></path>
                </svg>
            </div>
            
            <h2 class="text-4xl md:text-6xl font-extrabold tracking-tight leading-tight mb-4 text-white">
                Build Trust. Settle Agreements.
            </h2>
            <p class="text-lg md:text-xl text-slate-300 mb-8 max-w-3xl mx-auto">
                PeerPact provides a simple, secure way for individuals to create and manage informal agreements. Formalize your commitments with ease.
            </p>

            <!-- Download Links -->
            <div class="flex flex-col sm:flex-row gap-4">
                <!-- Apple App Store Button -->
                <a href="#" class="flex items-center justify-center px-8 py-4 bg-gray-900 text-white font-semibold rounded-full shadow-lg transition-transform transform hover:scale-105">
                    <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20">
                        <path d="M13.25 15.25a2.5 2.5 0 100-5 2.5 2.5 0 000 5zm2.5-1.5a.75.75 0 00-1.5 0v.5a.75.75 0 001.5 0v-.5zM12 17.5a.75.75 0 00-1.5 0v.5a.75.75 0 001.5 0v-.5z"></path>
                        <path fill-rule="evenodd" d="M10 2a8 8 0 100 16 8 8 0 000-16zM5 8.75a.75.75 0 011.5 0v2.5a.75.75 0 01-1.5 0v-2.5z" clip-rule="evenodd"></path>
                    </svg>
                    Download on the App Store
                </a>
                
                <!-- Google Play Store Button -->
                <a href="#" class="flex items-center justify-center px-8 py-4 bg-gray-900 text-white font-semibold rounded-full shadow-lg transition-transform transform hover:scale-105">
                    <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20">
                        <path fill-rule="evenodd" d="M13.25 15.25a2.5 2.5 0 100-5 2.5 2.5 0 000 5zm2.5-1.5a.75.75 0 00-1.5 0v.5a.75.75 0 001.5 0v-.5zM12 17.5a.75.75 0 00-1.5 0v.5a.75.75 0 001.5 0v-.5z" clip-rule="evenodd"></path>
                        <path d="M10 2a8 8 0 100 16 8 8 0 000-16zM5 8.75a.75.75 0 011.5 0v2.5a.75.75 0 01-1.5 0v-2.5z"></path>
                    </svg>
                    Get it on Google Play
                </a>
            </div>
        </div>
    </main>

    <!-- Footer -->
    <footer class="w-full max-w-6xl mx-auto text-center text-sm text-slate-500 py-8 mt-12">
        &copy; 2024 PeerPact. All rights reserved.
    </footer>

</body>
</html>
