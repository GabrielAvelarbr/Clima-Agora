<h1 align="center"> ☀️ Clima Agora </h1>

***

![Clima-agora-Preview](https://github.com/GabrielAvelarbr/Clima-Agora/assets/117688731/3326768e-4288-488d-b497-2a6412e12572)

## 🌐 Sobre o Projeto!

Este projeto consiste em uma aplicação que permite aos usuários visualizar as condições climáticas de uma cidade específica, utilizando a API OpenWeather.

Ao acessar a aplicação, os usuários são recebidos com um campo de entrada onde podem digitar o nome da cidade desejada. Após inserir o nome da cidade e clicar no botão de busca, a aplicação fornece informações precisas sobre a temperatura atual, temperatura máxima e mínima, porcentagem de umidade e velocidade do vento na cidade digitada pelo usuário.

## 📂 Estrutura do Repositório

- `public/`: Diretório que contém arquivos públicos estáticos.
    - `css/`: Arquivos de estilização.
    - `js/`: responsável pelo código JavaScript da interface do usuário.
      
- `src/`: Diretório que armazena o código-fonte do projeto.
    - `controllers/`: Lida com a lógica de entrada/saída. Recebe as requisições HTTP, chama os serviços apropriados e envia as respostas.
    - `routes/`:  Define a rota para obter as condições climáticas de diferentes cidades.
    - `services/`: Contém a lógica para para a chamada da API open weather e processar os dados retornados.
    - `views/`: Templates de visualização da aplicação.

- `.dockerignore`: Lista de arquivos e diretórios que serão ignorados pelo Docker ao construir a imagem.
- `.gitignore`: Lista de arquivos e diretórios que serão ignorados pelo Git.
- `.prettierrc`: Arquivo de configuração para o Prettier, um formatador de código.
- `Dockerfile`: Define a imagem Docker para o projeto, especificando como a aplicação deve ser construída.
- `app.js`: Arquivo principal da aplicação, onde o servidor é configurado e iniciado.
- `docker-compose.yml`: Arquivo de configuração do Docker Compose para definir e gerenciar múltiplos contêineres Docker.
- `package-lock.json`: Arquivo que descreve a árvore exata de dependências instaladas.
- `package.json`: Arquivo de configuração do npm que lista as dependências do projeto, scripts e outras informações de configuração.
  
## 🔧 Pré-requisitos

`Node.js` ou `Docker`

## 🚀 Como Usar 

1. Clone o Repositório:
    ```bash
    git clone https://github.com/Compass-pb-aws-2024-ABRIL/sprints-2-3-pb-aws-abril.git
    ```
2. Navegue até o diretório do projeto e Altere para a Branch "grupo-3":
    ```bash
    cd sprints-2-3-pb-aws-abril
    git checkout grupo-3
    ```

- **Usando npm**

3. Instale as dependências usando npm:
    ```bash
    npm install
    ```

4. Execute a Aplicação:
    ```bash
    npm run dev
    ```
    
5. Acesse a Aplicação:
   ```bash
   http://localhost
    ```
- **Usando Docker**

3. Execute a Aplicação com Docker Compose:
    ```bash
    docker compose up
    ```

4. Acesse a Aplicação:
   ```bash
   http://localhost
    ```
   
## 👨‍💻 Autor
- [Gabriel Avelar](https://github.com/GabrielAvelarbr)

