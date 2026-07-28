# 🌭 Top Dog — Sistema de Pedidos Online



<div align="center">



### Aplicação web para gerenciamento de pedidos de uma hamburgueria/hotdogueria



Um sistema desenvolvido para digitalizar o processo de pedidos,

permitindo que clientes visualizem o cardápio, adicionem produtos ao carrinho

e realizem pedidos através de uma experiência simples, moderna e responsiva.



<br>



🌐 **Demo Online**

https://hotdogueria-topdog.vercel.app/



</div>



---



## 📌 Sobre o projeto



O **Top Dog** é uma aplicação web desenvolvida para uma hamburgueria/hotdogueria, com o objetivo de oferecer uma experiência digital de pedidos online.



O projeto simula uma solução real para um negócio de alimentação, permitindo que clientes naveguem pelo cardápio, filtrem produtos por categorias, adicionem itens ao carrinho e finalizem seus pedidos.



Além da interface do cliente, o projeto envolve integração com uma API própria para gerenciamento das informações relacionadas aos pedidos.



A aplicação foi desenvolvida pensando em desafios encontrados em sistemas reais, como gerenciamento de estado, organização de dados, experiência do usuário e comunicação entre Front-end e Back-end.



---



## 🎯 Objetivos do projeto



- Criar uma solução digital para gerenciamento de pedidos;

- Desenvolver uma experiência semelhante a sistemas reais de delivery;

- Aplicar conceitos avançados de React;

- Trabalhar gerenciamento de estado global;

- Integrar Front-end e Back-end;

- Desenvolver uma aplicação pensando em necessidades reais de negócios.



---



## ✨ Funcionalidades



### 🍔 Cardápio digital

- ✅ Listagem de produtos;

- ✅ Organização por categorias;

- ✅ Visualização dos detalhes dos produtos;

- ✅ Interface otimizada para navegação.



### 🛒 Carrinho de compras

- ✅ Adicionar produtos ao carrinho;

- ✅ Remover produtos;

- ✅ Alterar quantidade dos itens;

- ✅ Cálculo automático do valor total;

- ✅ Persistência das informações durante a navegação.



### 📦 Pedidos

- ✅ Criação de pedidos;

- ✅ Comunicação com API;

- ✅ Organização das informações do pedido;

- ✅ Preparação dos dados para processamento.



### 📱 Interface

- ✅ Design responsivo;

- ✅ Experiência otimizada para dispositivos móveis;

- ✅ Navegação intuitiva;

- ✅ Interface moderna.



---



## 🚀 Tecnologias utilizadas



<div>



<img src="https://skillicons.dev/icons?i=react,typescript,vite,tailwind,nodejs,express,prisma,postgres,git,github" />



</div>



## Front-end



- **React** — Construção da interface utilizando componentes reutilizáveis;

- **TypeScript** — Tipagem estática para maior segurança no desenvolvimento;

- **Vite** — Ambiente moderno de desenvolvimento;

- **Tailwind CSS** — Construção da interface responsiva;

- **React Router** — Gerenciamento de rotas;

- **React Hook Form** — Gerenciamento de formulários;

- **Yup** — Validação de dados.



## Back-end



- **Node.js** — Ambiente de execução do servidor;

- **Express** — Criação da API;

- **Prisma ORM** — Comunicação com banco de dados;

- **PostgreSQL** — Persistência das informações.



## Ferramentas



- **Git/GitHub** — Controle de versão;

- **Vercel** — Hospedagem da aplicação Front-end;

- **Render** — Hospedagem do Back-end.



---



## 🧩 Arquitetura do projeto



A aplicação foi dividida em duas partes principais:



```
topdog

├── frontend
│   ├── components
│   ├── pages
│   ├── contexts
│   ├── hooks
│   └── services
│
└── backend
    ├── routes
    ├── controllers
    ├── services
    └── prisma
```



Essa separação permite maior organização, manutenção e evolução do sistema.



---



## 🧠 Desafios enfrentados



Durante o desenvolvimento, alguns desafios importantes foram trabalhados:



### 🛒 Gerenciamento do carrinho



Um dos principais desafios foi controlar corretamente o estado dos produtos, garantindo:



- atualização das quantidades;

- cálculo correto dos valores;

- inclusão e remoção dos itens;

- sincronização das informações.



### 🔄 Comunicação entre Front-end e Back-end



Foi necessário estruturar a comunicação entre as aplicações utilizando requisições HTTP, garantindo envio correto dos dados dos pedidos.



### 📄 Organização dos pedidos



O sistema precisou lidar com a estruturação das informações enviadas pelo cliente, preparando os dados para serem processados pelo servidor.



### 📱 Experiência mobile



Como sistemas de pedidos são frequentemente utilizados em dispositivos móveis, foi necessário garantir uma interface responsiva e simples de utilizar.



---



## 📚 Aprendizados



Com esse projeto foi possível aprimorar:



- Desenvolvimento de aplicações completas Front-end e Back-end;

- Gerenciamento de estado no React;

- Integração com APIs próprias;

- Organização de projetos maiores;

- Modelagem e persistência de dados;

- Criação de soluções digitais para negócios reais.



---



## 🔮 Melhorias futuras



Algumas melhorias que podem ser implementadas:



- [ ] Painel administrativo para gerenciamento de pedidos;

- [ ] Atualização de status dos pedidos em tempo real;

- [ ] Integração com pagamentos online;

- [ ] Envio automático de notificações;

- [ ] Integração com WhatsApp;

- [ ] Sistema de autenticação para clientes.



---



## 💻 Como executar o projeto



### Front-end



Clone o repositório:



```bash
git clone https://github.com/gabriel360p/topdog-frontend.git
```



Acesse a pasta:



```bash
cd topdog-frontend
```



Instale as dependências:



```bash
npm install
```



Execute o projeto:



```bash
npm run dev
```



Acesse no navegador:



```
http://localhost:5173
```



---



## 👨‍💻 Autor



Gabriel Costa



Desenvolvedor Front-end focado em criar aplicações modernas, responsivas e soluções digitais para empresas.



🔗 GitHub:

https://github.com/gabriel360p



🔗 Portfólio:

https://gabrielcosta-dev.vercel.app/



<div align="center">



⭐ Se este projeto foi útil, considere deixar uma estrela no repositório.



</div>
