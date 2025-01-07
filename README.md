<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EdgeHub Marketing</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8f9fa;
            color: #212529;
            scroll-behavior: smooth;
        }
        .header {
            background-color: #1e293b;
            color: #f1f5f9;
            padding: 1.5rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .header a {
            color: #f1f5f9;
            margin-right: 1rem;
            text-decoration: none;
            font-weight: 500;
        }
        .header a:hover {
            text-decoration: underline;
        }
        .section {
            padding: 4rem 2rem;
        }
        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            text-align: center;
            font-weight: 700;
        }
        .footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #1e293b;
            color: #f1f5f9;
            font-size: 0.875rem;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="header flex justify-between items-center">
        <h1 class="text-2xl font-bold">EdgeHub Marketing</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#about">About</a>
            <a href="#contact">Contact Us</a>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home" class="section bg-gray-100">
        <h2>Welcome to EdgeHub Marketing</h2>
        <p class="text-center text-lg">Where creativity meets precision for all your marketing needs.</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="section">
        <h2>Our Services</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mt-8">
            <div class="p-4 bg-white rounded shadow">
                <h3 class="text-xl font-semibold">Graphic Design</h3>
                <p>Crafting visually stunning logos, banners, and graphics.</p>
            </div>
            <div class="p-4 bg-white rounded shadow">
                <h3 class="text-xl font-semibold">Copywriting</h3>
                <p>Engaging content that drives sales and engagement.</p>
            </div>
            <div class="p-4 bg-white rounded shadow">
                <h3 class="text-xl font-semibold">Content Writing</h3>
                <p>Informative blogs and articles tailored to your audience.</p>
            </div>
            <div class="p-4 bg-white rounded shadow">
                <h3 class="text-xl font-semibold">Website Development</h3>
                <p>Responsive, visually appealing, and functional websites.</p>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="section bg-gray-100">
        <h2>Portfolio</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 mt-8">
            <!-- Project 1 -->
            <div class="bg-white rounded shadow">
                <img src="pinnacle.png" alt="Pinnacle Tech Logo" class="w-full">
                <div class="p-4">
                    <h3 class="text-xl font-semibold">Pinnacle Tech</h3>
                    <p>A corporate logo design for a futuristic tech company.</p>
                </div>
            </div>
            <!-- Project 2 -->
            <div class="bg-white rounded shadow">
                <img src="aurora botanicals.png" alt="Aurora Botanicals Logo" class="w-full">
                <div class="p-4">
                    <h3 class="text-xl font-semibold">Aurora Botanicals</h3>
                    <p>A minimalistic logo design for an organic beauty brand.</p>
                </div>
            </div>
            <!-- Project 3: Resapi -->
            <div class="bg-white rounded shadow">
                <img src="resapi.jpg" alt="Resapi Project" class="w-full">
                <div class="p-4">
                    <h3 class="text-xl font-semibold">Resapi</h3>
                    <p>A branding and identity project for Resapi, a volunteer initiative dedicated to providing psychological first aid and mental health support..</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About Us</h2>
        <p class="text-center text-lg">At EdgeHub Marketing, we are passionate about delivering innovative marketing solutions tailored to your brand's unique needs.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section bg-gray-100">
        <h2>Contact Us</h2>
        <p class="text-center text-lg">Get in touch with us for any inquiries or collaboration opportunities.</p>
        <p class="text-center text-lg font-bold mt-4">Email: <a href="mailto:edgehubmarketing@gmail.com" class="text-blue-500">edgehubmarketing@gmail.com</a></p>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>© 2025 EdgeHub Marketing. All rights reserved.</p>
    </footer>
</body>
</html>
