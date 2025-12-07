#  DataWho: Gestão de Dados para Pequenos Negócios




DataWho é uma plataforma web no modelo **Software as a Service (SaaS)**, projetada para ser a central de inteligência de dados de **microempresas e empresas de pequeno porte**. A solução simplifica a coleta, organização e análise de informações corporativas através de um fluxo de trabalho poderoso e intuitivo: **Formulários ➔ Tabelas ➔ Dashboards**.

## 🎯 O Problema que Resolvemos

Pequenos negócios precisam de dados para tomar decisões, mas frequentemente suas informações estão espalhadas em planilhas e sistemas desconectados. O DataWho centraliza todo o processo, desde a entrada de um dado de cliente até a visualização de um gráfico de vendas, em um ambiente único, seguro e acessível.

## ✨ Principais Funcionalidades

### 1. Estrutura de Acessos
O sistema é dividido em ambientes claros para garantir segurança e organização:

-   **Homepage Pública**: Ponto de entrada para conhecer a plataforma e realizar o cadastro inicial da empresa.
-   **Ambiente Corporativo Seguro**: Após o login, toda a operação ocorre em um espaço restrito, em conformidade com as boas práticas de proteção de dados.

### 2. Perfis de Usuário
Uma hierarquia de permissões que espelha a estrutura de uma empresa real:

-   👤 **Gestor**:
    -   Responsável pelo cadastro da organização.
    -   Nível máximo de permissão.
    -   Gerencia usuários (adiciona/remove) e supervisiona o ambiente.
-   👥 **Usuário**:
    -   Vinculado à empresa pelo Gestor.
    -   Opera o dia a dia do sistema.
    -   Cria formulários, insere dados e gera análises.

### 3. O Fluxo de Dados: Formulários ➔ Tabelas ➔ Dashboards

#### 📝 **Etapa 1: Formulários (Coleta de Dados)**
-   **Biblioteca de Templates**: Para acelerar a adoção, o DataWho oferece modelos de formulários prontos para áreas críticas do negócio:
    -   **Administrativo**: Cadastro de Colaboradores, Registro de Reuniões.
    -   **Financeiro**: Lançamento de Receitas e Despesas, Fluxo de Caixa.
    -   **Comercial**: Cadastro de Clientes, Pedidos de Venda, Pesquisa de Satisfação.
    -   **Operacional**: Ordem de Serviço, Check-list de Qualidade.
    -   **Estratégico**: Plano de Ação, Registro de Metas.
-   **Submissões**: Cada preenchimento de formulário é armazenado de forma segura como uma submissão.

#### 🗂️ **Etapa 2: Tabelas (Organização de Dados)**
-   **Fonte da Verdade**: O usuário seleciona as submissões de um formulário específico para gerar uma tabela.
-   **Estruturação**: As tabelas organizam as informações coletadas, servindo como a base de dados primária para todas as análises.

#### 📊 **Etapa 3: Dashboards (Análise e Visualização)**
-   **Widgets Inteligentes**: A partir de uma tabela, o usuário pode gerar visualizações dinâmicas.
-   **Tipos de Gráficos**: Suporte para gráficos de barras, pizza, linhas e mais, que se atualizam conforme novos dados são inseridos nas tabelas.
-   **Tomada de Decisão**: Transforma dados brutos em conhecimento estratégico, apoiando decisões mais rápidas e informadas.

## 🛠️ Tecnologias Utilizadas

-   **Frontend**: React, Vite, Recharts, Axios, CSS Modules.
-   **Backend**: Node.js, Express.
-   **Banco de Dados**: MongoDB com Mongoose.
-   **Autenticação**: JSON Web Tokens (JWT).
