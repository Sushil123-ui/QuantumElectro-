<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mock Test Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">MockTest</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#tests">Tests</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#login">Login</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <h1>Welcome to MockTest</h1>
        <p>Your ultimate destination for mock tests and preparation.</p>
        <div class="quick-links">
            <a href="#latest-tests">Latest Tests</a>
            <a href="#popular-tests">Popular Tests</a>
        </div>
    </section>

    <!-- Tests Section -->
    <section id="tests">
        <h2>Tests</h2>
        <div class="categories">
            <div class="category">
                <h3>Competitive Exams</h3>
                <ul>
                    <li><a href="#test1">Test 1</a></li>
                    <li><a href="#test2">Test 2</a></li>
                </ul>
            </div>
            <div class="category">
                <h3>Academic Exams</h3>
                <ul>
                    <li><a href="#test3">Test 3</a></li>
                    <li><a href="#test4">Test 4</a></li>
                </ul>
            </div>
            <div class="category">
                <h3>Mock Interviews</h3>
                <ul>
                    <li><a href="#test5">Test 5</a></li>
                    <li><a href="#test6">Test 6</a></li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Test Page Section -->
    <section id="test-page">
        <h2>Test Name</h2>
        <div class="test-header">
            <span>Time Left: 30:00</span>
            <span>Total Questions: 50</span>
        </div>
        <div class="question-section">
            <p>Question 1: What is the capital of France?</p>
            <ul>
                <li><input type="radio" name="q1" value="a"> Paris</li>
                <li><input type="radio" name="q1" value="b"> London</li>
                <li><input type="radio" name="q1" value="c"> Rome</li>
                <li><input type="radio" name="q1" value="d"> Berlin</li>
            </ul>
            <button>Previous</button>
            <button>Next</button>
        </div>
        <button class="submit-button">Submit</button>
    </section>

    <!-- Results Page Section -->
    <section id="results">
        <h2>Your Results</h2>
        <div class="result-summary">
            <p>Score: 45/50</p>
            <p>Correct Answers: 45</p>
            <p>Incorrect Answers: 5</p>
        </div>
        <button class="retake-button">Retake Test</button>
        <div class="detailed-results">
            <h3>Detailed Results</h3>
            <ul>
                <li>Question 1: Correct</li>
                <li>Question 2: Incorrect</li>
                <!-- Add more questions -->
            </ul>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>Information about the company, mission, vision, team members, and history.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">Submit</button>
        </form>
        <div class="contact-details">
            <p>Email: info@mocktest.com</p>
            <p>Phone: +123456789</p>
            <p>Address: 123 MockTest Street</p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 MockTest. All rights reserved.</p>
        <div class="social-media">
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
            <a href="#">LinkedIn</a>
        </div>
    </footer>
</body>
</html>
