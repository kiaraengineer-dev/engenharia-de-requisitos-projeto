# Relatório de Requisitos — Prefeitura de Valiria

**Projeto:** Sistema de Distribuição de Cestas Básicas  
**Cliente:** Prefeitura de Valiria (fictício)  
**Disciplina:** Engenharia de Requisitos

## 1. Introdução

Este documento apresenta os requisitos funcionais e não funcionais identificados durante o levantamento de necessidades do cliente para o desenvolvimento de um sistema web de distribuição de cestas básicas.

## 2. Requisitos Funcionais

### [RF01] Cadastro de Beneficiários

O sistema deve permitir cadastrar beneficiários, incluindo foto do documento de identidade, dados pessoais e dependentes.

### [RF02] Validação Automática via CadÚnico

O sistema deve consultar automaticamente a base do CadÚnico para validar se o beneficiário é elegível.

### [RF03] Controle de Entregas

O sistema deve registrar cada entrega de cesta básica, garantindo que uma família receba apenas uma cesta por período.

### [RF04] Gestão de Postos de Entrega

O sistema deve permitir cadastrar e gerenciar postos de entrega, incluindo locais de difícil acesso.

### [RF05] Fluxo de Verificação Social

Assistentes sociais devem poder aprovar, reprovar ou solicitar informações adicionais sobre cadastros.

### [RF06] Perfis de Usuário

O sistema deve oferecer perfis distintos com acessos específicos:

- Administrador;
- Coordenador Regional;
- Beneficiário.

### [RF07] Acompanhamento de Status

O usuário deve poder acompanhar o status do cadastro e da entrega em tempo real.

### [RF08] Geração de Relatórios

O sistema deve gerar relatórios em gráficos e planilhas contendo:

- Número de famílias atendidas;
- Porcentagem de visitas realizadas;
- Entregas concluídas por região.

### [RF09] Autenticação Segura

O sistema deve permitir login com segurança compatível com a LGPD.

### [RF10] Notificações via WhatsApp

Enviar avisos automáticos ao beneficiário sobre:

- Aprovação do cadastro;
- Dia de retirada;
- Confirmação da entrega.

### [RF11] Integração com PostgreSQL

O sistema deve manter todos os dados armazenados no banco PostgreSQL.

## 3. Requisitos Não Funcionais

### [RNF01] Usabilidade

O sistema deve possuir interface clara e acessível para usuários com baixo nível de letramento digital.

### [RNF02] Desempenho

Consultas ao CadÚnico devem ocorrer em até 3 segundos, quando o serviço externo estiver estável.

### [RNF03] Segurança

O sistema deve utilizar:

- Criptografia de senhas;
- Controle de acesso por perfil;
- Backups automáticos;
- Conformidade com a LGPD.

### [RNF04] Disponibilidade

O sistema deve estar disponível no mínimo 95% do tempo mensal.

### [RNF05] Escalabilidade

Deve suportar aumento no número de beneficiários e regiões atendidas sem perda significativa de desempenho.

### [RNF06] Compatibilidade

A aplicação deve funcionar em qualquer navegador moderno, sem necessidade de instalação.

### [RNF07] Manutenibilidade

O código deve seguir padrões simples e estruturados para facilitar manutenção por equipes futuras.

### [RNF08] Confiabilidade

O sistema deve registrar logs de erros e eventos para auditoria de operações.

### [RNF09] Acessibilidade

As telas devem seguir boas práticas de contraste, tamanhos de texto e leitura simples.

### [RNF10] Limitações do Escopo

O sistema será exclusivamente web e não terá:

- Aplicativo mobile;
- Automações avançadas;
- Chat interno;
- Sistemas financeiros integrados.
