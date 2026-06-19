# 🏢 BigCondomínios

Sistema completo de **gestão de condomínios**, com funcionalidades para administração de moradores, controle de multas e operações essenciais do dia a dia condominial. Ideal para síndicos, administradoras e fins educacionais.

---

## ✨ Funcionalidades Principais

- 👤 Cadastro e gestão de moradores
- ⚠️ Registro e controle de multas
- 📊 Visualização de status e gravidade das infrações
- 📱 Interface responsiva (acessível em dispositivos móveis)
- 🔎 Filtros por status, gravidade e morador

---

## 🧾 Estrutura da Multa

Cada multa registrada possui os seguintes campos:

- **Morador**
- **Valor**
- **Data de Ocorrência**
- **Data de Vencimento**
- **Status:** `aberta`, `paga`, `vencida`
- **Gravidade:** `leve`, `moderada`, `grave`
- **Descrição**

---

## 📁 Estrutura do Projeto

BigCondominios-frontend/ # Aplicação Front-End (HTML/CSS/JS ou React)
Back-End/ # API Back-End (Java Spring Boot)
BigCondominios1.0Funcionalidades/ # Protótipos e testes adicionais

yaml
Copiar
Editar

---

## 🛠️ Tecnologias Utilizadas

- **Back-End:** Java, Spring Boot, Maven
- **Front-End:** HTML, CSS, JavaScript (puro ou framework)
- **Banco de Dados:** _(especifique aqui, ex: MySQL, PostgreSQL)_
- **Outros:**
  - [Vercel](https://vercel.com/) – Deploy do Front-End
  - [Font Awesome](https://fontawesome.com/) – Ícones

---

## ▶️ Como Rodar o Projeto

### 🔧 Back-End

1. Acesse a pasta do backend:
   ```bash
   cd Back-End
Execute o servidor:

Linux/macOS:

bash
Copiar
Editar
./mvnw spring-boot:run
Windows:

bash
Copiar
Editar
mvnw.cmd spring-boot:run
##  🌐 Front-End
Acesse a pasta do frontend:

bash
Copiar
Editar
cd BigCondominios-frontend
Se o projeto usar Node.js:

bash
Copiar
Editar
npm install
npm run dev
Ou, se for estático, abra index.html diretamente no navegador.

##  🤝 Contribuindo
Contribuições são bem-vindas! Para colaborar:

Faça um fork do repositório

Crie uma nova branch:

bash
Copiar
Editar
git checkout -b feature/nome-da-sua-feature
Faça commit das alterações:

bash
Copiar
Editar
git commit -am 'Adiciona nova funcionalidade'
Faça push para sua branch:

bash
Copiar
Editar
git push origin feature/nome-da-sua-feature
Abra um Pull Request explicando suas mudanças


##  💬 Suporte
Para dúvidas, sugestões ou problemas, abra uma issue no repositório.
Obrigado por contribuir com o BigCondomínios! 🚀

## 👨‍💻 Desenvolvido por
Abel, Bruno, Luiz e Samuel(Amigos da graduação)
Desenvolvido como prática com ASP.NET Core e frontend estático em HTML/CSS/JS.
