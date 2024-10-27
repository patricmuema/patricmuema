<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunrise Learning Center</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header, footer { background-color: #FFD700; padding: 1rem; text-align: center; }
        header h1, footer p { margin: 0; color: #333; }
        nav { display: flex; justify-content: center; gap: 1rem; margin: 1rem 0; }
        nav a { text-decoration: none; color: #333; }
        .container { padding: 1rem; max-width: 900px; margin: auto; }
        .cta-button { display: inline-block; padding: 0.5rem 1rem; background-color: #FFD700; color: #333; text-decoration: none; border-radius: 5px; margin-top: 1rem; }
        h2 { color: #444; }
        .contact-form { display: flex; flex-direction: column; gap: 0.5rem; max-width: 400px; margin: auto; }
        .contact-form input, .contact-form textarea { padding: 0.5rem; }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Sunrise Learning Center</h1>
        <p>Where Curiosity Meets Creativity</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">About Us</a>
        <a href="#program">Program & Curriculum</a>
        <a href="#classrooms">Classrooms</a>
        <a href="#resources">Parent Resources</a>
        <a href="#volunteer">Volunteer</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <!-- Home Section -->
    <section class="container" id="home">
        <h2>Welcome to Sunrise Learning Center</h2>
        <p>Sunrise Learning Center is a nurturing space for young learners to explore, create, and discover through our Reggio Emilia-inspired approach. Our goal is to foster each child's unique potential and promote whole-child development in a warm, inclusive environment.</p>
        <a href="#program" class="cta-button">Learn More About Our Approach</a>
    </section>

    <!-- About Us Section -->
    <section class="container" id="about">
        <h2>About Us</h2>
        <p>Founded with a passion for early childhood education, Sunrise Learning Center adopts the Reggio Emilia model, promoting respect, responsibility, and community. Our program encourages hands-on learning and collaborative exploration, creating a vibrant community for children and their families.</p>
    </section>

    <!-- Program & Curriculum Section -->
    <section class="container" id="program">
        <h2>Program & Curriculum</h2>
        <p>Our Reggio Emilia-inspired curriculum centers on child-directed learning and values each child's individuality. Through engaging activities and developmentally appropriate pacing, we nurture cognitive, social, emotional, and physical growth in each child.</p>
        <a href="#classrooms" class="cta-button">Explore Our Classrooms</a>
    </section>

    <!-- Classrooms Section -->
    <section class="container" id="classrooms">
        <h2>Classrooms</h2>
        
        <!-- Infant Room -->
        <h3>Infant Room (Ages 0-1)</h3>
        <p><strong>Activities & Theories:</strong> Sensory play inspired by Piaget's sensorimotor stage.</p>
        <p><strong>Materials:</strong> Soft pillows, sensory toys, low mirrors.</p>
        <p><strong>Parental Involvement:</strong> Reading, singing, and sensory play.</p>

        <!-- 1-2 Year-Old Room -->
        <h3>1-2 Year-Old Room</h3>
        <p><strong>Activities & Theories:</strong> Language and social development through Vygotsky's scaffolding.</p>
        <p><strong>Materials:</strong> Small manipulatives, art supplies, language cards.</p>
        <p><strong>Parental Involvement:</strong> Art projects, reading, simple puzzles.</p>

        <!-- 3-4 Year-Old Room -->
        <h3>3-4 Year-Old Room</h3>
        <p><strong>Activities & Theories:</strong> Creative problem-solving through Montessori and Reggio-inspired projects.</p>
        <p><strong>Materials:</strong> Toy kitchen, art and science manipulatives, blocks.</p>
        <p><strong>Parental Involvement:</strong> Group explorations, storytelling, cooking, sorting, counting.</p>
    </section>

    <!-- Parent Resources Section -->
    <section class="container" id="resources">
        <h2>Parent Resources</h2>
        <p>We value family engagement and offer resources to support learning at home. Join us for Family Art Night, storytelling sessions, and seasonal events to strengthen the community and celebrate your child's learning journey.</p>
        <a href="#contact" class="cta-button">See Upcoming Events</a>
    </section>

    <!-- Volunteer Opportunities Section -->
    <section class="container" id="volunteer">
        <h2>Volunteer Opportunities</h2>
        <p>We invite parents to join storytime, assist with art activities, and help with outdoor play. Community events like Family Art Night provide wonderful opportunities to get involved and enrich our shared experience.</p>
        <a href="#contact" class="cta-button">Sign Up to Volunteer</a>
    </section>

    <!-- Contact Us Section -->
    <section class="container" id="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 123 Learning Lane, Hometown, State, Zip</p>
        <p><strong>Phone:</strong> (123) 456-7890</p>
        <p><strong>Email:</strong> info@sunriselearningcenter.org</p>
        
        <!-- Contact Form -->
        <form class="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone">

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit" class="cta-button">Submit</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Sunrise Learning Center - All Rights Reserved</p>
        <p>Follow Us: Facebook | Instagram | Twitter</p>
    </footer>

</body>
</html>
