This is a full stack JavaScript microservice that extracts client information from request headers and returns it as a clean JSON API. It's part of my journey through the freeCodeCamp APIs and Microservices Certification, and a great introduction to working with HTTP headers and Express middleware.

🔗 Link to website: https://nifty-boiled-binder.glitch.me

⚙️ Features
Parses HTTP request headers to return:

ipaddress: Client's IP address

language: Preferred language(s) from the Accept-Language header

software: System and browser info from the User-Agent header

Returns a clean JSON object in response to a GET request at /api/whoami

Handles requests without any client input

🛠 Tech Stack
Node.js

Express.js

Glitch (for live deployment)

JavaScript (ES6)

📦 About
A simple request header parser microservice built with Node.js and Express. Returns a JSON object with IP address, language, and software information extracted from the request headers.
