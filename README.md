# japao-liberdade
Projeto sobre o bairro da Liberdade do estado de São Paulo que irá constar informações sobre os comércios, restaurantes, museus feiras e festivais.
# 🇯🇵 Japão Liberdade

> **Tudo sobre a Liberdade em um só lugar.**

O **Japão Liberdade** é um projeto de plataforma digital dedicado ao bairro da Liberdade, em São Paulo.

A proposta é reunir, em um único lugar, informações sobre **comércios, gastronomia, cultura, eventos, promoções, notícias, transporte, pontos de interesse e organizações locais**.

O projeto busca facilitar a vida de quem visita, trabalha ou vive na Liberdade, ao mesmo tempo em que oferece aos comerciantes uma maneira gratuita de divulgar seus estabelecimentos.

---

## 🎯 Objetivo

Criar um guia digital completo e gratuito da Liberdade.

O usuário poderá descobrir:

* 🏪 Comércios
* 🍜 Restaurantes
* 🛍️ Lojas
* 🛒 Mercados
* ☕ Cafés
* 🎎 Cultura
* 📅 Eventos
* 🔥 Promoções
* 📄 Panfletos
* 📰 Notícias
* 🚌 Transporte
* 🚇 Metrô
* 🗺️ Pontos de interesse
* 🤝 Organizações locais
* 🏮 História do bairro

---

## 💡 Proposta

O Japão Liberdade não pretende ser apenas um catálogo de estabelecimentos.

A ideia é construir uma **plataforma digital da Liberdade**, reunindo:

**comércio + cultura + gastronomia + história + eventos + transporte + comunidade.**

O projeto será gratuito para visitantes e comerciantes.

> **Se estou indo para a Liberdade, eu abro o Japão Liberdade.**

---

## 👥 Público

### Visitantes

Pessoas que estão visitando a Liberdade e querem descobrir:

* Onde comer
* Onde comprar
* O que fazer
* Eventos
* Promoções
* Pontos turísticos
* Como chegar

### Moradores e trabalhadores

Pessoas que frequentam a região e querem acompanhar:

* Novos estabelecimentos
* Promoções
* Eventos
* Notícias
* Serviços
* Feiras
* Atividades culturais

### Comerciantes

Estabelecimentos que desejam divulgar gratuitamente:

* Informações
* Cardápios
* Promoções
* Eventos
* Panfletos
* Fotos
* Contatos

---

# 🚀 Funcionalidades planejadas

## 🗺️ Explorar

Mapa interativo da Liberdade com estabelecimentos e pontos de interesse.

Categorias:

* 🍜 Gastronomia
* 🛍️ Compras
* 🛒 Mercados
* ☕ Cafés
* 🎎 Cultura
* 🏮 Eventos
* 🚌 Transporte
* ⛩️ História

---

## 🏪 Comércios

Cada estabelecimento terá uma página própria contendo:

* Nome
* Categoria
* Fotos
* Endereço
* Horário de funcionamento
* Telefone
* Redes sociais
* Formas de pagamento
* Faixa de preço
* Cardápio
* Promoções
* Eventos
* Localização
* Como chegar

---

## 🔎 Busca

Busca por:

* Estabelecimento
* Categoria
* Produto
* Gastronomia
* Evento
* Promoção
* Localização

Exemplos:

```text
"Restaurante japonês"

"Lamen"

"Mercado japonês"

"Loja de anime"

"Eventos hoje"

"Promoções"
```

---

## 🔥 Promoções

Página dedicada às promoções dos estabelecimentos.

Cada promoção poderá possuir:

* Título
* Descrição
* Preço
* Imagem
* Data de início
* Data de término
* Estabelecimento

---

## 📅 Eventos

Calendário de eventos da Liberdade.

Exemplos:

* Feiras
* Festivais
* Eventos culturais
* Eventos gastronômicos
* Música
* Exposições

---

## 📰 Notícias

Área destinada a notícias e novidades relacionadas ao bairro.

Categorias:

* Comércio
* Cultura
* Eventos
* Transporte
* História
* Novidades

---

## 🎎 Cultura e história

Conteúdo sobre:

* História da Liberdade
* Imigração japonesa
* Cultura
* Arquitetura
* Ruas históricas
* Festivais
* Templos
* Associações
* Personalidades
* Curiosidades

---

## 🚌 Transporte

Informações sobre:

* 🚇 Metrô
* 🚌 Linhas de ônibus
* 🚶 Rotas a pé
* 📍 Pontos de ônibus
* 📍 Pontos de interesse

---

## 📄 Panfletos

Área para divulgação de panfletos e materiais promocionais dos estabelecimentos.

---

## 🤝 Organizações

Cadastro de:

* Associações
* Instituições
* Organizações culturais
* Templos
* Centros culturais
* Projetos comunitários

---

# 👨‍💼 Área do comerciante

Os comerciantes poderão criar uma conta gratuita e gerenciar suas informações.

Funcionalidades planejadas:

* Cadastro do estabelecimento
* Atualização de informações
* Cadastro de promoções
* Cadastro de eventos
* Cadastro de cardápio
* Upload de panfletos
* Upload de imagens

Todo conteúdo enviado poderá passar por moderação antes de ser publicado.

---

# 🔐 Administração

Área administrativa para gerenciamento da plataforma.

O administrador poderá:

* Aprovar estabelecimentos
* Editar estabelecimentos
* Remover estabelecimentos
* Aprovar promoções
* Aprovar eventos
* Gerenciar notícias
* Gerenciar panfletos
* Gerenciar organizações
* Moderar avaliações
* Gerenciar usuários

---

# 🛠️ Stack planejada

A stack ainda poderá ser alterada durante o desenvolvimento.

### Frontend

* React
* Vite
* JavaScript
* HTML
* CSS

### Backend

* Node.js
* Express

### Banco de dados

* PostgreSQL

### Mapas

* OpenStreetMap
* Leaflet

### Hospedagem

Inicialmente será avaliado o uso de:

* Render
* Railway
* Outras plataformas de baixo custo

A prioridade será manter o projeto com o menor custo possível.

---

# 🏗️ Arquitetura planejada

```text
                    JAPÃO LIBERDADE
                           │
                           ▼
                    ┌────────────────┐
                    │   FRONTEND     │
                    │                │
                    │ React/Vite/ *  │
                    └──────┬─────────┘
                           │
                          API
                           │
                           ▼
                    ┌──────────────┐
                    │   BACKEND    │
                    │              │
                    │ Node/Express*│
                    └──────┬───────┘
                           │
                           ▼
                    ┌─────────────┐
                    │ PostgreSQL* │
                    └─────────────┘
                           │
                  ┌────────┴────────┐
                  ▼                 ▼
               Mapas             Storage
                               Imagens/PDFs
```

---

# 📱 Prioridade mobile

O projeto será desenvolvido com abordagem **mobile-first**.

A experiência deve ser especialmente útil para pessoas que já estão fisicamente na Liberdade utilizando o celular.

Exemplo:

> "O que tem perto de mim?"

> "Onde posso comer?"

> "Quais eventos estão acontecendo hoje?"

> "Quais ônibus passa aqui?"

---

# 💰 Modelo

O projeto tem como princípio ser:

### Gratuito para usuários

O acesso às informações não terá cobrança.

### Gratuito para comerciantes

Comerciantes poderão cadastrar seus estabelecimentos sem mensalidade.

### Sem venda de posicionamento

A princípio, nenhum estabelecimento deverá aparecer melhor posicionado simplesmente por pagar.

A sustentabilidade financeira do projeto poderá futuramente envolver:

* Doações
* Patrocínios
* Apoio da comunidade
* Publicidade não invasiva

---

# 🗺️ Roadmap

## Fase 1 — MVP

* [ ] Estrutura inicial do projeto
* [ ] Identidade visual
* [ ] Página inicial
* [ ] Busca
* [ ] Lista de estabelecimentos
* [ ] Página de estabelecimento
* [ ] Categorias
* [ ] Mapa

## Fase 2 — Conteúdo

* [ ] Promoções
* [ ] Eventos
* [ ] Notícias
* [ ] Panfletos
* [ ] Cultura e história
* [ ] Organizações

## Fase 3 — Comerciantes

* [ ] Cadastro
* [ ] Login
* [ ] Painel do comerciante
* [ ] Cadastro de estabelecimento
* [ ] Cadastro de promoções
* [ ] Cadastro de eventos
* [ ] Cadastro de cardápio

## Fase 4 — Administração

* [ ] Painel administrativo
* [ ] Moderação
* [ ] Gerenciamento de usuários
* [ ] Aprovação de conteúdo

## Fase 5 — Evolução

* [ ] Avaliações (importação de outros lugares)
* [ ] Favoritos (se e somente se houver patrocínio para pagas despesas com banco de dados)
* [ ] Notificações 
* [ ] Geolocalização
* [ ] Melhorias de busca
* [ ] Estatísticas
* [ ] Otimização para mecanismos de busca (SEO)

---

# 📚 Documentação

A documentação do projeto ficará em:

```text
/docs
```

Documentos planejados:

* Arquitetura
* Banco de dados
* Regras de negócio
* API
* Protótipos
* Decisões técnicas
* Roadmap

---

# 🤝 Status

🚧 **Em desenvolvimento**

Este projeto está em fase de planejamento e prototipação.

A arquitetura, tecnologias e funcionalidades poderão ser modificadas conforme o desenvolvimento e os testes do produto.

---

# 🇯🇵 Visão

O objetivo final é que o Japão Liberdade se torne uma referência digital sobre o bairro:

> **Um lugar onde visitantes descobrem a Liberdade, moradores encontram o que precisam e comerciantes conseguem divulgar seus negócios gratuitamente.**


# Stacks

O site está previsto para ter o deploy ou no Render, Railway ou Fly.io, por esse motivo será estudado qual arquitetura esses servidores aceitam para adaptar os códigos para eles.

**FrontEnd**

**BackEnd**


