🧮 Express Arithmetic API using Route Parameters

This is a simple Node.js project using Express.js that acts as an HTTP server for basic arithmetic operations. Instead of using query parameters, it uses **route parameters** (`/sum/:a/:b`) for cleaner and RESTful endpoints.

1. Clone the Repository

```bash
git clone https://github.com/Yuvrajjjjjjj/Basic-HTTP--Server-.git
cd Basic-HTTP--Server-
```

2. Install Dependencies

```bash
npm install
```

3. Start the Server

```bash
node index.js
```

Server runs at: [http://localhost:3000](http://localhost:3000)


## 📌 Available API Endpoints

Each route expects two numbers passed directly in the URL path.

➕ Addition

```http
GET /sum/:a/:b
```
Example:
`GET http://localhost:3000/sum/4/5`  
Response:  
```json
{ "ans": 9 }
```


➖ Subtraction

```http
GET /subtract/:a/:b
```
Example:
`GET http://localhost:3000/subtract/9/3`  
Response:
```json
{ "ans": 6 }
```


✖️ Multiplication

```http
GET /multiply/:a/:b
```
Example:
`GET http://localhost:3000/multiply/2/6`  
Response:  
```json
{ "ans": 12 }
```


➗ Division

```http
GET /divide/:a/:b
```
Example: 
`GET http://localhost:3000/divide/10/2`  
Response:
```json
{ "ans": 5 }
```

🛠 Technologies Used

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)

This project is open-source and available under the [MIT License](LICENSE).
