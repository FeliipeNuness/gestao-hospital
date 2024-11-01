# gestao-hospital

# Sistema de Gestão Hospitalar

Um sistema de gestão hospitalar desenvolvido para facilitar o gerenciamento de pacientes e consultas em uma clínica ou hospital. Este projeto foi construído com foco na organização e eficiência do fluxo de informações, utilizando **React** para o frontend e **Django** para o backend.

## Funcionalidades

- **Gerenciamento de Pacientes**: Cadastro e visualização de pacientes com informações como nome, idade, endereço, telefone, histórico médico e data de nascimento.
- **Gerenciamento de Consultas**: Registro de consultas com informações sobre o paciente, data, motivo, hora e status da consulta (agendada, concluída ou cancelada).
- **Filtros por Status**: Listagem de pacientes já atendidos em uma página dedicada.
- **Atualizações de Consulta**: Possibilidade de criar, atualizar e obter consultas específicas de um paciente.
- **Responsividade**: Interface ajustada para dispositivos móveis.

## Tecnologias Utilizadas

- **Frontend**: [React](https://reactjs.org/) com [TypeScript](https://www.typescriptlang.org/) e [TailwindCSS](https://tailwindcss.com/).
- **Backend**: [Django](https://www.djangoproject.com/), com uso de Class-Based Views (CBVs) para maior modularidade.
- **Banco de Dados**: [PostgreSQL](https://www.postgresql.org/).
- **Comunicação API**: Uso do `axios` para chamadas ao backend.

## Estrutura do Projeto

```bash
hospital_management_system/
├── backend/
│   ├── manage.py
│   ├── appointments/ # App responsável pelo gerenciamento de consultas
│   └── patients/     # App responsável pelo gerenciamento de pacientes
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   ├── services/
    │   │   └── appointmentService.ts # Funções para criar, atualizar e buscar consultas
    │   └── App.tsx
    └── tailwind.config.js


