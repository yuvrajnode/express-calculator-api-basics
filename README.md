# Express Calculator API

A tiny Express.js server that does arithmetic through route parameters, e.g. `GET /sum/4/5`. Built as a first exercise in routing and HTTP servers with Node.js.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

## Getting started

```bash
git clone https://github.com/yuvrajnode/express-calculator-api-basics.git
cd express-calculator-api-basics
npm install
node index.js
```

The server runs at `http://localhost:3000`.

## Endpoints

| Method | Route | Example | Response |
|---|---|---|---|
| GET | `/sum/:a/:b` | `/sum/4/5` | `{ "ans": 9 }` |
| GET | `/subtract/:a/:b` | `/subtract/9/3` | `{ "ans": 6 }` |
| GET | `/multiply/:a/:b` | `/multiply/2/6` | `{ "ans": 12 }` |
| GET | `/divide/:a/:b` | `/divide/10/2` | `{ "ans": 5 }` |

```bash
curl http://localhost:3000/multiply/7/6
# {"ans":42}
```

## License

[MIT](LICENSE) © Yuvraj Singh
