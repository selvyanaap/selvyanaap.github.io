# selvyanaap.github.io
repository mini project coding camp software engineer revou

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GlobalTech Solutions - Company Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* CSS Variables */
        :root {
            --primary: #2563eb;
            --primary-dark: #1d4ed8;
            --secondary: #64748b;
            --accent: #f59e0b;
            --light: #f8fafc;
            --dark: #1e293b;
            --text: #334155;
            --border: #e2e8f0;
            --shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
            --radius: 8px;
        }

        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', 'Segoe UI', system-ui, sans-serif;
        }

        body {
            line-height: 1.6;
            color: var(--text);
            background-color: #ffffff;
            overflow-x: hidden;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }

        /* ... [PASTE ALL YOUR CSS CODE HERE] ... */
    </style>
</head>
<body>
    <!-- Header & Navigation -->
    <header>
        <div class="container">
            <nav class="navbar">
                <a href="#" class="logo">
                    <i class="fas fa-globe"></i>
                    Global<span>Tech</span>
                </a>
                <ul class="nav-menu" id="nav-menu">
                    <li><a href="#home" class="nav-link active">Home</a></li>
                    <li><a href="#profile" class="nav-link">Our Profile</a></li>
                    <li><a href="#branches" class="nav-link">Our Branches</a></li>
                    <li><a href="#message" class="nav-link">Message Us</a></li>
                </ul>
                <button class="hamburger" id="hamburger">
                    <span class="bar"></span>
                    <span class="bar"></span>
                    <span class="bar"></span>
                </button>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <div class="hero-content">
                <h1 id="welcome-message">Welcome to GlobalTech Solutions</h1>
                <p>We deliver innovative digital solutions that drive business growth and transform industries. Our team of experts is committed to excellence in every project we undertake.</p>
                <div class="hero-buttons">
                    <a href="#profile" class="btn">Learn More</a>
                    <a href="#branches" class="btn btn-outline">Our Branches</a>
                </div>
            </div>
        </div>
    </section>

    <!-- ... [PASTE ALL YOUR HTML SECTIONS HERE] ... -->

    <script>
        // JavaScript for interactive features
        document.addEventListener('DOMContentLoaded', function() {
            // Mobile Navigation Toggle
            const hamburger = document.getElementById('hamburger');
            const navMenu = document.getElementById('nav-menu');
            
            if (hamburger) {
                hamburger.addEventListener('click', function() {
                    hamburger.classList.toggle('active');
                    navMenu.classList.toggle('active');
                });
                
                // ... [PASTE ALL YOUR JAVASCRIPT CODE HERE] ...
            }
        });
    </script>
</body>
</html>
