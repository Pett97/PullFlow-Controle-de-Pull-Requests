# PullFlow  
## Controle pessoal de Pull Requests
Um app para organizar e acompanhar suas PRs por tarefa, status, e histórico de revisão.

💡 Sobre o app
Você cria uma entrada para cada PR com informações como:

Número e título da tarefa (ex: 12143 - tela de pedidos)

Link da PR

Status (em teste, aguardando ajuste, aprovado, etc.)

Observações ou comentários


Isso te ajuda a não se perder, especialmente quando faz revisões, precisa voltar em algo ou enviar novos commits na mesma PR.

✅ Funcionalidades básicas
 
 [] Criar registro de uma PR

 [] Editar status e observações

 [] Marcar PR como concluída

 [] Visualizar lista de PRs por status

 [] Notificações para revisão pendente

 [] Exportar histórico em PDF

## 🧠 Protótipos
Figma

Tela de listagem de PRs (com status em cores)

Tela de cadastro/edição

## 🗃️ Modelagem do Banco
Tabela: pull_requests

id

titulo

numero_tarefa

link

status (em teste, aprovado, ajustes, etc.)

comentarios

data_criacao

data_conclusao

## 🗓️ Planejamento de Sprints
#### [] Sprint 1
   []Protótipos no Figma

   [] Modelagem do banco

   [x] Setup do repositório Expo

#### [] Sprint 2
   [] Cadastro de PR

   [] Lista com filtros simples

   [] Edição de status e observações

#### [] Sprint 3
   [] Histórico de alterações

   [] Validações e testes

   [] Notificações locais

#### [] Sprint 4
   [] Polimento visual

   [] Ajustes finais

   [] Testes

   [] Publicação do projeto

