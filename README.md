# Basic-HTTP--Server-
# Basic HTTP Server using Node.js and Express

This is a simple HTTP server built using Express.js with four arithmetic endpoints. You can perform basic operations by sending GET requests with query parameters.

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/basic-http-server.git
cd basic-http-server

2. Install dependencies:
npm install

3. Start the server:
node index.js
The server will run on http://localhost:3000

📌 Available Routes
All endpoints expect two query parameters: a and b.

➕ Addition
http://localhost:3000/sum?a=1&b=2
Response: { "ans": 3 }

✖️ Multiplication
http://localhost:3000/multiply?a=2&b=3
Response: { "ans": 6 }

➗ Division
http://localhost:3000/divide?a=10&b=2
Response: { "ans": 5 }

➖ Subtraction
http://localhost:3000/subtract?a=5&b=3
Response: { "ans": 2 }
