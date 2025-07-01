# portfolio-site
from flask import Flask, render_template

app = Flask(_name_)

@app.route('/')
def home():
    return render_template('index.html')

if _name_ == '_main_':
    app.run(debug=True)
    <!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="{{ url_for('static', filename='style.css') }}">
</head>
<body>
    <h1>Hi, I'm Nagamani!</h1>
    <p>I am learning Flask and building cool things.</p>

    <h2>Projects</h2>
    <ul>
        <li>✔ Flask API</li>
        <li>✔ Web Scraper</li>
        <li>✔ Portfolio Website</li>
    </ul>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    text-align: center;
    background-color: #f5f5f5;
    color: #333;
}

h1 {
    color: #007bff;
}
