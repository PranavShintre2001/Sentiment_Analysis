<!-- templates/index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sentiment Analysis App</title>
    <link rel="stylesheet" href="{{ url_for('static', filename='style.css') }}">
</head>
<body>
    <div class="container">
        <h1>🧠 Sentiment Analysis</h1>
        <form method="POST">
            <textarea name="text" placeholder="Enter text here..." required>{{ request.form.text }}</textarea>
            <button type="submit">Analyze</button>
        </form>
        
        {% if result %}
            <div class="result">
                <p><strong>Sentiment:</strong> {{ result }}</p>
                <p><strong>Polarity Score:</strong> {{ polarity }}</p>
            </div>
        {% endif %}
    </div>
</body>
</html>
