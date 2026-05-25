# 🚀 API REST com Express e Deploy no Render

## 👨‍🎓 Trabalho Acadêmico
Aluno: Gabriel R. Massoni  
Curso: ADS – Sistemas Operacionais

---

# 📌 Introdução

Uma API REST permite a comunicação entre sistemas por meio de requisições HTTP. Ela é muito utilizada em aplicações web, sistemas mobile e serviços em nuvem.

Neste trabalho, será apresentada a criação de uma API REST utilizando Node.js, Express.js e deploy na plataforma Render.

---

# 🧠 O que é uma API REST?

API REST é uma interface que permite a troca de dados entre sistemas.

Ela utiliza métodos HTTP como:

- GET;
- POST;
- PUT;
- DELETE.

Esses métodos permitem consultar, cadastrar, atualizar e excluir informações.

---

# ⚙️ Criando uma API REST com Express

## Passo 1: Inicializar o projeto

Crie uma nova pasta para o projeto e abra no VS Code.

```bash
npm init -y
```

---

## Passo 2: Instalar o Express

```bash
npm install express
```

---

## Passo 3: Instalar o CORS

```bash
npm install cors
```

O CORS é um mecanismo de segurança que controla o acesso entre domínios diferentes no navegador.

---

## Passo 4: Criar o arquivo principal

Crie um arquivo chamado:

```text
index.js
```

Exemplo básico:

```javascript
const express = require("express");
const cors = require("cors");

const app = express();
app.use(cors());
app.use(express.json());

app.get("/", (req, res) => {
  res.send("API REST funcionando!");
});

app.listen(3000, () => {
  console.log("Servidor rodando na porta 3000");
});
```

---

## Passo 5: Executar o servidor

```bash
node index.js
```

---

# 🌐 Render para Simular Web Services

O Render é uma plataforma de hospedagem em nuvem que permite publicar aplicações web, APIs e serviços backend.

Ele suporta tecnologias como:

- Node.js;
- Python;
- Docker;
- Bancos de dados;
- Repositórios Git.

---

# ✅ Benefícios do Render

- Deploy rápido;
- Integração com GitHub;
- Atualizações automáticas;
- Certificado SSL gratuito;
- Interface simples;
- Escalabilidade;
- Ideal para APIs e microsserviços.

---

# 🔄 Deploy Contínuo

Com o Render integrado ao GitHub, toda alteração enviada ao repositório pode gerar uma nova publicação automática da aplicação.

Isso facilita:
- Testes;
- Atualizações;
- Versionamento;
- Organização do projeto.

---

# 📌 Conclusão

A criação de APIs REST com Express.js é uma prática muito utilizada no desenvolvimento de sistemas modernos.

Ao utilizar o Render, é possível publicar a API na nuvem de forma simples, permitindo acesso online ao serviço e simulando um ambiente real de produção.

---

# 📚 Referências

- Express.js Documentation.
- Node.js Documentation.
- Render Documentation.
- GitHub Documentation.
- Material acadêmico da disciplina de Sistemas Operacionais.
