<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">
</head>
<body class="bg-gray-900 text-gray-200">
    <!-- Header Section -->
    <header class="bg-gray-800 sticky top-0 z-50">
        <div class="container mx-auto flex justify-between items-center py-4 px-6">
            <h1 class="text-xl font-bold">Your Name</h1>
            <nav>
                <ul class="flex space-x-4 text-sm">
                    <li><a href="#about" class="text-gray-300 hover:text-white">About</a></li>
                    <li><a href="#projects" class="text-gray-300 hover:text-white">Projects</a></li>
                    <li><a href="#contact" class="text-gray-300 hover:text-white">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="h-screen flex items-center justify-center">
        <div class="text-center">
            <h2 class="text-4xl font-bold mb-4">Welcome to My Portfolio</h2>
            <p class="text-gray-400 max-w-md mx-auto text-base">Showcasing my skills, projects, and achievements. Let's build something great together.</p>
            <a href="#projects" class="mt-6 inline-block bg-blue-500 text-white text-sm px-6 py-3 rounded-md hover:bg-blue-600">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-800">
        <div class="container mx-auto grid md:grid-cols-2 gap-8 items-center">
            <div>
                <h3 class="text-2xl font-bold mb-4">About Me</h3>
                <p class="text-gray-400 text-sm">Write a concise description about yourself, your background, and your specialization. Share what inspires you and your goals.</p>
            </div>
            <div class="flex justify-center">
                <img src="https://via.placeholder.com/300" alt="Your Photo" class="rounded-full border-4 border-gray-700">
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20">
        <div class="container mx-auto">
            <h3 class="text-2xl font-bold text-center mb-8">Projects</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Example Project -->
                <div class="bg-gray-800 rounded-md overflow-hidden">
                    <img src="https://via.placeholder.com/300" alt="Project Thumbnail" class="w-full">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold mb-2">Project Title</h4>
                        <p class="text-gray-400 text-sm">Brief description of the project. Highlight its purpose and features.</p>
                        <a href="#" class="mt-4 inline-block text-blue-400 hover:underline text-sm">View Details</a>
                    </div>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-800">
        <div class="container mx-auto text-center">
            <h3 class="text-2xl font-bold mb-6">Contact Me</h3>
            <p class="text-gray-400 text-sm mb-6">I'd love to hear from you! Feel free to reach out with opportunities or questions.</p>
            <form action="#" method="POST" class="max-w-lg mx-auto space-y-4">
                <input type="text" name="name" placeholder="Your Name" class="w-full bg-gray-700 text-gray-200 text-sm px-4 py-2 rounded-md border border-gray-600 focus:ring-blue-500">
                <input type="email" name="email" placeholder="Your Email" class="w-full bg-gray-700 text-gray-200 text-sm px-4 py-2 rounded-md border border-gray-600 focus:ring-blue-500">
                <textarea name="message" rows="4" placeholder="Your Message" class="w-full bg-gray-700 text-gray-200 text-sm px-4 py-2 rounded-md border border-gray-600 focus:ring-blue-500"></textarea>
                <button type="submit" class="bg-blue-500 text-white text-sm px-6 py-2 rounded-md hover:bg-blue-600">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-500 py-4">
        <div class="container mx-auto text-center text-sm">
            <p>&copy; 2025 Your Name. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
