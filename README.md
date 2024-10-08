<h1 style="color: #1f8efa;">🌐 ETH Telegram Mini App NextJS Starter Kit</h1>

<p>Welcome to the <strong>ETH Telegram Mini App Starter Kit</strong>! This kit helps you create mini applications integrated with Ethereum and Telegram using <strong>Next.js</strong>. 🚀</p>

---

<h2 style="color: #ff7f50;">📚 Resources</h2>

<p>Here are some useful resources to help you get started:</p>
<ul>
  <li><a href="https://medium.com/rabble-labs/deploy-your-first-telegram-mini-app-on-ethereum-8b589f4e6411" style="color: #1f8efa;"><strong>Blog</strong></a> on using this Starter Kit 📖</li>
  <li><strong>For Visual Learners</strong> 🎥: <a href="https://www.youtube.com/watch?v=cFLKu4sl76I"><img src="http://i.ytimg.com/vi/cFLKu4sl76I/hqdefault.jpg" alt="YouTube video" /></a></li>
</ul>

---

<h2 style="color: #ff7f50;">⚙️ Prerequisites</h2>

<p>Make sure you have the following installed on your machine:</p>
<ul>
  <li><a href="https://nodejs.org/" style="color: #1f8efa;"><strong>Node.js</strong></a> (v16 or higher)</li>
  <li><a href="https://www.npmjs.com/" style="color: #1f8efa;"><strong>npm</strong></a> or <a href="https://yarnpkg.com/" style="color: #1f8efa;"><strong>Yarn</strong></a></li>
</ul>

---

<h2 style="color: #ff7f50;">🚀 Setup Guide</h2>

<ol>
  <li><strong>Clone the repository</strong>:</li>
  <pre><code>git clone https://github.com/HAPPYS1NGH/rabble-tg-mini-app-nextjs-js</code></pre>
  
  <li><strong>Navigate to the project directory</strong>:</li>
  <pre><code>cd rabble-tg-mini-app-nextjs-js</code></pre>
  
  <li><strong>Set up environment variables</strong>:</li>
  <ul>
    <li>Create a <code>.env.local</code> file and copy the contents of <code>.env.sample</code>.</li>
    <li>Obtain the WalletConnect project ID from <a href="https://cloud.walletconnect.com/" style="color: #1f8efa;"><strong>WalletConnect</strong></a>.</li>
  </ul>
  <pre><code>NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID=your_project_id_here</code></pre>

  <li><strong>Install dependencies</strong>:</li>
  <pre><code>npm install</code> or <code>yarn install</code></pre>

  <li><strong>Start the development server</strong>:</li>
  <pre><code>npm run dev</code> or <code>yarn dev</code></pre>
  
  <li><strong>View the app</strong>: Open your browser and go to <a href="http://localhost:3000" style="color: #1f8efa;">http://localhost:3000</a>.</li>
</ol>

---

<h2 style="color: #ff7f50;">🌍 Exposing Your Local Server</h2>

<p>To test the app on Telegram, you'll need to expose your local server:</p>
<ul>
  <li><strong>Expose server using npm</strong>:<pre><code>npm run expose</code></pre></li>
  <li><strong>Expose server using yarn</strong>:<pre><code>yarn expose</code></pre></li>
</ul>

<p>Alternatively, use services like <strong>ngrok</strong> to expose your endpoint.</p>

---

<h2 style="color: #ff7f50;">🤖 Registering Your Bot on Telegram (Development)</h2>

<ol>
  <li>Open <strong>Telegram</strong> and search for <strong>BotFather</strong>.</li>
  <li>Use the <code>/newbot</code> command to register a bot.</li>
  <li>Use the <code>/setmenubutton</code> command in BotFather (it might not autocomplete).</li>
  <li>Paste the URL from your <strong>LocalTunnel</strong>.</li>
  <li>Set the button name for starting the mini app.</li>
  <li>Go to the bot and test the mini app button.</li>
</ol>

<p><em>Repeat these steps for production with your production URL.</em></p>

---

<h2 style="color: #ff7f50;">🛠️ Registering Your Bot on Telegram (Production)</h2>

<p>Here are the steps for registering your bot in the production environment:</p>

<ol>
  <li>Deploy your app on platforms like <strong>Vercel</strong> or <strong>Netlify</strong>.</li>
  <li>Follow the same steps as in development to register your bot on Telegram using the production URL.</li>
</ol>

---

<h2 style="color: #ff7f50;">🔗 Interacting with Ethereum Contracts</h2>

<p>This starter kit uses <strong>Wagmi v2</strong> hooks for interacting with Ethereum contracts on the <strong>Arbitrum</strong> network. Use these hooks to read and write data to contracts seamlessly.</p>

---

<h2 style="color: #ff7f50;">🗂️ Directory Structure</h2>

<p>The project follows a typical <strong>Next.js</strong> structure. Here's an overview:</p>

<pre><code>.  
├── README.md  
├── components.json  
├── next.config.js  
├── public  
│   └── icons and assets  
├── src  
│   ├── app  
│   ├── assets  
│   ├── components  
│   ├── constants  
│   ├── containers  
│   ├── hooks  
│   ├── lib  
│   ├── providers  
│   └── utils  
└── tailwind.config.js
</code></pre>

---

<h2 style="color: #ff7f50;">❓ FAQs</h2>

<h3 style="color: #1f8efa;">What are Telegram Mini Apps?</h3>
<p>Mini apps are web apps inside Telegram in the form of bots, offering specific UI elements like buttons, popups, and more.</p>

<h3 style="color: #1f8efa;">What do I need to convert my WebApp to a Mini App?</h3>
<p>Your web app should work fine as a mini app, but avoid in-app links to other domains for smooth integration.</p>

---

<h2 style="color: #ff7f50;">🛠️ Support</h2>

<p>If you run into any issues:</p>
<ul>
  <li><a href="https://t.me/+rFqLyk4_W-diZDZl" style="color: #1f8efa;"><strong>Telegram Group</strong></a></li>
  <li><a href="https://twitter.com/happys1ngh" style="color: #1f8efa;"><strong>Twitter: @happys1ngh</strong></a></li>
  <li><a href="https://github.com/HAPPYS1NGH/rabble-tg-mini-app-nextjs-js/issues" style="color: #1f


BUIDL SHOULD NOT STOP!🏗️
#   t g b o t - g e e k - r a j 
 
 
