# Businesses-ideas-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Custom Software Development Services</title>
    <link rel="stylesheet" href="{{ url_for('static', filename='style.css') }}">
</head>
<body>
    <header>
        <h1>Custom Software Development Services</h1>
        <nav>
            <a href="{{ url_for('home') }}">Home</a>
            <a href="{{ url_for('contact') }}">Contact</a>
        </nav>
    </header>
    <main>
        {% block content %}{% endblock %}
    </main>
    <footer>
        <p>&copy; 2025 Custom Software Development Services</p>
    </footer>
</body>
</html>
{% extends "base.html" %}

{% block content %}
<h2>Welcome to Custom Software Development Services</h2>
<p>We offer tailored software solutions to meet your business needs.</p>
{% endblock %}{% extends "base.html" %}

{% block content %}
<h2>Contact Us</h2>
<form method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="Williams Jones" required>
    <label for="orvillepeck79@gmail.com">Email:</label>
    <input type="email" id="email" name="email" required>
    <label for="message">Message:</label>
    <textarea id="message" name="message" required></textarea>
    <button type="submit">Send</button>
</form>
{% endblock %}body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

nav a {
    color: #fff;
    margin: 0 1em;
    text-decoration: none;
}

main {
    padding: 2em;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    margin-bottom: 0.5em;
}

input, textarea {
    margin-bottom: 1em;
    padding: 0.5em;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    padding: 0.5em;
    border: none;
    border-radius: 4px;
    background-color: #333;
    color: #fff;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}python app.py
