## 🌐 [English Version of README](README_EN.md)

# Imersão Dev Back-End

Bem-vindo à **Imersão Dev Back-End** da Alura! Este projeto foi desenvolvido para criar uma API que permite o gerenciamento de posts com upload de imagens, conectando um servidor local ao MongoDB e utilizando a API Google Gemini para gerar descrições automáticas de imagens.

## 🔨 Funcionalidades do Projeto

- **Listagem de Posts:** Exibe todos os posts armazenados no banco de dados.
- **Criação de Posts:** Permite criar novos posts com texto e/ou imagens.
- **Atualização de Posts:** Atualiza informações dos posts existentes, incluindo descrições geradas automaticamente.
- **Upload de Imagens:** Suporte ao upload e armazenamento local de imagens.
- **Descrição Automática de Imagens:** Integração com a API Google Gemini.

## ✔️ Técnicas e Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript no servidor.
- **Express.js**: Framework para criação de APIs REST.
- **MongoDB**: Banco de dados NoSQL para armazenamento de posts.
- **Mongoose**: Biblioteca para modelagem de dados com MongoDB.
- **Google Gemini API**: Utilizada para gerar descrições automáticas de imagens.
- **Google Cloud Platform (GCP)**: Plataforma de deploy para o projeto.
- **JavaScript ES6+**: Uso de modernas funcionalidades da linguagem.

## 📁 Estrutura do Projeto

- **Base/**: Arquivos de suporte e pacotes extras.
- **Extra/**: Materiais adicionais, como wallpapers.
- **src/**: Código-fonte principal.
    - **config/**: Configurações do projeto, como conexão com o banco de dados.
    - **controllers/**: Lógica das requisições HTTP.
    - **models/**: Definições e operações com o banco de dados.
    - **services/**: Integração com a API Google Gemini.
- **uploads/**: Diretório para armazenamento de imagens enviadas.
- **server.js**: Arquivo principal que inicializa o servidor.
- **package.json**: Lista de dependências e scripts do projeto.

## 🛠️ Abrir e rodar o projeto

1. **Certifique-se de ter o Node.js instalado**:
    - Verifique a instalação:
      ```bash
      node -v
      ```
    - Caso necessário, faça o download do [Node.js](https://nodejs.org/).

2. **Clone o Repositório**:
    - Utilize o comando:
      ```bash
      git clone <URL_DO_REPOSITORIO>
      ```

3. **Instale as Dependências**:
    - Entre na pasta do projeto e execute:
      ```bash
      npm install
      ```

4. **Configure as Variáveis de Ambiente**:
    - Crie um arquivo `.env` na raiz do projeto e insira:
      ```env
      STRING_CONEXAO=<URL_DO_SEU_MONGODB>
      GEMINI_API_KEY=<SUA_CHAVE_DA_API_GEMINI>
      ```

5. **Inicie o Servidor**:
    - Utilize o comando:
      ```bash
      npm start
      ```

6. **Teste os Endpoints**:
    - Use ferramentas como **Postman** ou **Insomnia** para testar os endpoints da API.

## 🌐 Deploy

### Como fazer o deploy na Google Cloud Platform (GCP):

1. **Crie um Projeto no GCP**:
    - Acesse o [Google Cloud Console](https://console.cloud.google.com/) e crie um novo projeto.

2. **Ative a API Google Gemini**:
    - Ative a **Google Generative AI API** no projeto.

3. **Hospede a Aplicação**:
    - Use o **App Engine** ou **Cloud Run** para hospedar o servidor Node.js.
    - Configure as variáveis de ambiente diretamente na plataforma.

4. **Teste o Deploy**:
    - Acesse a URL gerada pelo GCP para testar o funcionamento da API.

## 📲 Recursos e Comunidade

- **Dicas e Recursos Extras:** Explore os materiais complementares no [Guia de Mergulho](https://www.notion.so/Imers-o-Dev-Back-End-Guia-de-Mergulho-31067142b5d54643a32edbb158f8e681?pvs=21).
