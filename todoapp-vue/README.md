TodoList em Vue.js
Este é um simples TodoList desenvolvido com Vue.js. O projeto permite adicionar, listar e remover tarefas de uma lista interativa. Este projeto foi criado com Vue CLI para demonstrar como criar uma aplicação simples usando o framework Vue.
Funcionalidades
Adicionar tarefas à lista.
Remover tarefas da lista.
Responsivo, com layout adaptável para diferentes tamanhos de tela.
Tecnologias Utilizadas
Vue.js: Framework para construção de interfaces.
CSS: Para estilização da aplicação.
Vue CLI: Ferramenta de linha de comando para criação e desenvolvimento de projetos Vue.js.
Pré-requisitos
Antes de começar, você precisa ter instalado em sua máquina:
Node.js: Para instalar o Vue CLI e outras dependências.
NPM (gerenciador de pacotes do Node.js) ou Yarn.
Como instalar o Node.js e o NPM:
Baixe e instale o Node.js a partir de https://nodejs.org/.
Após a instalação, verifique se o Node.js e o NPM foram instalados corretamente rodando os seguintes comandos no terminal:
bash
Copiar
Editar
node -v
npm -v
Passo a Passo para Rodar o Projeto
1. Clone o Repositório
Primeiro, clone este repositório para sua máquina local.
bash
Copiar
Editar
git clone https://github.com/RafaelDFSdev/ToDoApp-Vue.git
2. Instale as Dependências
Entre no diretório do projeto e instale as dependências usando o NPM:
bash
Copiar
Editar
cd todolist-vue
npm install
Ou, se você estiver usando o Yarn:
bash
Copiar
Editar
yarn install
3. Inicie o Servidor de Desenvolvimento
Após a instalação das dependências, inicie o servidor de desenvolvimento:
bash
Copiar
Editar
npm run serve
Ou, se você estiver usando o Yarn:
bash
Copiar
Editar
yarn serve
Isso irá iniciar a aplicação em http://localhost:8080. Você pode abrir seu navegador e visualizar a aplicação.
4. Estrutura do Projeto
A estrutura do projeto é organizada da seguinte maneira:
csharp
Copiar
Editar
todolist-vue/
├── node_modules/           # Dependências do projeto
├── public/
│   ├── index.html          # Arquivo HTML principal
├── src/
│   ├── assets/             # Arquivos estáticos (ex.: imagens, CSS)
│   ├── components/         # Componentes Vue
│   ├── App.vue             # Componente principal
│   ├── main.js             # Arquivo de entrada da aplicação
├── package.json            # Configurações e dependências do projeto
└── vue.config.js           # Configurações do Vue CLI
5. Como Usar
O input de texto na tela permite adicionar uma nova tarefa.
Cada tarefa adicionada aparecerá na lista abaixo com um botão de "Remover", que pode ser usado para excluir a tarefa.
6. Personalizações
Se desejar personalizar o estilo da aplicação, você pode editar o arquivo src/App.vue ou adicionar novos componentes em src/components.
Contribuindo
Se você deseja contribuir para este projeto, sinta-se à vontade para fazer um fork e criar um pull request.
Licença
Este projeto é licenciado sob a MIT License.