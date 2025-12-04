<h1 align="center">🧰 RedTape WhatsApp Customer Support</h1>
<h3 align="center">AI-powered customer service automation using WhatsApp + n8n + Groq + Airtable</h3>

<p>
This project is a fully automated <b>WhatsApp-based customer support system</b>, designed similar to RedTape’s customer service workflow.  
It allows customers to <b>check inventory, place orders, get updates, and create support tickets</b> — all through WhatsApp.
</p>

<p>The automation is powered using <b>n8n workflows</b>, connected with <b>Twilio, Groq AI, Airtable, and custom AI prompts</b> to deliver fast, intelligent customer support.</p>

<hr>
Video Demonstration:-
<h2>🚀 Key Features</h2>
<ul>
  <li>✔ Trigger workflows directly from WhatsApp</li>
  <li>✔ Check live product inventory</li>
  <li>✔ Place orders through conversation</li>
  <li>✔ Fetch order details instantly</li>
  <li>✔ Auto-generate support tickets</li>
  <li>✔ AI-powered, natural language responses</li>
  <li>✔ Modular & scalable n8n workflow architecture</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>

<h3>Messaging & Connectivity</h3>
<ul>
  <li><b>Twilio WhatsApp API</b> – Handles incoming/outgoing messages</li>
</ul>

<h3>AI Engine</h3>
<ul>
  <li><b>OpenAI GPT OSS (120B)</b> running on <b>Groq API</b></li>
  <li>Ultra-fast inference + high natural language accuracy</li>
</ul>

<h3>Automation</h3>
<ul>
  <li><b>n8n</b> – Workflow automation engine</li>
  <li>Routes WhatsApp → AI → Airtable → WhatsApp</li>
</ul>

<h3>Database</h3>
<ul>
  <li><b>Airtable</b> – Stores inventory, orders, support tickets</li>
</ul>

<hr>

<h2>🧩 System Architecture (4-Phase Build)</h2>
<img width="1919" height="910" alt="Screenshot 2025-11-24 192644" src="https://github.com/user-attachments/assets/40d86465-a3e2-4701-a514-516bbab48791" />

<h3>1️⃣ Phase 1 – WhatsApp Setup (Twilio)</h3>
<ul>
  <li>Connected Twilio Sandbox with WhatsApp</li>
  <li>Configured webhook to n8n</li>
  <li>Two-way communication established</li>
</ul>

<h3>2️⃣ Phase 2 – AI Agent Setup (Groq + GPT OSS)</h3>
<ul>
  <li>Integrated Groq API with GPT OSS 120B</li>
  <li>Created custom AI personality</li>
  <li>Added intent handling (orders, inventory, tickets)</li>
</ul>

<h3>3️⃣ Phase 3 – Airtable Backend Setup</h3>
<ul>
  <li>Created 3 main tables:</li>
  <ul>
    <li><b>Inventory Table</b> – Shoes, sizes, stock</li>
    <li><b>Orders Table</b> – Order IDs, status, user details</li>
    <li><b>Support Tickets Table</b> – Ticket IDs, issue logs</li>
  </ul>
</ul>

<h3>4️⃣ Phase 4 – System Prompts & Business Logic</h3>
<ul>
  <li>Added custom role prompts + return policy</li>
  <li>Mapped all customer intents</li>
  <li>Created safe and structured AI response templates</li>
</ul>

<hr>

<h2>📲 How the System Works (End-to-End)</h2>
<ol>
  <li>User sends message on WhatsApp</li>
  <li>Twilio → forwards to n8n</li>
  <li>n8n → sends to Groq AI for analysis</li>
  <li>AI detects customer intent</li>
  <li>If needed → n8n queries Airtable</li>
  <li>AI generates friendly response</li>
  <li>n8n sends reply back to WhatsApp</li>
</ol>
<img width="1599" height="777" alt="Screenshot 2025-11-24 192633" src="https://github.com/user-attachments/assets/c843360b-e048-42e9-a1df-5a6777d6bf94" />

<hr>

<h2>📦 Features in Action</h2>

<h3>🧾 1. Live Inventory Check</h3>
<p>User: <i>“Do you have size 9 running shoes?”</i><br>
System → checks Airtable → returns availability, price, sizes.</p>
<img width="1851" height="915" alt="Screenshot 2025-11-24 192657" src="https://github.com/user-attachments/assets/4eafa300-a530-4718-9c02-c7bd8702f41f" />
<img width="387" height="846" alt="Screenshot 2025-12-04 203520" src="https://github.com/user-attachments/assets/46f3c080-89f5-43f5-93e5-070dc4634522" />

<h3>📦 2. Order Tracking</h3>
<p>User: <i>“Track my order RT1023.”</i><br>
System → fetches status → replies instantly.</p>
<img width="387" height="846" alt="Screenshot 2025-12-04 203520" src="https://github.com/user-attachments/assets/681ef2e3-3e79-4b4c-8360-39860e8bab3d" />
<img width="1853" height="911" alt="Screenshot 2025-11-24 192707" src="https://github.com/user-attachments/assets/d8828472-014b-4add-98da-890876d016c6" />

<h3>🎫 3. Support Ticket Creation</h3>
<p>User: <i>“My shoes are damaged.”</i><br>
System → creates ticket → returns Ticket ID.</p>
<img width="392" height="847" alt="Screenshot 2025-12-04 203619" src="https://github.com/user-attachments/assets/73953d24-8331-43bb-bad2-0268263b40e3" />


<img width="1849" height="918" alt="Screenshot 2025-11-24 192717" src="https://github.com/user-attachments/assets/a87dd480-2a59-4b0d-8783-12f58d22db20" />

<hr>

<h2>🧱 Modular Design Benefits</h2>
<ul>
  <li>Easy to scale new features</li>
  <li>Clear and separated workflows</li>
  <li>Maintainable AI prompts</li>
  <li>Flexible database structure</li>
</ul>

<hr>

<h2>🚀 Future Enhancements</h2>
<ul>
  <li>🌐 Multi-language support (Hindi, Hinglish)</li>
  <li>🧠 Product recommendations using embeddings</li>
  <li>🔗 Auto-sync inventory from eCommerce API</li>
  <li>💳 WhatsApp payment integration</li>
  <li>🤝 Personalized customer profiles</li>
</ul>

<hr>

<h2>📌 Project Name</h2>
<h3><b>👉 RedTape WhatsApp Customer Support</b></h3>

<br>

<h2 align="center">🎉 Making Customer Support Faster, Smarter, and Fully Automated!</h2>
