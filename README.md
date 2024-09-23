# Sistema de Agendamento de Atendimentos Hospitalares

Este projeto documenta a arquitetura de um sistema de agendamento de atendimentos hospitalares utilizando o **C4-Model** e a extensão **C4-PlantUML**.

## O que é o C4-Model?

O **C4-Model** é uma abordagem para descrever a arquitetura de software em diferentes níveis de detalhes, permitindo uma visão clara do sistema. Ele é dividido em quatro níveis principais:

- **Contexto**: Visão geral do sistema e como ele interage com usuários e sistemas externos.
- **Container**: Estrutura do sistema dividida em contêineres (aplicações, serviços, banco de dados, etc.).
- **Componente**: Detalhes dos principais componentes dentro dos contêineres.
- **Código (Classe)**: Zoom no código-fonte, mostrando a estrutura interna das classes.

## Sistema de Agendamento de Atendimentos Hospitalares

Funcionalidades principais do sistema:

- Agendamento de Consultas, Exames, Terapias e Procedimentos
- Gestão de Profissionais e Pacientes
- Confirmação Antecipada de Atendimentos
- Integração com Sistemas de Pagamento e Convênios
- Registro de Receitas e Prontuários Eletrônicos
- Envio de Notificações

## Roteiro

- [x] **Contexto**: Definimos a interação entre o usuário, o sistema de agendamento e os serviços externos.
- [x] **Containers**: Dividimos a arquitetura em frontend (React/React Native), backend (Spring Boot) e banco de dados (PostgreSQL).
- [x] **Componentes**: Detalhamos os componentes dentro do backend, utilizando uma arquitetura MVC.
- [x] **Código (Classe)**: Exemplificamos uma classe "Agendamento" com atributos e métodos.

## Reflexões

- É essencial usar todos os níveis do **C4-Model** para documentar a arquitetura?
- Como o uso de contêineres pode facilitar o desenvolvimento e a manutenção do sistema?
- O nível de código é necessário ou suficiente para comunicar as intenções da arquitetura?
