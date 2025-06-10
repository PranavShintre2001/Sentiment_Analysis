<!-- README.md -->
<h1 align="center">🧠 Web-Based Sentiment Analysis App</h1>

<p align="center">
  A lightweight web application built using <strong>Python</strong>, <strong>Flask</strong>, and <strong>TextBlob</strong> that performs sentiment analysis on user input text. It detects and classifies sentiments into Positive, Negative, or Neutral with a clean and simple web interface.
</p>

<hr/>

<h2>🚀 Features</h2>

<ul>
  <li>📥 Accepts user input through a simple text box</li>
  <li>🧠 Uses TextBlob to detect sentiment based on polarity</li>
  <li>📊 Displays sentiment result: Positive, Negative, or Neutral</li>
  <li>🌐 Clean and responsive web UI using HTML/CSS with Flask templating</li>
</ul>

<hr/>

<h2>🧰 Tech Stack</h2>

<ul>
  <li><strong>Language:</strong> Python</li>
  <li><strong>Framework:</strong> Flask</li>
  <li><strong>Library:</strong> TextBlob</li>
  <li><strong>Frontend:</strong> HTML, CSS (Static Files)</li>
</ul>

<hr/>

<hr/>

<h2>💡 How It Works</h2>

<ol>
  <li>User enters a sentence or paragraph in the input box.</li>
  <li>The backend calculates the <code>polarity</code> using TextBlob.</li>
  <li>Based on the polarity score:
    <ul>
      <li><strong>Positive:</strong> polarity &gt; 0</li>
      <li><strong>Negative:</strong> polarity &lt; 0</li>
      <li><strong>Neutral:</strong> polarity == 0</li>
    </ul>
  </li>
  <li>The result is shown on the same page.</li>
</ol>

<hr/>

<h2>⚙️ Installation & Setup</h2>

<ol>
  <li>Clone the repository</li>

  <pre><code>git clone https://github.com/your-username/Sentiment_Analysis.git
cd Sentiment_Analysis</code></pre>

  <li>Install dependencies (you can use a virtual environment)</li>

  <pre><code>pip install -r requirements.txt</code></pre>

  <li>Run the application</li>

  <pre><code>python Sentiment_Analysis.py</code></
