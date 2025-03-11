<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>We Are Stars</title>                
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background: #333; color: white; padding: 15px; text-align: center; }
        nav { display: flex; justify-content: center; background: #444; padding: 10px; }
        nav a { color: white; text-decoration: none; padding: 10px 20px; }
        .container { padding: 20px; text-align: center; }
        .form-group { margin-bottom: 15px; }
        input, textarea, select { width: 100%; padding: 10px; margin-top: 5px; }
        .btn { background: #28a745; color: white; padding: 10px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>We Are Stars</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact Us</a>
        <a href="#survey">Survey</a>
    </nav>
    
    <section id="home" class="container">
        <h2>Welcome to We Are Stars</h2>
        <p>Connecting talent with industry professionals worldwide.</p>
    </section>
    
    <section id="about" class="container">
        <h2>About Us</h2>
        <p>We Are Stars is a talent management platform ensuring no talent goes unnoticed.</p>
    </section>
    
    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <form>
            <div class="form-group">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
            </div>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>
    
    <section id="survey" class="container">
        <h2>Talent Evaluation Survey</h2>
        <form>
            <div class="form-group">
                <label>What is your talent?</label>
                <input type="text" name="talent" required>
            </div>
            <div class="form-group">
                <label>Preferred Category:</label>
                <select name="category">
                    <option>Acting</option>
                    <option>Influencing</option>
                    <option>Music</option>
                    <option>Other</option>
                </select>
            </div>
            <div class="form-group">
                <label>Do you have professional experience?</label><br>
                <input type="radio" name="experience" value="yes"> Yes
                <input type="radio" name="experience" value="no"> No
            </div>
            <button type="submit" class="btn">Submit Survey</button>
        </form>
    </section>
</body>
</html>
