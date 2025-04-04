# Barber Shop Scheduler 📅✂️

Um aplicativo **Full Stack** para gerenciamento de agendamentos em uma barbearia, desenvolvido com **Java**, **Docker** e **Angular**. Esta aplicação simplifica o processo de marcação, visualização e gerenciamento de horários, garantindo uma experiência fluida para clientes e administradores.

## 📌 Funcionalidades Principais
- **Agendamento de horários:** Clientes podem marcar serviços diretamente pelo aplicativo.
- **Visualização de calendário:** Interface intuitiva para consultar horários disponíveis.
- **Gerenciamento de clientes:** Cadastro, edição e exclusão de clientes.
- **Gerenciamento de serviços:** Cadastro de serviços como corte, barba, etc.
- **Controle financeiro:** Relatório básico de receitas por serviço.
- **Responsividade:** Interface otimizada para desktop e dispositivos móveis.

## 🚀 Tecnologias Utilizadas
### Front-End:
- **Angular** 17
- **Bootstrap** para estilização
- **Ngx-Mask** para máscaras de entrada
- **Angular CDK** para componentes avançados

### Back-End:
- **Java** com **Spring Boot**
- **PostgreSQL** para banco de dados relacional

### Outros:
- **Docker** para containerização
- **Docker Compose** para orquestração de serviços
- **Mermaid** para diagramas
- **Yarn** para gerenciamento de dependências

## 🎯 Valores da Aplicação
1. **Eficiência:** Reduz tempo gasto em tarefas manuais de organização.
2. **Facilidade:** Interface intuitiva para interação com clientes e administradores.
3. **Escalabilidade:** Arquitetura modular para integração futura de novos serviços.
4. **Segurança:** Gerenciamento seguro de dados com Docker e Java.

## 🛠️ Como Rodar o Projeto
### Requisitos:
- **Docker** e **Docker Compose** instalados.
- **Node.js** na versão 20.9.0 (ou superior).
- **Angular CLI** configurado.

### Passo a Passo:
1. Clone o repositório do back-end:
   ```bash
   git clone https://github.com/Priscila-Santos/Barber-Shop-API

1. Clone o repositório do front-end:
   ```bash
   git clone https://github.com/Priscila-Santos/Barber-Shop

### 🗺️ Diagrama do Projeto
Aqui está um diagrama Mermaid para descrever os componentes do projeto:
  ```mermaid
  graph TD
    Client[Usuário / Cliente] -->|Acessa| FrontEnd[Angular App]
    FrontEnd -->|Envia requisições| BackEnd[Java Spring API]
    BackEnd -->|Consulta e Atualiza| Database[PostgreSQL]
    BackEnd -->|Retorna dados| FrontEnd
```
### 🔗 Links Úteis

- **Back-End:** [Barber-Shop-API](https://github.com/Priscila-Santos/Barber-Shop-API)
- **Documentação Angular:** [AngularCLI](https://angular.io/cli)
- **Docker:** [Docker Docs](https://docs.docker.com/)

