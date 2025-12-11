<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <link href="https://fonts.googleapis.com/css2?family=Telegraf&display=swap" rel="stylesheet"> <!-- Font Link -->
    <style>
        body {
            font-family: 'Telegraf', sans-serif; /* Use Telegraf font */
            margin: 0;
            padding: 0;
            background-color: #E6D6BF; /* Light background */
            color: #37858E; /* Default font color */
            font-size: 20px; /* Increased font size for body */
        }

        header {
            background: #37858E; /* Header background color */
            color: white; /* Change header text color to white */
            padding: 20px 0; /* Increased padding */
            text-align: center; /* Centered text */
            font-size: 35px; /* Increased font size for header */
        }

        header img {
            max-width: 400px; /* Increased logo width to 400px */
            height: auto; /* Maintain aspect ratio */
            margin-bottom: 10px; /* Space between logo and title */
        }

        h1 {
            color: #F9740D; /* Change header title color */
            font-size: 50px; /* Increased font size for h1 */
        }

        nav {
            margin: 10px 0;
            font-size: 22px; /* Increased font size for navigation */
        }

        nav a {
            color: white; /* Link color */
            margin: 0 15px;
            text-decoration: none;
        }

        section {
            padding: 20px;
            background-image: url('https://i.ibb.co/fVQHbg7D/Screenshot-2025-12-09-025435.png'); /* Background image for each section */
            background-size: cover; /* Cover the entire section */
            background-position: center; /* Center the image */
            background-repeat: no-repeat; /* Prevent repeating */
            margin: 10px;
            border-radius: 5px;
            color: white; /* Default text color */
            font-size: 20px; /* Increased font size for section text */
            text-align: justify; /* Justify text in sections */
        }

        section h2 { 
            color: #F9740D; /* Updated section title color */
            font-size: 30px; /* Increased font size for section titles */
            text-align: left; /* Align section titles to the left */
        }

        section p {
            color: #37858E; /* Paragraph color */
            font-size: 20px; /* Increased font size for paragraphs */
        }

        .freshood-solution p, .freshood-solution li {
            color: #37858E; /* Updated to specific color for the Freshood Solution section */
            font-size: 20px; /* Increased font size for list items */
        }

        .download-app {
            color: #F9740D; /* Download Our App text color */
            font-size: 24px; /* Increased font size for download app */
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background: #37858E; /* Footer background color */
            color: white; /* Keep footer text white */
            position: relative;
            bottom: 0;
            width: 100%;
            font-size: 18px; /* Increased font size for footer */
        }

        .socials {
            display: flex;
            justify-content: center;
            gap: 20px;
            font-size: 20px; /* Increased font size for social links */
        }

        .socials a {
            color: #37858E; /* Color for social media links */
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://i.ibb.co/S4DCCs5F/Freshood-Logo-Primary.png" alt="Freshood Logo"> <!-- Updated logo image -->
        <h1>Welcome to Freshood</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#solution">The Freshood Solution</a>
            <a href="#signup">How to Sign Up</a>
            <a href="#contact">Contact</a>
            <a href="#socials">Socials</a>
        </nav>
    </header>

    <section id="home">
        <h2>Home</h2>
        <p>Join us on this transformative journey to revolutionize agriculture, empower farmers, and tackle global food security challenges. Let’s cultivate a brighter, sustainable future for all.</p>
    </section>

    <section id="about">
        <h2>About</h2>
        <p><strong>Mission:</strong> At Freshood, our mission is to revolutionize the agricultural landscape by leveraging innovative technology to empower farmers and enhance supply chain efficiency. We strive to create a transparent and sustainable agricultural ecosystem that connects farmers directly with buyers, reduces post-harvest losses, and promotes food security while fostering economic growth in local communities.</p>
        <p><strong>Vision:</strong> Our vision is to be the leading force in transforming agriculture into a tech-driven, sustainable industry. We envision a future where every farmer has access to advanced tools and data-driven insights, enabling them to thrive in a competitive market. By disrupting traditional agricultural practices, we aim to cultivate a resilient and responsive food system that benefits farmers, consumers, and the planet alike.</p>
    </section>

    <section id="solution" class="freshood-solution">
        <h2>The Freshood Solution</h2>
        <p>The Freshood platform offers a revolutionary approach to agricultural trade by empowering farmers and ensuring greater access to resources and markets. Our innovative solution bridges the gap between farmers and businesses, promoting efficiency and sustainability.</p>
        <p>Key components of the Freshood Solution include:</p>
        <ul>
            <li>Direct relationships between farmers and buyers to ensure the freshest produce.</li>
            <li>Reliable payment methods for seamless transactions.</li>
            <li>Real-time analytics to aid decision-making in the marketplace.</li>
            <li>Encouragement of eco-friendly farming practices.</li>
            <li>A robust community for sharing knowledge and resources.</li>
        </ul>
    </section>

    <section id="signup">
        <h2>How to Sign Up</h2>
        <p>To get started, please refer to the following user guides:</p>
        <ul>
            <li><a href="https://youtu.be/MqMcb8p-JDc" target="_blank">Buyer Sign Up User Guide</a></li>
            <li><a href="https://youtu.be/pgV272SbK5Y" target="_blank">Seller Sign Up User Guide</a></li>
        </ul>
    </section>

    <section id="socials">
        <h2>Follow Us</h2>
        <p>Connect with us on social media:</p>
        <div class="socials">
            <a href="https://www.facebook.com" target="_blank">Facebook</a>
            <a href="https://www.instagram.com" target="_blank">Instagram</a>
            <a href="https://freshood.co/" target="_blank">Seller Sign Up</a>
        </div>
        <h3 class="download-app">Download Our App</h3>
        <div class="socials">
            <a href="https://apps.apple.com/hk/app/freshood/id6741566570" target="_blank">Download on the App Store</a>
            <a href="https://play.google.com/store/apps/details?id=com.freshood.mobileapp" target="_blank">Get it on Google Play</a>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Contact us at <a href="mailto:freemanglobal2023@gmail.com">freemanglobal2023@gmail.com</a>.</p>
    </section>

    <footer>
        <p>&copy; 2025 Freshood</p>
        <p>Philippines SEC registered under FREEMAN GLOBAL PHILIPPINES, INC. (SEC NUMBER 2025080216233-00).</p>
        <p>Address: Level 10-01, Fort Legend Tower, 3rd Avenue and 31st Street, Fort Bonifacio, Taguig City, Fourth District, National Capital Region (NCR), 1630, Metro Manila, Philippines.</p>
    </footer>
</body>
</html>
