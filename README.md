# Aabhay.io[
<!DOCTYPE html>
<html>
<head>
    <title>My Simple Website</title>
    <style>
        /* CSS code for styling */
        body {
            font-family: Arial, sans-serif;
        }
        
        header {
            background-color: #f5f5f5;
            padding: 20px;
        }
        
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        
        nav li {
            display: inline;
            margin-right: 10px;
        }
        
        section {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple Website</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section>
        <h2>About Me</h2>
        <p>Hello! I am a web developer passionate about creating awesome websites.</p>
    </section>
    
    <section>
        <h2>Contact Me</h2>
        <p>You can reach me at email@example.com or through the contact form below:</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <br>
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            <br>
            <input type="submit" value="Submit">
        </form>
    </section>
</body>
</html>
