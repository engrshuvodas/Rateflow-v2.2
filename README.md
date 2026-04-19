<h1>🚀 RateFlow v2.2 — Live Currency Calculator</h1>

<p>
A sleek, modern, and fully interactive <strong>currency calculator web app</strong> that allows users to:
</p>

<ul>
<li>💱 Convert currencies in real-time</li>
<li>🔍 Calculate custom exchange rates</li>
<li>📊 Compare rates instantly</li>
</ul>

<p><strong>Built with:</strong> HTML, CSS, Vanilla JavaScript</p>

<hr>

<h2>✨ Features</h2>

<h3>💱 Currency Converter</h3>
<ul>
<li>Convert between USD ($), BDT (৳), INR (₹)</li>
<li>Manual exchange rate input</li>
<li>Live calculation as you type</li>
<li>Shows:
  <ul>
    <li>Converted value</li>
    <li>Reverse rate</li>
    <li>USD base value</li>
    <li>All currency equivalents</li>
  </ul>
</li>
</ul>

<h3>🔍 Rate Finder</h3>
<ul>
<li>Find exchange rates using two known values</li>
<li>Supports:
  <ul>
    <li>BDT → USD</li>
    <li>INR → USD</li>
    <li>BDT → INR</li>
  </ul>
</li>
<li>Shows per-unit rate and reverse rate</li>
<li>Displays equation preview</li>
</ul>

<h3>📊 Rate Comparison</h3>
<ul>
<li>Compare all calculated rates</li>
<li>Highlights the <strong>best rate</strong></li>
<li>Shows implied cross rates</li>
</ul>

<h3>🔄 Cross Rate Calculator</h3>
<ul>
<li>USD ↔ BDT</li>
<li>USD ↔ INR</li>
<li>BDT ↔ INR</li>
<li>Includes reverse rate display</li>
</ul>

<h3>📅 Date Tracking</h3>
<ul>
<li>Select custom date</li>
<li>Formatted display</li>
<li>Keeps conversion context clear</li>
</ul>

<h3>⚡ Real-Time Updates</h3>
<ul>
<li>No buttons required</li>
<li>Instant updates on input</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
rateflow/
│── rateflow-v2.2.html
</pre>

<p>This is a single-file application.</p>

<hr>

<h2>🚀 How to Use</h2>

<h3>1. Clone Repository</h3>
<pre>git clone https://github.com/yourusername/rateflow.git</pre>

<h3>2. Open File</h3>
<pre>rateflow-v2.2.html</pre>

<p>No installation required.</p>

<hr>

<h2>🧠 How It Works</h2>

<h3>Base Logic</h3>
<ul>
<li>USD is used as the base currency</li>
<li>User inputs:
  <ul>
    <li>1 USD = X BDT</li>
    <li>1 USD = Y INR</li>
  </ul>
</li>
</ul>

<h3>Conversion Formula</h3>
<pre>
USD value = amount / rate(from)
Result = USD value × rate(to)
</pre>

<h3>Rate Finder Formula</h3>
<pre>
Rate = Local Currency ÷ USD
Reverse = 1 / Rate
</pre>

<hr>

<h2>🎯 Use Cases</h2>
<ul>
<li>Freelancers calculating payments</li>
<li>Currency comparison</li>
<li>Manual exchange verification</li>
<li>Educational purposes</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
<li>HTML5</li>
<li>CSS3</li>
<li>Vanilla JavaScript</li>
</ul>

<hr>

<h2>🔮 Future Improvements</h2>
<ul>
<li>Live API integration</li>
<li>Save rate history</li>
<li>Add more currencies</li>
<li>Charts and analytics</li>
</ul>

<hr>

<h2>🤝 Contributing</h2>
<pre>
1. Fork the repo
2. Create your branch
3. Commit changes
4. Open pull request
</pre>

<hr>

<h2>📄 License</h2>
<p>MIT License</p>

<hr>

<h2>💡 Author</h2>
<p>
<strong>Shuvo</strong><br>
WhatsApp Marketing & Software Solutions
</p>
