# 🧴 LimpeExpress

O **LimpeExpress** é um aplicativo mobile desenvolvido para facilitar a compra de produtos de limpeza de forma rápida, prática e segura. A plataforma permite que clientes realizem pedidos diretamente pelo celular e recebam seus produtos em casa por meio de motoboys cadastrados no sistema.

Este projeto foi desenvolvido como parte da disciplina de Desenvolvimento Mobile, com o objetivo de aplicar os conhecimentos adquiridos durante o semestre na construção de um **MVP (Produto Mínimo Viável)**.

📖 Visão Geral

Muitas pessoas precisam comprar produtos de limpeza para suas casas ou estabelecimentos, mas nem sempre possuem tempo para se deslocar até uma loja física. Além disso, encontrar produtos com preços acessíveis e entrega rápida pode ser um desafio.

O **LimpeExpress** foi criado para solucionar esse problema, oferecendo uma plataforma simples e intuitiva que permite aos usuários comprar produtos de limpeza pelo celular e recebê-los em casa através de entregadores cadastrados.


🎯 Objetivos

* Desenvolver um aplicativo mobile funcional.
* Aplicar os conhecimentos adquiridos na disciplina.
* Criar uma plataforma simples e intuitiva para compra de produtos de limpeza.
* Disponibilizar uma área exclusiva para motoboys realizarem entregas.
* Entregar um MVP funcional ao final do semestre.

---
 👥 Público-Alvo

O aplicativo é destinado a:

* Pessoas entre 18 e 65 anos.
* Donas de casa.
* Pequenos comerciantes.
* Empresas que utilizam materiais de limpeza.
* Usuários de smartphones Android.
* Pessoas que buscam praticidade na compra de produtos de limpeza.

---

 🚀 Funcionalidades

Cliente

* Cadastro de usuário.
* Login.
* Visualização de produtos.
* Busca de produtos.
* Carrinho de compras.
* Finalização de pedidos.
* Acompanhamento do status da entrega.

 Motoboy

* Login.
* Visualização das entregas disponíveis.
* Aceitar entregas.
* Atualizar o status da entrega.
* Concluir entregas.

 Administrador

* Gerenciar produtos.
* Gerenciar pedidos.
* Gerenciar entregadores.

---

 ⭐ Funcionalidades Futuras

* Modo escuro.
* Avaliação de produtos.
* Avaliação de entregadores.
* Histórico de compras.
* Cupons de desconto.
* Sistema de promoções.
* Chat entre cliente e entregador.
* Notificações em tempo real.

---

 🛠 Tecnologias Utilizadas

Front-end

* React Native
* Expo

 Back-end

* Node.js

 Banco de Dados

* PostgreSQL

 Serviços

* Google Maps API
* API de Geolocalização
* Expo Notifications
* Firebase Authentication (opcional)

---

 📂 Estrutura do Projeto

```text
LimpeExpress/
│
├── app/
├── assets/
├── components/
├── screens/
├── services/
├── navigation/
├── database/
├── utils/
├── package.json
└── README.md
```

---

 🗄 Modelagem Conceitual

 Entidades

 Usuário

* id
* nome
* email
* senha
* telefone
* endereço

 Produto

* id
* nome
* descrição
* preço
* estoque
* imagem

 Pedido

* id
* data
* valor total
* status

 Entrega

* id
* status
* localização
* data

 Motoboy

* id
* nome
* telefone
* veículo

---

# 🔗 Relacionamentos

* Um **Usuário** pode realizar vários **Pedidos**.
* Um **Pedido** contém um ou mais **Produtos**.
* Cada **Pedido** gera uma **Entrega**.
* Um **Motoboy** pode realizar diversas **Entregas**.

---

 📋 Histórias de Usuário

 Cliente

* Como cliente, desejo visualizar os produtos disponíveis.
* Como cliente, desejo adicionar produtos ao carrinho.
* Como cliente, desejo finalizar um pedido.
* Como cliente, desejo acompanhar o status da entrega.
 Motoboy

* Como motoboy, desejo visualizar as entregas disponíveis.
* Como motoboy, desejo aceitar uma entrega.
* Como motoboy, desejo atualizar o status da entrega.

 Administrador

* Como administrador, desejo cadastrar e editar produtos.
* Como administrador, desejo gerenciar pedidos.
* Como administrador, desejo gerenciar entregadores.

---

 📱 Fluxo do Aplicativo

```text
Login/Cadastro
       │
       ▼
Tela Inicial
       │
       ▼
Lista de Produtos
       │
       ▼
Carrinho
       │
       ▼
Finalizar Pedido
       │
       ▼
Entrega
       │
       ▼
Pedido Concluído
```

---

 💾 Banco de Dados

O PostgreSQL será responsável pelo armazenamento das seguintes informações:

* Usuários
* Produtos
* Pedidos
* Entregas
* Motoboys

---

 🌟 Diferenciais

* Interface simples e intuitiva.
* Compra rápida de produtos de limpeza.
* Área exclusiva para motoboys.
* Acompanhamento do status da entrega.
* Integração com serviços de localização.
* Estrutura preparada para futuras funcionalidades.

---

 🚧 Status do Projeto

O projeto encontra-se em desenvolvimento e está sendo construído como um **MVP (Produto Mínimo Viável)** para fins acadêmicos.

---

 👨‍💻 Equipe

Projeto desenvolvido para a disciplina de **Desenvolvimento Mobile**, com foco na aplicação prática dos conhecimentos adquiridos durante o semestre.

---

 📄 Licença

Este projeto possui finalidade exclusivamente acadêmica e educacional.
