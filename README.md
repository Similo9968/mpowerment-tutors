# mpowerment-tutors
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>M-Powerment Tutors</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>M-Powerment Tutors</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <div class="container">
            <h2>Welcome to M-Powerment Tutors</h2>
            <p>Your path to academic success starts here!</p>
            <img src="https://via.placeholder.com/800x400.png?text=Tutoring+session" alt="Tutoring session" class="responsive">
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>M-Powerment Tutors is dedicated to providing high-quality tutoring services to students of all ages. Our experienced tutors are here to help you achieve your academic goals.</p>
            <img src="https://via.placeholder.com/800x400.png?text=About+Us" alt="About us" class="responsive">
        </div>
    </section>

    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <ul>
                <li>One-on-One Tutoring</li>
                <li>Group Tutoring</li>
                <li>Online Tutoring</li>
                <li>Homework Assistance</li>
                <li>Test Preparation</li>
            </ul>
            <img src="https://via.placeholder.com/800x400.png?text=Our+Services" alt="Our services" class="responsive">
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form action="submit_form.php" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 M-Powerment Tutors. All rights reserved.</p>
            <p><a href="https://www.facebook.com" target="_blank">Facebook</a> | <a href="https://www.twitter.com" target="_blank">Twitter</a> | <a href="https://www.instagram.com" target="_blank">Instagram</a></p>
        </div>
    </footer>
</body>
</html>
