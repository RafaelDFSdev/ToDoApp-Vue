# ToDoList - Vue.js

Este é um projeto simples de uma **ToDo List** desenvolvido com **Vue.js**. Ele permite adicionar e remover tarefas de uma lista de maneira interativa. O objetivo deste projeto é demonstrar o uso básico do Vue.js e como criar uma aplicação de tarefas utilizando os conceitos de componentes e bindings.

## Funcionalidades

- Adicionar tarefas.
- Remover tarefas.
- Interface simples com entrada de texto para adicionar tarefas.

## Tecnologias Utilizadas

- **Vue.js**: Framework JavaScript para construção da interface.
- **CSS**: Estilização da aplicação.
- **Node.js e NPM**: Gerenciamento de pacotes e dependências.

## Pré-requisitos

Antes de começar, você precisa ter o seguinte instalado no seu sistema:

- **Node.js**: [Node.js](https://nodejs.org/)
- **NPM**: O gerenciador de pacotes do Node.js, que já vem instalado junto com o Node.js.

## Rodando o Projeto

Siga os passos abaixo para rodar o projeto em sua máquina localmente.

1. **Clone o repositório:**

   No terminal, execute o comando abaixo para clonar o repositório:

   ```bash
   git clone https://github.com/seu-usuario/todolist-vue.git

2. **Acesse o diretório do projeto:Após o clone, acesse a pasta do projeto:**
   ```bash
    cd todolist-vue
3. **Instale as dependências:**

   Execute o comando abaixo para instalar todas as dependências do projeto:

   ```bash
   npm install
4. **Rodando o servidor de desenvolvimento:**

   Após a instalação das dependências, execute o comando abaixo para iniciar o servidor de desenvolvimento:
    ```bash
    npm run serve
5. **Abra o projeto no navegador:**

   O projeto será acessível no navegador através do endereço:

   ```bash
   http://localhost:8080
## Contribuindo

Sinta-se à vontade para contribuir com o projeto! Aqui estão alguns passos para colaborar:

1. **Fork o repositório**.
   - Faça um fork do repositório para sua conta no GitHub.

2. **Crie uma branch para suas mudanças**:
   - Crie uma nova branch para a funcionalidade ou correção que você deseja implementar.
   - Utilize o comando:
     ```bash
     git checkout -b feature/nova-funcionalidade
     ```

3. **Faça o commit das suas alterações**:
   - Faça commit das alterações com uma mensagem clara e descritiva.
   - Utilize o comando:
     ```bash
     git commit -am 'Adicionando nova funcionalidade'
     ```

4. **Envie para o repositório original**:
   - Envie suas alterações para o repositório de sua fork.
   - Utilize o comando:
     ```bash
     git push origin feature/nova-funcionalidade
     ```

5. **Abra um Pull Request**:
   - No GitHub, abra um pull request para que suas alterações possam ser revisadas e mescladas ao repositório principal.
     
## Estrutura do Projeto

  ```csharp

todolist-vue/
├── public/              # Arquivos públicos
├── src/
│   ├── assets/          # Arquivos estáticos
│   ├── components/      # Componentes Vue.js
│   ├── App.vue          # Componente principal
│   ├── main.js          # Arquivo de entrada
├── babel.config.js      # Dependências e scripts
├── jsconfig.json        # Dependências e scripts
├── package.json         # Dependências e scripts
├── README.md            # Este arquivo
└── vue.config.js        # Dependências e scripts

