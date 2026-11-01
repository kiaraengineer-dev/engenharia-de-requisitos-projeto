# Entrevista com o Cliente — Prefeitura de Valiria

**Projeto:** Sistema de Distribuição de Cestas Básicas  
**Cliente:** Prefeitura de Valiria (fictício)

## 1. Contexto

O projeto visa apoiar a colaboração com o governo, utilizando a base de dados do Cadastro Único (CadÚnico) para gerenciar a distribuição de cestas básicas a famílias de baixa renda, garantindo que cada família receba apenas uma cesta por período.

## 2. Objetivo principal

Desenvolver um sistema que permita cadastrar, validar e acompanhar beneficiários de forma segura e eficiente, garantindo transparência no processo de entrega e ampliando o alcance a comunidades de difícil acesso.

## 3. Público-alvo

Famílias em situação de vulnerabilidade social, com baixa renda, cadastradas no CadÚnico e residentes em regiões de Salvador e arredores.

## 4. Problemas identificados

- Dificuldade em identificar endereços de comunidades pouco documentadas.
- Processo manual de visitas e validações sociais.
- Ausência de um sistema centralizado para coordenar os beneficiários por região.

## 5. Requisitos e funcionalidades

### 5.1 Cadastro e validação

- Cadastro de beneficiário (representante da família).
- Validação por meio de foto de identidade.
- Associação automática com o CadÚnico.
- Cadastro de dependentes, sem limite de quantidade.

### 5.2 Perfis e papéis de usuário

**Administrador**
- Cria e gerencia coordenadores.
- Visualiza relatórios.
- Controla permissões.

**Coordenador Regional**
- Gerencia beneficiários da sua área.
- Realiza atualizações.
- Aprova retiradas.

**Beneficiário**
- Consulta apenas suas próprias informações.
- Consulta a situação da cesta.

### 5.3 Fluxo operacional

1. Beneficiário comparece à instituição para cadastro.
2. Assistente social realiza visita de verificação.
3. Beneficiário fica ativo no sistema até nova avaliação.
4. Coordenadores definem postos de entrega (UPAs, escolas etc.).
5. Regiões de difícil acesso terão entregas diretas.

## 6. Relatórios e indicadores

**Número de famílias atendidas por região**
- Modelo: gráfico.
- Leitura: Coordenador.

**Percentual de visitas realizadas e cestas entregues**
- Modelo: gráfico e planilha.
- Leitura: Coordenador.

**Níveis de acesso:** somente o Administrador pode editar, excluir e permitir acessos.

## 7. Regras e restrições

- Cada beneficiário só pode visualizar seu próprio cadastro.
- Coordenadores só têm acesso à sua região.
- O Administrador é o único com acesso global.
- Atendimento aos requisitos da LGPD.
- Integração com banco de dados PostgreSQL e CadÚnico.
- Armazenamento de dados sensíveis, como CPF, endereço e informações sociais.
- Necessidade de autenticação por usuário e senha.

## 8. Requisitos técnicos

- Sistema web.
- Integração com o sistema CadÚnico para verificação.
- Integração planejada com WhatsApp (WPP API) para notificações de entrega.

## 9. Resultado esperado

- Maior alcance às comunidades de difícil acesso.
- Redução de fraudes e duplicidades.
- Facilidade de auditoria e transparência nas entregas.
- Automação do processo de cadastro, validação e entrega.
