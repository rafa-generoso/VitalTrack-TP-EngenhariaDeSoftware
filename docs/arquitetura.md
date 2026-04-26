# Arquitetura do Sistema - HealthTrack

## Visão Geral

A aplicação será um sistema web full-stack, composto por frontend, backend e banco de dados, com comunicação via API REST.

---

## Modelo C4

O modelo C4 foi utilizado para representar a arquitetura do sistema em diferentes níveis de abstração, facilitando a compreensão da estrutura e organização da solução.

---

## Nível 1 - Diagrama de Contexto

O sistema HealthTrack interage com:

- Usuário (principal ator)
- Sistema Web (HealthTrack)

 Descrição:
O usuário acessa o sistema através de um navegador, interagindo com a aplicação para registrar e visualizar hábitos.

---

## Nível 2 - Diagrama de Contêineres

O sistema é composto por:

- **Frontend (React)**  
  Responsável pela interface do usuário

- **Backend (ASP.NET Core)**  
  Responsável pela lógica de negócio e API

- **Banco de Dados (SQL Server)**  
  Responsável pelo armazenamento dos dados

 Comunicação:
- Frontend ↔ Backend: HTTP (JSON)
- Backend ↔ Banco: conexão direta

---

## Nível 3 - Componentes (Backend)

O backend será dividido em:

- Controllers → recebem requisições HTTP  
- Services → regras de negócio  
- Models → estrutura dos dados  
- Data → acesso ao banco  

---

## Tecnologias Utilizadas

- Frontend: React  
- Backend: C# com ASP.NET Core  
- Banco de dados: SQL Server  

---

## Justificativa das Tecnologias

O React foi escolhido por sua capacidade de criar interfaces dinâmicas e reutilizáveis.

O ASP.NET Core foi escolhido por sua robustez, desempenho e ampla utilização no mercado.

O SQL Server foi escolhido pela sua confiabilidade e integração com o ecossistema .NET.

---

## Justificativa do Modelo Arquitetural

O modelo cliente-servidor foi adotado por permitir a separação entre frontend e backend, facilitando manutenção, escalabilidade e organização do sistema.

O uso do modelo C4 permite uma visualização clara da arquitetura em diferentes níveis, facilitando o entendimento do sistema.
