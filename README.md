<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DubaiHealthHacks - Healthcare Innovation Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50">
    <!-- Navbar -->
    <nav class="bg-white shadow-lg">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between items-center py-4">
                <a href="#" class="text-2xl font-bold text-blue-600">DubaiHealthHacks</a>
                <div class="space-x-6">
                    <a href="#initiatives" class="text-gray-700 hover:text-blue-600">Initiatives</a>
                    <a href="#events" class="text-gray-700 hover:text-blue-600">Events</a>
                    <a href="#contact" class="text-gray-700 hover:text-blue-600">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="py-20 text-center">
        <div class="max-w-4xl mx-auto px-4">
            <h1 class="text-5xl font-bold mb-6">Reimagining Dubai's Healthcare</h1>
            <p class="text-xl text-gray-600 mb-8">Empowering innovators in AI, telemedicine & inclusive health tech</p>
            <button class="bg-blue-600 text-white px-8 py-3 rounded-lg hover:bg-blue-700">Join the Movement</button>
        </div>
    </section>

    <!-- Features Grid -->
    <section id="initiatives" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 grid md:grid-cols-3 gap-8">
            <div class="p-6 border rounded-lg">
                <h3 class="text-xl font-bold mb-4">🏆 Health Hackathons</h3>
                <p>Annual competitions for AI-driven solutions</p>
            </div>
            <div class="p-6 border rounded-lg">
                <h3 class="text-xl font-bold mb-4">🤖 Smart Health Tech</h3>
                <p>Showcasing Dubai's telemedicine & wearable innovations</p>
            </div>
            <div class="p-6 border rounded-lg">
                <h3 class="text-xl font-bold mb-4">❤️ Inclusive Care</h3>
                <p>Autism-friendly clinics & accessibility tools</p>
            </div>
        </div>
    </section>

    <script>
        // Add dynamic event countdown
        const hackDate = new Date('2025-03-01').getTime();
        setInterval(() => {
            const now = new Date().getTime();
            document.getElementById('countdown').innerHTML = Math.floor((hackDate - now)/(1000*60*60*24)) + " Days Until Next Hackathon";
        }, 1000);
    </script>
</body>
</html>
