# Sistema de Distribuição de Cestas Básicas — Prefeitura de Valiria

Projeto acadêmico desenvolvido em grupo na disciplina de **Engenharia de Requisitos**, da Universidade Católica do Salvador (UCSAL).

## Sobre o projeto

O projeto consiste na especificação de um sistema web para gerenciamento da distribuição de cestas básicas a famílias em situação de vulnerabilidade social.

O cliente fictício é a **Prefeitura de Valiria**, que apresentou a necessidade de organizar e otimizar o processo de cadastro, validação e acompanhamento dos beneficiários, utilizando como referência os dados do Cadastro Único (CadÚnico).

A proposta busca proporcionar maior transparência, segurança e eficiência na distribuição de benefícios, evitando duplicidades e ampliando o atendimento às comunidades de difícil acesso.

## Objetivo

Desenvolver a documentação de requisitos de um sistema capaz de:

- Cadastrar e validar famílias beneficiárias.
- Gerenciar informações de representantes e dependentes.
- Controlar a distribuição de cestas básicas por período.
- Organizar postos e regiões de entrega.
- Gerenciar diferentes perfis de usuários e permissões.
- Acompanhar o status dos cadastros e das entregas.
- Gerar relatórios e indicadores de atendimento.

## Perfis de usuários

O sistema contempla três perfis principais:

**Administrador**
- Gerencia coordenadores regionais.
- Controla permissões de acesso.
- Visualiza relatórios gerais.
- Possui acesso global ao sistema.

**Coordenador Regional**
- Gerencia beneficiários de sua região.
- Atualiza cadastros.
- Aprova retiradas de cestas.
- Define postos de entrega.
- Consulta indicadores regionais.

**Beneficiário**
- Consulta seu próprio cadastro.
- Acompanha a situação da sua cesta básica.
- Não possui acesso aos dados de outros beneficiários.

## Requisitos do sistema

A documentação contempla:

- 11 Requisitos Funcionais (RF).
- 10 Requisitos Não Funcionais (RNF).
- Regras de negócio e restrições.
- Perfis de usuários e controle de acesso.
- Entrevista e levantamento de necessidades do cliente.

## Tecnologias e integrações previstas

- Aplicação web.
- PostgreSQL para armazenamento de dados.
- Integração com o CadÚnico para validação de beneficiários.
- Integração planejada com WhatsApp API para notificações.
- Requisitos de segurança e proteção de dados conforme a LGPD.

## Estrutura da documentação

A documentação do projeto será organizada nas seguintes etapas:

1. Entrevista com o cliente.
2. Relatório de requisitos.
3. Perfis de usuários.
4. Estudo de viabilidade.
5. Apresentação do projeto.

## Observações

Este repositório apresenta a documentação acadêmica produzida pelo grupo, considerando as necessidades e definições aceitas pelo cliente fictício durante o levantamento de requisitos.

As funcionalidades, regras de negócio e decisões registradas representam o escopo definido para o projeto, não necessariamente uma aplicação implementada.

## Informações acadêmicas

- **Instituição:** Universidade Católica do Salvador (UCSAL).
- **Disciplina:** Engenharia de Requisitos.
- **Cliente fictício:** Prefeitura de Valiria.
- **Natureza:** Projeto acadêmico em grupo.
