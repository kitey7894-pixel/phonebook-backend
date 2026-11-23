# Phonebook backend — Full Stack Open part 3

Backend do phonebook (exercícios 3.1–3.22).

**App online:** https://phonebook-backend-w8rv.onrender.com

- API: https://phonebook-backend-w8rv.onrender.com/api/persons
- Info: https://phonebook-backend-w8rv.onrender.com/info

Obs.: instância free do Render hiberna com inatividade — a primeira requisição pode demorar ~50s.

## Rodando local

```bash
npm install
# crie um arquivo .env com:
# MONGODB_URI=<sua connection string do MongoDB Atlas>
# PORT=3001
npm run dev
```

## Scripts

- `npm start` — produção
- `npm run dev` — desenvolvimento com reload (`node --watch`)
- `npm run lint` — ESLint
- `node mongo.js <senha>` — lista a agenda direto do Atlas
- `node mongo.js <senha> <nome> <numero>` — adiciona entrada
