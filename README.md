#  DataWho: Gestão de Dados para Pequenos Negócios




DataWho é uma plataforma web no modelo **Software as a Service (SaaS)**, projetada para ser a central de inteligência de dados de **microempresas e empresas de pequeno porte**. A solução simplifica a coleta, organização e análise de informações corporativas através de um fluxo de trabalho poderoso e intuitivo: **Formulários ➔ Tabelas ➔ Dashboards**.

Pequenos negócios precisam de dados para tomar decisões, mas frequentemente suas informações estão espalhadas em planilhas e sistemas desconectados. O DataWho centraliza todo o processo, desde a entrada de um dado de cliente até a visualização de um gráfico de vendas, em um ambiente único, seguro e acessível.

## Principais Funcionalidades

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
-   👥 **Operador**:
    -   Vinculado à empresa pelo Gestor.
    -   Opera o dia a dia do sistema.
    -   Cria formulários, insere dados e gera análises.


## Tecnologias Utilizadas

-   **Frontend**: React, Vite, Recharts, Axios, CSS Modules.
-   **Backend**: Node.js, Express.
-   **Banco de Dados**: MongoDB com Mongoose.
-   **Autenticação**: JSON Web Tokens (JWT).
