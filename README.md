Angular Todo List App
Este é um projeto de exemplo para criar uma aplicação Angular que consome uma API RESTful para criar, ler, atualizar e deletar itens de uma lista de afazeres (todo list).

Pré-requisitos
Antes de começar, verifique se você tem os seguintes requisitos instalados em sua máquina:

Node.js: O Node.js é uma plataforma para execução de JavaScript no servidor. Você precisará dele para instalar pacotes e rodar o servidor de desenvolvimento.

Angular CLI: O Angular CLI é uma ferramenta de linha de comando para criar, gerenciar e desenvolver aplicativos Angular. Você pode instalar o Angular CLI globalmente usando o npm (Node Package Manager). Execute o seguinte comando no terminal:

bash
Copiar código
npm install -g @angular/cli
Instalação
Clone este repositório para o seu ambiente local:

bash
Copiar código
git clone https://github.com/seu-usuario/angular-todo-list-app.git
Navegue até o diretório do projeto:

bash
Copiar código
cd angular-todo-list-app
Instale as dependências do projeto usando o npm:

Copiar código
npm install
Executando o Servidor de Desenvolvimento
Após a instalação das dependências, você pode iniciar o servidor de desenvolvimento usando o seguinte comando:

Copiar código
ng serve
Isso iniciará o servidor de desenvolvimento em http://localhost:4200/. Navegue até esse URL no seu navegador para visualizar a aplicação.

Utilização
A aplicação Todo List permite adicionar novos itens à lista, marcá-los como concluídos e deletá-los da lista.

Para adicionar um novo item, digite o nome do item no campo de texto e pressione o botão "Adicionar Item".

Para marcar um item como concluído, clique na caixa de seleção ao lado do item.

Para deletar um item, clique no botão "Deletar" ao lado do item.

Recursos Adicionais
Este projeto utiliza o Angular para o frontend e o JSON Server para simular uma API RESTful no backend. Você pode encontrar mais informações sobre o Angular em angular.io e sobre o JSON Server em json-server.dev.

Este projeto é apenas um exemplo simples e não inclui tratamento de erros robusto, autenticação de usuário, ou outros recursos comuns em aplicações reais. Ele serve como uma introdução básica ao desenvolvimento de aplicações Angular que consomem APIs RESTful.

