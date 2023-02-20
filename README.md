<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
  </head>
  <body>
    <h1>Product Scraper</h1>
    <p>This is a command-line tool that scrapes product data from a website and saves it to a CSV or JSON file.</p>
    <h2>Usage</h2>
    <pre><code>go run main.go -website &lt;url&gt; [-format &lt;csv/json&gt;]</code></pre>
    <p>The following flags are available:</p>
    <ul>
      <li><code>-website</code>: URL of the website to scrape (required)</li>
      <li><code>-format</code>: Output file format (default: <code>csv</code>)</li>
    </ul>
    <h2>Example</h2>
    <p>Scrape product data from <code>https://www.example.com/products</code> and save it to a CSV file:</p>
    <pre><code>go run main.go -website https://www.example.com/products</code></pre>
    <p>Scrape product data from <code>https://www.example.com/products</code> and save it to a JSON file:</p>
    <pre><code>go run main.go -website https://www.example.com/products -format json</code></pre>
    <h2>Implementation</h2>
    <p>The scraper is implemented in Go and uses the <a href="https://github.com/gocolly/colly">Colly</a> library for web scraping.</p>
    <p>The <code>main</code> function:</p>
    <p>For more information on the implementation, please refer to the code comments.</p>
  </body>
</html>
