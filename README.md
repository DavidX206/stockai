<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stock AI Bot</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            line-height: 1.6;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        a {
            color: #0070f3;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Stock AI Bot</h1>
        <p>Welcome to the Stock AI Bot! This application provides real-time stock data and insights using advanced AI technologies. Built with Next.js, the Vercel AI SDK, OpenAI, and Vercel KV, the bot offers users up-to-date information about various stocks, including price trends, market news, as well as predictions.</p>

        <h2>Table of Contents</h2>
        <ul>
            <li><a href="#features">Features</a></li>
            <li><a href="#installation">Installation</a></li>
            <li><a href="#usage">Usage</a></li>
            <li><a href="#configuration">Configuration</a></li>
            <li><a href="#contributing">Contributing</a></li>
            <li><a href="#license">License</a></li>
        </ul>

        <h2 id="features">Features</h2>
        <ul>
            <li>Real-time Stock Data: Access current stock prices and market data.</li>
            <li>AI-Driven Insights: Leverage OpenAI for analyzing and predicting market trends.</li>
            <li>User-Friendly Interface: Built with Next.js for a responsive and modern user experience.</li>
            <li>Persistent Data Storage: Utilize Vercel KV for storing user interactions and preferences.</li>
            <li>Scalable and Fast: Deployed on Vercel, ensuring optimal performance and scalability.</li>
        </ul>

        <h2 id="installation">Installation</h2>

        <h3>Prerequisites</h3>
        <ul>
            <li>Node.js v14 or later</li>
            <li>npm or yarn</li>
        </ul>

        <h3>Steps</h3>
        <ol>
            <li><strong>Clone the repository:</strong>
                <pre><code>git clone https://github.com/yourusername/stock-ai-bot.git
cd stock-ai-bot</code></pre>
            </li>
            <li><strong>Install dependencies:</strong>
                <pre><code>// Using npm:
npm install

// Or using yarn:
yarn install</code></pre>
            </li>
            <li><strong>Environment Variables:</strong>
                <p>Create a <code>.env</code> file in the root directory and configure the following variables:</p>
                <pre><code>OPENAI_API_KEY=your_openai_api_key
VERCEL_KV_URL=your_vercel_kv_url</code></pre>
            </li>
            <li><strong>Run the Development Server:</strong>
                <pre><code>// Using npm:
npm run dev

// Or using yarn:
yarn dev</code></pre>
                <p>Open <a href="http://localhost:3000" target="_blank">http://localhost:3000</a> in your browser to see the application.</p>
            </li>
        </ol>

        <h2 id="usage">Usage</h2>
        <p>1. <strong>Search for Stocks:</strong> Use the search bar to find specific stocks.</p>
        <p>2. <strong>View Stock Details:</strong> Click on a stock to view detailed information, including historical data and AI-generated insights.</p>
        <p>3. <strong>Get Predictions:</strong> Use the bot interface to ask questions about future market trends or specific stocks.</p>

        <h2 id="configuration">Configuration</h2>
        <p>The bot is configured to use OpenAI for natural language processing and Vercel KV for data storage. You can customize the bot's behavior and appearance by modifying the configuration files in the <code>config</code> directory.</p>

        <h2 id="contributing">Contributing</h2>
        <p>We welcome contributions to the Stock AI Bot! To contribute, please fork the repository, create a new branch, and submit a pull request. Be sure to follow our <a href="CONTRIBUTING.md">contribution guidelines</a>.</p>

        <h2 id="license">License</h2>
        <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more details.</p>
    </div>
</body>
</html>
