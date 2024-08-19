const express = require('express');
const app = express();
const port = 3000;

// Rotas da API
app.get('/registros', (req, res) => {
  // Lógica para buscar os registros de ponto do usuário
  res.json(registros);
});

app.post('/registros', (req, res) => {
  // Lógica para criar um novo registro de ponto
  res.status(201).send();
});

app.listen(port, () => {
  console.log(`Servidor rodando na porta ${port}`);
});
