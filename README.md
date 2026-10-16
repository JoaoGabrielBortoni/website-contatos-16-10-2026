# Projeto: Contatos com Autenticação (React + JWT)

Aplicação React Web com login, registro, logout e rotas privadas, consumindo a API:
https://api-contatos-auth-04-09-25.onrender.com

## Como rodar

```bash
npm install
npm run dev
```

Acesse o endereço exibido no terminal (normalmente http://localhost:5173).

## Estrutura

```
src/
├── App.jsx                 # Rotas públicas e privadas
├── main.jsx                # Ponto de entrada
├── api/api.js              # Axios + interceptor do token JWT
├── context/AuthContext.jsx # Login/logout global
├── components/Navbar.jsx   # Barra de navegação
└── pages/
    ├── Login.jsx
    ├── Registrar.jsx
    └── Contatos.jsx        # Rota protegida
```

## Observação
A API está hospedada no Render e pode levar alguns segundos para "acordar" na primeira requisição.
