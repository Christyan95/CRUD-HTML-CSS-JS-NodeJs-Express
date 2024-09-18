# CRUD - HTML, CSS, JS, NodeJs e Express

# Sobre o Projeto como um todo:

. O que vamos criar é uma aplicação de controle de gastos com login com email e senha, cadastro de usuário e um CRUD (Criar, Ler, Atualizar e Remover) de receitas e despesas.

# Tecnologias utilizadas nesse repositório

. FRONTEND: HTML, Javascript e CSS puros
. AUTENTICACAO: Firebase authentication
. BANCO DE DADOS: Firebase firestore

. BACKEND: NodeJs com Express
. AUTENTICACAO: JWT
. BANCO DE DADOS: Firebase firestore

# Projeto

. Instalar node

. Iniciar um pacote npm com valores padrão
...npm init -y

. Instalar as bibliotecas
...npm install express
...npm install firebase-admin
...npm install --save-dev jest
...npm install -save-dev @babel/plugin-transform-modules-commonjs

.Adicionar no package.json antes de dependencies
..."type": "module"

.Adicionar plugin Thunder Client
...facilidade nas chamadas http

.Gerar uma nova chave privada no firebase
...Em configuracoes do projeto - contas de servico - gerar nova chave privada
......Nomear de serviceAccountKey

# Como executar o projeto

...node index.js

#

#

#

# Explicação

. CAMADA DE CONTROLLER
... Receber requisição no servidor
... Retornar resposta ao cliente

. CAMADA DE ROUTES
... Definir e organizar as rotas de acessos as funcionalidades do sistema
... Encaminhar as requisições para os controllers correspondentes

. CAMADA DE MODEL
... Contém a lógica e as regras de negócios
... Converte dados em algo que não faz sentido pro negócio

. CAMADA DE REPOSITÓRY
... Lógica de acesso aos dados
...... Banco de dados
...... APIs de terceiros
