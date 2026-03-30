# Portfólio de Automações e Integrações ERP

Repositório destinado à demonstração de fluxos de automação utilizando **n8n**, **JS** e **SQL Server**, focados em otimização de processos e integridade de dados no ecossistema Protheus.

---

1. Implementação de RAG (Retrieval-Augmented Generation)
Este projeto utiliza Inteligência Artificial para consultar documentos e dados do ERP diretamente pelo ClickUp. O fluxo intercepta perguntas em linguagem natural, busca o contexto em uma base de vetores/SQL e devolve a resposta mastigada para o usuário.

**Tecnologias:** n8n, OpenAI API, ClickUp Webhooks.


<img width="1533" height="686" alt="FLUXO_RAG" src="https://github.com/user-attachments/assets/91a67b98-7003-487f-bafc-fa08335f2b2a" />

---

2. Motor de Alertas: Monitoramento de Dados Críticos
Automação desenvolvida para garantir a qualidade do cadastro no Protheus. O fluxo realiza queries programadas no banco de dados para identificar campos obrigatórios vazios ou inconsistentes (ex: Matrícula ou CPF em branco) e dispara alertas imediatos por e-mail para os responsáveis.

**Tecnologias:** n8n, MS SQL Server (T-SQL), Nodes de E-mail (SMTP).

<img width="1397" height="481" alt="Disparo_de_alerta_por_campo_nao_preenchido" src="https://github.com/user-attachments/assets/01e8677a-bcf3-43a0-ae52-808ffe9a8c06" />


---

3. Atualização de cep na BA1 via API ViaCEP
Integração desenvolvida para suprir a necessidade de varredura e atualização de bairros obsoletos ou incompletos no sistema. O fluxo identifica registros com inconsistências e consome a API ViaCEP para garantir a padronização dos dados de endereço.

**Tecnologias:** n8n, API REST (ViaCEP), SQL Server Update.

<img width="1503" height="360" alt="Atualiza_Bairro" src="https://github.com/user-attachments/assets/3209f78b-a701-4c5e-bd0d-c2780b822914" />


---

4. Priorização Automática de Equipes
Fluxo lógico para distribuição de tarefas e priorização de chamados baseado em campos de status. Garante que as demandas críticas cheguem aos squads corretos sem necessidade de triagem manual.

**Tecnologias:** n8n, Lógica de Condicionais (IF/Switch).

<img width="1223" height="683" alt="Categorização_equipe" src="https://github.com/user-attachments/assets/f89e15c6-c5de-4e2f-9efc-1954165d2c1d" />
<img width="1521" height="603" alt="Categorização_prioridade" src="https://github.com/user-attachments/assets/656c925e-8586-4cbe-8012-330a00fea671" />


---
