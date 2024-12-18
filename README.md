# Cadastro de Clientes - Sistema de Gestão para Loja

## Demonstração
Se você quiser ver o sistema em ação, clique no seguinte link para uma demonstração ao vivo do projeto: [Demo do Sistema](#)

## Sumário
1. [Título do Projeto](#título-do-projeto)
2. [Demonstração](#demonstração)
3. [Entendimento do Negócio](#entendimento-do-negócio)
4. [Entendimento dos Dados](#entendimento-dos-dados)
5. [Capturas de Tela/Visualizações](#capturas-de-tela-visualizações)
6. [Tecnologias Utilizadas](#tecnologias-utilizadas)
7. [Configuração](#configuração)
8. [Abordagem](#abordagem)
9. [Status do Projeto](#status-do-projeto)
10. [Créditos](#créditos)

## Título do Projeto
Este projeto consiste em um **sistema de cadastro de clientes** para uma loja. Ele permite gerenciar dados de clientes, realizar vendas, emitir recibos, consultar histórico de compras, e gerar relatórios. A ideia é facilitar o controle de informações e melhorar a experiência tanto para os funcionários quanto para os clientes da loja.

## Demonstração
- Se você tiver interesse em ver o funcionamento do projeto, temos uma **demonstração online** que pode ser acessada [aqui](#).
- A demonstração inclui as principais funcionalidades do sistema, como cadastro, consulta e atualização de dados de clientes.

## Entendimento do Negócio
A principal **necessidade de negócio** que esse sistema resolve é a gestão eficiente do cadastro de clientes, proporcionando agilidade no atendimento e controle das informações. Ao integrar a base de dados dos clientes, o sistema permite aos vendedores acessar rapidamente informações sobre compras anteriores, possibilitando um atendimento personalizado e eficaz.

### Objetivos do Projeto:
- Facilitar o processo de **cadastro de novos clientes**.
- Melhorar a **organização e o controle** dos dados dos clientes.
- Ajudar a **gerar relatórios de vendas** e históricos de compras.

## Entendimento dos Dados
Para este sistema, os dados são armazenados em uma base de dados relacional. Cada cliente tem um conjunto de informações como nome, e-mail, número de telefone, histórico de compras, entre outros. Esses dados são usados para:
- Cadastro e consulta rápida de clientes.
- Gerar relatórios sobre compras e comportamento de compra.

Os dados podem ser importados de **planilhas** ou inseridos manualmente via interface do usuário.

## Capturas de Tela/Visualizações
### Tela Inicial
![Tela Inicial](imagens/tela_inicial.png)

### Cadastro de Cliente
![Cadastro de Cliente](imagens/cadastro_cliente.png)

### Histórico de Compras
![Histórico de Compras](imagens/historico_compras.png)

## Tecnologias Utilizadas
- **Frontend**: HTML, CSS, JavaScript (React)
- **Backend**: Node.js, Express
- **Banco de Dados**: MongoDB
- **Autenticação**: JWT (JSON Web Tokens)
- **Testes**: Jest, Mocha
- **Outros**: Docker (para containerização), Nginx (para proxy reverso)

## Configuração
### Requisitos
- Node.js >= 14.x
- MongoDB
- Docker (opcional, para configuração em container)

### Como Instalar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/cadastro-de-clientes.git
   cd cadastro-de-clientes
   
2. Instale as dependências:
   ```bash
   npm install

3. Configure o banco de dados (crie um banco no MongoDB):
   ```bash
   mongo --host localhost --port 27017

4. Inicie o servidor:
   ```bash
   npm start

## Como Usar
1. Acesse o sistema pelo navegador em `http://localhost:3000`.
2. Cadastre um cliente e faça consultas rápidas.
3. Acesse a funcionalidade de geração de relatórios no menu principal.

## Abordagem
O desenvolvimento desse projeto seguiu uma abordagem ágil, utilizando as melhores práticas de desenvolvimento de software, como:

- Planejamento inicial das funcionalidades e objetivos.
- Desenvolvimento iterativo, com foco em testes constantes para garantir que cada funcionalidade fosse integrada de forma eficiente.
- Interface simples e responsiva, pensando sempre no usuário final, que pode ser tanto o funcionário da loja quanto o cliente.

## Status do Projeto
- **Versão atual**: 1.0
- **Status**: Em andamento, algumas funcionalidades estão em processo de otimização, como a geração de relatórios de vendas.

## Créditos
- **Desenvolvedor Principal**: Seu Nome
- **Apoio**: [Mentor ou nome de colaborador, se houver]
- **Design**: [Nome do Designer ou ferramenta utilizada, se aplicável]
