# 📌 Sistema de Gestão de Serviços a Clientes

## 📖 Descrição
Este projeto consiste no desenvolvimento de um sistema de gestão de tarefas voltado para freelancers, permitindo-lhes registar o trabalho realizado diariamente e calcular o valor adequado a cobrar aos seus clientes.

O sistema inclui funcionalidades como a criação de contas, gestão de projetos e tarefas, controlo de tempo, relatórios financeiros e colaboração entre utilizadores.

## 🚀 Funcionalidades Principais

### 🔐 Autenticação e Conta do Utilizador
- Criação de conta e login.
- Edição de informações pessoais (nome, credenciais e número de horas de trabalho diário).

### 📂 Gestão de Projetos
- Criar, editar e remover projetos.
- Definir nome do cliente e preço por hora.
- Opção de apagar ou desassociar tarefas ao excluir um projeto.
- Mover tarefas entre projetos ou torná-las independentes.

### ✅ Controlo de Tarefas
- Criar tarefas com descrição e data/hora de início.
- Associar tarefas a um projeto com preço hora padrão.
- Finalizar tarefas com data/hora de término.
- Listar todas as tarefas em curso e calcular tempo total gasto.
- Listar tarefas finalizadas dentro de um período de datas.
- Remover tarefas em curso ou finalizadas.

### 🤝 Colaboração em Projetos
- Convidar outros utilizadores para colaborar em projetos.
- Aceitar ou recusar convites.
- Gerir permissões, permitindo a colaboração em tarefas.
- Remover utilizadores convidados de um projeto.

### 📊 Relatórios e Estatísticas
- Geração de relatórios mensais pessoais:
  - Lista de tarefas realizadas por dia, incluindo informação do projeto.
  - Número total de horas por dia e no mês.
  - Cálculo do valor financeiro total baseado no preço por hora.
  - Sinalização de dias em que o utilizador excedeu o limite de horas diárias.
- Geração de relatórios mensais por projeto e cliente:
  - Exibição dos utilizadores que trabalharam nas tarefas diárias.
  - Tempo total gasto por projeto e cliente.

## 🛠️ Tecnologias Utilizadas
- **Linguagem de programação:** C#
- **Framework:** .NET (Windows Forms)
- **Base de Dados:** SQL Server / SQLite
- **Controlo de Versão:** Git & GitHub

## 🏁 Como Executar o Projeto
### 🔧 Requisitos
- .NET SDK instalado
- SQL Server ou SQLite configurado

### 📥 Instalação e Execução
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-utilizador/nome-do-repositorio.git
   cd nome-do-repositorio
   ```
2. Abra o projeto no **Visual Studio**.
3. Configure a base de dados e execute as migrações (se aplicável).
4. Compile e inicie a aplicação.

## 📜 Licença
Este projeto está sob a [Licença MIT](https://opensource.org/licenses/MIT).

