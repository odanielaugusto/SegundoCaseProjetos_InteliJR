---
sidebar_position: 1
---

# 📄 Visão de Produto

## 🗓 Informações Gerais

- **Nome do Projeto:** 
InteliHub – Plataforma de gestão e acompanhamento tanto do cliente quanto da Inteli Júnior.

- **Cliente:** 
Inteli Júnior

- **Responsável da Visão de Produto (PO):**
João Dias, Felipe Teixeira, Daniel Augusto, Rayssa Guedes, Livia Negrini, Messias Olivindo, Rodrigo Ferraz.

---

## 📘 Resumo do Projeto

### Projeto: Landing Page Institucional e Plataforma Web - Inteli Júnior

#### Entregáveis de Valor

1. **Landing Page Institucional**  
   - Objetivo: Apresentar a Inteli Júnior ao público externo, explicando o que é a empresa e como ela funciona.

2. **Plataforma Web**  
   - Objetivo: Ferramenta para Diretores, Membros, Leads e Clientes focada em:
     - Gestão de projetos
     - Acompanhamento de equipes e entregas

#### Contexto

O projeto surgiu da necessidade de:
- Fortalecer a presença digital da empresa
- Organizar e centralizar processos internos
- Resolver problemas como:
  - Falta de visibilidade online
  - Gestão descentralizada de informações
  - Baixa integração entre áreas

A solução proposta oferecerá um sistema eficiente e acessível para clientes, membros e gestores.

#### Descrição

Desenvolver:
- **Uma landing page institucional** para apresentar a Inteli Júnior ao público externo
- **Uma plataforma web** para centralizar:
  - Gestão de projetos
  - Gestão de equipes
  - Comunicação interna da empresa júnior

#### Objetivos

- Fortalecer a presença digital da Inteli Júnior
- Centralizar a gestão de projetos e equipes
- Facilitar a comunicação entre membros, diretores e clientes

#### Público-Alvo

- Equipe interna da Inteli Júnior (Diretores, Membros e Leads)
- Clientes atuais
- Potenciais clientes interessados nos serviços da empresa

#### 👤 Personas

1. Inteli Junior:
   a) Presidência (presidente e vice): Acessam a plataforma como administradores gerais e gerenciam a permissão de todos os membros e configurações da plataforma. 
   b) Diretores: Acessam a plataforma para controlar  os  dados, gerir os membros de seus setores e visualizar andamento dos projetos.
   c) Membros: Acessam a plataforma para alimentar os dados dos projetos e gerenciar tanto seu trabalho indivdual quanto atualizar os outros respectivos membros e diretores da sua área sobre o andamento do projeto

2. Clientes:
   a) Atuais: Acompanham o andamento do projeto pela plataforma de forma visual, com informações sobre entregáveis e membros responsáveis.
   b) Potenciais: Descobrem o que é a inteli júnior pela landing page, visualizando provas sociais, projetos entregues e quem são os responsaveis pela empresa júnior.

**Principais Funcionalidades:**
1. Inteli Júnior:
    - Cadastro e login com diferentes níveis de permissão (presidência, diretores e membros).
    - Painel administrativo para presidência e diretores gerenciarem dados e equipes.
    - Visualização do andamento dos projetos com status, entregáveis, responsáveis.
    - Atualização de informações pelos membros diretamente na plataforma.
    - Gerenciamento de usuários e permissões conforme as áreas da empresa

2. Clientes:
    - Cadastro e login para acompanhamento do projeto contratado.
    - Acesso a landing page institucional com informações sobre a empresa, serviços, projetos, formas de contato e equipe.

---

## 🧩 Matriz "É / Não É / Faz / Não Faz"
<div align="center">

| Categoria  | Descrição |
|-----------|-----------|
| **É**     | Uma aplicação web para gestão de projetos internos e acompanhamento de clientes, além de uma landing page institucional.  |
| **Não É** | Não substitui reuniões estratégicas ou operacionais entre membros da Inteli Júnior. |
| **Faz**   | Permite cadastro e login de usuários, gestão de permissões, acompanhamento de projetos, edição de dados, visualização de projetos e visibilidade/reconhecimento da Inteli Júnior. |
| **Não Faz** | Substitui totalmente a comunicação humana entre Inteli Júnior e os clientes por meio de videoconferências ou realiza controle financeiro detalhado (como emissão de faturas e manipulação de dados para calculo como um ERP faria). |

</div>

---

## 🧠 Matriz de Certezas, Suposições e Dúvidas

<div align="center">

| Tipo        | Descrição                                                                |
|-------------|--------------------------------------------------------------------------|
| **Certeza**   | A plataforma deve permitir a gestão de projetos com diferentes níveis de acesso (presidência, diretores, membros, clientes). |
| **Suposição** | Acreditamos que os clientes usarão principalmente a plataforma para acompanhar o progresso dos projetos, e a landing page será o primeiro ponto de contato. |
| **Dúvida**    | O dashboard será suficiente para que os clientes se sintam atualizados sobre seus projetos, ou ainda será necessária uma comunicação humana via reunião recorrente? |

</div>

# Épicos e User Stories - Plataforma Inteli Junior

## Epic 1: Gestão de Projetos (Diretor de Projetos)

**Descrição:**  
Como diretor de projetos, quero um ambiente para gerenciar projetos da minha área, para que as informações sejam acessíveis à equipe, à empresa e aos clientes.

### User Stories:

**US 1.1 - Criar Projeto**  
- Como diretor de projetos, quero criar projetos preenchendo nome, tipo, links relevantes, membros, data de entrega e cliente associado.

**Critérios de Aceite:**
- Formulário de criação com todos os campos listados.
- Validação obrigatória para campos essenciais (nome, tipo e data de entrega).
- Opção de salvar e visualizar projeto após cadastro.

**US 1.2 - Editar Projeto**  
- Como diretor de projetos, quero editar as informações dos projetos já cadastrados.

**Critérios de Aceite:**
- Edição disponível apenas para projetos ativos.


**US 1.3 - Excluir Projeto**  
- Como diretor de projetos, quero excluir projetos que não são mais relevantes.

**Critérios de Aceite:**
- Confirmação de exclusão com alerta.
- Apenas usuários autorizados podem excluir.

**US 1.4 - Dashboard de Projetos**  
- Como diretor de projetos, quero visualizar uma dashboard com o status dos projetos.

**Critérios de Aceite:**
- Visualização de métricas: total de projetos ativos, dentro do prazo, fora do prazo, próximos da entrega e distribuição por tipo.
- Atualização automática dos dados.

**US 1.5 - Acesso de Clientes**  
- Como cliente, quero acessar o andamento dos meus projetos por meio de chave de acesso.

**Critérios de Aceite:**
- Sistema de login por chave.
- Visualização restrita ao projeto do cliente.

**US 1.6 - Barra de Progresso Automática**  
- Como usuário, quero visualizar o andamento do projeto com base na data atual e na data de entrega.

**Critérios de Aceite:**
- Barra de progresso automática atualizada diariamente.
- Visualização no card do projeto.

---

## Epic 2: Gestão de Parcerias (Diretor de Relações Institucionais)

**Descrição:**  
Como diretor de relações institucionais, quero cadastrar e gerenciar parcerias e ativações para acompanhar o relacionamento com empresas.

### User Stories:

**US 2.1 - Cadastro de Parceria**  
- Como diretor, quero registrar novas parcerias com informações sobre a empresa e tipo de relacionamento.

**Critérios de Aceite:**
- Cadastro de nome da empresa, tipo de parceria, data de início e status.

---

**US 2.2 - Edição de Parceria**

- Como diretor, quero editar os dados de uma parceria cadastrada, para manter as informações sempre atualizadas e corrigir possíveis erros.

**Critérios de Aceite:**
- Permitir edição de: nome da empresa, tipo de parceria, data de início, e status (ativa/inativa).
- Somente usuários com perfil de Diretor de RI podem realizar edições.

---

**US 2.3 - Exclusão de Parceria**
- Como diretor, quero excluir uma parceria do sistema, para remover registros que foram inseridos incorretamente ou que não são mais relevantes.

**Critérios de Aceite:**
- Exclusão apenas disponível para usuários com permissão de Diretor.
- Exigir confirmação antes da exclusão.
- Parceria excluída não deve estar vinculada a ativações registradas (ou exigir exclusão prévia dessas ativações).

---

**US 2.4 - Visualizar Histórico de Ativações**  
- Como diretor, quero ver o histórico de ativações realizadas com cada parceiro.

**Critérios de Aceite:**
- Lista de ativações vinculada ao cadastro do parceiro.
- Data e descrição da ativação.



---

## Epic 3: Gestão de Pessoas (Diretor de Gestão de Pessoas)

**Descrição:**  
Como diretor de gestão de pessoas, quero acessar e atualizar as informações de desenvolvimento dos membros.

### User Stories:

**US 3.1 - Visualizar Membros**  
- Como diretor, quero visualizar uma lista com nome e informações essenciais dos membros para ter uma visão geral da equipe.

**Critérios de Aceite:**
- Exibição de todos os membros cadastrados com suas informações essenciais.

**US 3.2 - Acessar Perfil do Membro**  
- Como diretor, quero acessar o perfil de cada membro para analisar suas informações individuais.

**Critérios de Aceite:**
- Informações disponíveis: objetivos profissionais, habilidades e forças.

--- 

**US 3.3 - Solicitar Adição de Novo Membro e Criar Informações de Desenvolvimento**  
- Como diretor de gestão de pessoas,  quero solicitar a adição de um novo membro ao sistema e já registrar suas informações iniciais, para iniciar o acompanhamento desde o ingresso e garantir sua integração ao processo de crescimento da EJ.

**Critérios de Aceite:**
- O diretor preenche um formulário com os dados do novo membro: nome completo, e-mail institucional, cargo, data de ingresso e foto.
- A solicitação é enviada para aprovação do Presidente ou Vice-presidente.
- Somente após a aprovação, o membro é oficialmente adicionado ao sistema.
- Após a aprovação, o perfil do membro deve estar visível na lista geral.
- A solicitação negada deve apresentar justificativa e notificar o diretor solicitante.

---

**US 3.4 - Atualizar Informações de Desenvolvimento**  
- Como diretor, quero editar informações do cadastro de cada membro, para refletir mudanças nas metas e progresso individual.

**Critérios de Aceite:**
- Formulário de atualização de dados.
- Histórico de alterações salvo automaticamente.

---

**US 3.5 - Excluir Informações de Desenvolvimento**  
- Como diretor, quero remover registros de desenvolvimento, para eliminar dados desatualizados, duplicados ou inválidos.

**Critérios de Aceite:**
- Exclusão com confirmação prévia.
- Apenas o Diretor de Gestão de Pessoas pode excluir.
- Exibição de alerta sobre a perda de dados históricos.

---

## Epic 4: Coleta de Métricas e Eficiência (Diretor Administrativo-Financeiro)

**Descrição:**  
Como diretor administrativo-financeiro, quero visualizar métricas de performance e eficiência das áreas.

### User Stories:

**US 4.1 - Visualizar Métricas de Áreas**  
- Como diretor, quero acompanhar as métricas de cada área da empresa.

**Critérios de Aceite:**
- Indicadores claros e atualizados periodicamente.
---

## Epic 5: Gestão Comercial (Diretor de Vendas)

**Descrição:**  
CComo diretor de vendas, quero cadastrar, visualizar, atualizar e excluir informações comerciais para gerenciar o funil de vendas e fechar contratos com mais eficiência.

### User Stories:

**US 5.1 - Cadastro de Propostas**  
- Como diretor, quero cadastrar e registrar potenciais clientes e iniciar o acompanhamento comercial.

**Critérios de Aceite:**
- Formulário de cadastro de lead com nome do cliente, serviço prestado, valor e status de andamento da venda.

**US 5.2 - Atualização de Status de Vendas**  
- Como diretor, quero atualizar o status das vendas em andamento.

**Critérios de Aceite:**
- Mudança de status da proposta de enviada para em negociação ou aprovada.

**US 5.3 - Dashboard de Vendas**  
- Como diretor, quero visualizar a evolução das vendas no sistema, para acompanhar os resultados e analisar o funil comercial.

**Critérios de Aceite:**
- Gráficos de conversão e pipeline de vendas.


---

## Epic 6: Gestão Estratégica (Presidente)

**Descrição:**  
Como presidente, quero visualizar o panorama geral da empresa com métricas estratégicas e status financeiro.

### User Stories:

**US 6.1 - Visualizar Dashboard Executivo**  
- Como presidente, quero um dashboard resumido de todas as áreas.

**Critérios de Aceite:**
- KPIs estratégicos exibidos em painel único.

**US 6.2 - Acesso a Relatórios Estratégicos**  
- Como presidente, quero acessar outras áreas da empresa para enxergar seus dados de performance.

**Critérios de Aceite:**
- Acesso a outras áreas da empresa.


---

## Epic 7: Suporte à Gestão Estratégica (Vice-Presidente)

**Descrição:**  
Como vice-presidente, quero acessar informações de performance das outras áreas e indicadores estratégicos para apoiar a presidência.

### User Stories:

**US 7.1 - Visualizar Relatórios de Performance**  
- Como vice-presidente, quero acompanhar a performance de cada área.

**Critérios de Aceite:**
- Acesso a outras áreas das empresa junior.

---

## Epic 8: Acompanhamento Individual (Membros de Área)

**Descrição:**  
Como membro de uma área, quero acessar a interface da minha área.

### User Stories:

**US 8.1 - Atualizar Minhas Informações Pessoais**  
- Como membro, quero atualizar meu perfil e habilidades.

**Critérios de Aceite:**
- Edição de informações pessoais com histórico.


---

## Epic 9: Acesso de Clientes Externos

**Descrição:**  
Como cliente, quero acessar o projeto contratado e acompanhar seu andamento.

### User Stories:

**US 9.1 - Login Seguro com Chave de Acesso**  
- Como cliente, quero acessar a aplicação de forma segura.

**Critérios de Aceite:**
- Sistema de autenticação funcional.

**US 9.2 - Visualizar Progresso do Meu Projeto**  
- Como cliente, quero ver atualizações do projeto.

**Critérios de Aceite:**
- Timeline de entregas e status atualizado.

**US 9.3 - Visualizar Entregas e Datas Importantes**  
- Como cliente, quero acompanhar as principais entregas.

**Critérios de Aceite:**
- Exibição de marcos do projeto.

## Epic 10: Gestão de Eventos (Diretor de Relações Institucionais)

**Descrição:**  
Como diretor de relações institucionais, quero criar, editar, excluir e acompanhar eventos institucionais (parcerias, ativações, workshops, feiras, etc.), para organizar o calendário da Inteli Júnior e garantir que toda a equipe esteja alinhada às próximas iniciativas.

### User Stories:

**US 10.1 – Criar Evento**  
- Como diretor de RI, quero cadastrar um novo evento preenchendo nome, tipo, data, horário, local, prioridade e parceiro associado.

**Critérios de Aceite:**
- Formulário de criação com campos obrigatórios: nome, tipo, data, horário, local e prioridade.    

---

**US 10.2 – Editar Evento**  
- Como diretor de RI, quero editar as informações de um evento já cadastrado para manter os dados sempre atualizados.

**Critérios de Aceite:**
- Permitir edição de todos os campos, exceto ID interno.  
---

**US 10.3 – Excluir Evento**  
- Como diretor de RI, quero excluir eventos cancelados ou criados erroneamente para manter o quadro de eventos limpo.

**Critérios de Aceite:**
- Exclusão restrita aos usuários com papel Diretor de RI ou superior.  


---

**US 10.4 – Visualizar Calendário de Eventos**  
- Como usuário autorizado, quero visualizar um quadro mensal com todos os eventos, para ter uma visão clara das próximas atividades.

**Critérios de Aceite:**
- Exibição em modo calendário (mensal) e modo lista.  
- Eventos coloridos por prioridade (baixa, média, alta).  
- Contador de “Eventos Planejados” visível acima do calendário.

---

**US 10.5 – Checklist de Infraestrutura do Evento**  
- Como diretor de RI, quero adicionar um checklist de tarefas (infraestrutura, comunicação, logística) a cada evento, para garantir que nada seja esquecido.

**Critérios de Aceite:**
- Permitir criar, editar, excluir itens de checklist vinculados ao evento.  
- Marcar itens como concluídos/pendentes.  




---
## Epic 11: Administração de Usuários & Permissões (Presidência / Vice-Presidência)

**Descrição:**  
Como presidente ou vice-presidente, quero gerenciar contas, papéis e permissões de todos os usuários da plataforma, garantindo que o acesso seja seguro, atualizado e compatível com as responsabilidades de cada membro e cliente.

### User Stories:

**US 11.1 – Listar Usuários**  
- Como presidente ou vice-presidente, quero visualizar uma lista de todos os usuários membros.

**Critérios de Aceite:**
- Tabela com todos os dados essenciais de todos os membros da empresa.


---

**US 11.2 – Alterar Papel e Permissões**  
- Como presidente ou vice-presidente, quero alterar o papel (presidência, diretor, membro, cliente) de um usuário para ajustar seus níveis de acesso.

**Critérios de Aceite:**
- Modal de edição com seleção de novo papel.  
- Confirmação antes de aplicar mudanças.  
- Log de alteração salvo com usuário, data e papel antigo/novo.  
- Mudança refletida imediatamente nas permissões de menu e funcionalidades.

---

**US 11.3 – Ativar / Desativar Usuário**  
- Como presidente ou vice-presidente, quero ativar ou desativar temporariamente uma conta para controlar o acesso sem perder histórico de dados.

**Critérios de Aceite:**
- Botão de alternância Ativar/Desativar na lista de usuários.  
- Confirmação via modal com lembrete de que o usuário não poderá acessar enquanto estiver inativo.  
- Status atualizado em tempo real e exibido na coluna “Status”.  
- Ação registrada em log administrativo.

---

**US 11.4 – Aprovar ou Rejeitar Novo Membro**  
- Como presidente ou vice-presidente, quero aprovar ou rejeitar solicitações de novos membros enviadas pelo Diretor de Gestão de Pessoas.

**Critérios de Aceite:**
- Seção “Solicitações Pendentes” com detalhes do candidato.  
- Botões “Aprovar” e “Rejeitar” com campo de justificativa (obrigatório ao rejeitar).  
- Após aprovação, conta é criada e aparece na lista geral de usuários.


---
## ⚙️ Requisitos Funcionais

### Autenticação & Permissões (Presidência / Vice-Presidência)
- **RF01** – Cadastro de usuários com papéis: presidência, vice-presidência, diretor, membro e cliente.  
  _Rel. US 11.1_
- **RF02** – Login autenticado, verificando papel e permissões.  
  _Rel. US 9.1, 11.1_
- **RF03** – Login de clientes via token de acesso exclusivo por projeto.  
  _Rel. US 1.5, 9.1_
- **RF04** – Tela de **lista de usuários** (filtros, paginação, busca).  
  _Rel. US 11.1_
- **RF05** – Alterar papéis/permissões em tempo real, com log de auditoria.  
  _Rel. US 11.2_
- **RF06** – Ativar / desativar contas, mantendo histórico.  
  _Rel. US 11.3_
- **RF07** – Aprovar ou rejeitar solicitações de novos membros (justificativa + notificação).  
  _Rel. US 11.4_
- **RF08** – Resetar senha via link seguro (e-mail, validade 60 min).  
  _Rel. US 11.5_
- **RF09** – Disponibilizar **logs administrativos** (alterações de papel, ativações, exclusões).  
  _Rel. US 11.2, 11.3_

### Gestão de Projetos (Diretoria de Projetos)
- **RF10** – Criar projeto (nome, tipo, data de entrega obrigatórios).  
  _Rel. US 1.1_
- **RF11** – Editar projetos ativos, salvando histórico de modificações.  
  _Rel. US 1.2_
- **RF12** – Excluir projetos com confirmação; restrito a usuários autorizados.  
  _Rel. US 1.3_
- **RF13** – Exibir **dashboard de projetos** (ativos, fora do prazo, próximos da entrega, por tipo).  
  _Rel. US 1.4_
- **RF14** – Calcular **barra de progresso automática** (data atual × data de entrega).  
  _Rel. US 1.6_
- **RF15** – Visualização restrita do projeto ao cliente mediante token.  
  _Rel. US 1.5_

### Gestão de Parcerias & Eventos (Diretoria de RI)
- **RF16** – CRUD de parcerias (nome, tipo, data início, status).  
  _Rel. US 2.1–2.3_
- **RF17** – Exibir **histórico de ativações** por parceiro (data, descrição).  
  _Rel. US 2.4_
- **RF18** – CRUD de **eventos** (nome, tipo, data, horário, local, prioridade, parceiro).  
  _Rel. US 10.1–10.3_
- **RF19** – Exibir **calendário/quadro** de eventos com filtros, cores por prioridade, contador “Eventos Planejados”.  
  _Rel. US 10.4_
- **RF20** – Gestão de **checklist de infraestrutura** por evento (itens, status, progresso %).  
  _Rel. US 10.5_

### Gestão de Pessoas (Diretoria de Gestão de Pessoas)
- **RF21** – Listar membros com informações essenciais (foto, nome, cargo).  
  _Rel. US 3.1_
- **RF22** – Exibir **perfil completo** de cada membro (objetivos, habilidades, forças).  
  _Rel. US 3.2_
- **RF23** – Fluxo de **solicitar novo membro** (formulário + aprovação).  
  _Rel. US 3.3_

### Métricas, Relatórios & Financeiro (Diretoria Admin-Fin)
- **RF24** – Exibir **métricas de performance financeira** ao diretor Admin-Fin.  
  _Rel. US 4.1_
- **RF25** – Painel de **fluxo de caixa mensal** (entradas, saídas, saldo) + projeção anual.  
  _Rel. Métricas de Finanças – comp. US 4.1_

### Gestão Comercial (Diretoria de Vendas)
- **RF26** – Cadastro de leads/propostas (cliente, serviço, valor, status).  
  _Rel. US 5.1_
- **RF27** – Atualização do **status de vendas** com histórico.  
  _Rel. US 5.2_
- **RF28** – Dashboard de vendas (gráficos de conversão, pipeline).  
  _Rel. US 5.3_
- **RF29** – Histórico de contratos/negociações por cliente.  
  _Rel. US 5.4_
- **RF30** – Exclusão de contrato com confirmação e log.  
  _Rel. US 5.5_

### Gestão Estratégica (Presidência / Vice-Presidência)
- **RF31** – Acesso a **relatórios estratégicos** segmentados por área.  
  _Rel. US 6.2, 7.1_

### Acesso Externo – Clientes
- **RF32** – Cliente visualiza **timeline** do projeto contratado (entregas, marcos).  
  _Rel. US 9.2, 9.3_
- **RF33** – Restrição de visualização apenas aos dados do projeto associado ao token.  
  _Rel. US 1.5, 9.1_

---

## 📌 Observações Finais

- **Dependências:** Integração com serviço de autenticação segura para login de clientes (ex: Auth0, Firebase Authentication).
- **Riscos Conhecidos:** Possível resistência de membros em adotar a plataforma no início; mitigação prevista via treinamento interno.
- **Considerações Legais:** Proteção de dados dos clientes conforme a LGPD (Lei Geral de Proteção de Dados).
- **Prazos:** Algumas funcionalidades, como dashboards de vendas e métricas de áreas, podem ser entregues em fases posteriores.

---




