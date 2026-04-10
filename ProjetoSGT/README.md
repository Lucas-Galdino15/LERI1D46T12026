 # Sistemas de Gestão de Tarefas

 ## 1. Introdução 

 ### 1.1 Propósito do Projeto

 Este documento especifica os requisitos funcionais e não-funcionais para o Sistema de Gestão de Tarefas (SGT), seguindo o padrão IEEE 29148:2018.

### 1.2 Escopo

O SGT permitirá que usuários criem, organizem e acompanhem tarefas pessoais e profissionais com sistema de prioridadee prazos.

### 1.3 Definição e Acrônimos

- **SGT**: Sistema de Gestão de Tarefas 
- **RF**: Requisito Funcional
- **RNF**: Requisito Não Funcional 
- **Sprint**: Período de 2 Semanas de Desenvolvimento 

### 1.4 Referências 

- IEEE 28148:2018 - Systems and software engineering
- CMMI for Development. Version 2.0.

## 2. Descrição Geral

### 2.1 Perspectiva do Produto 

O SGT será uma aplicação responsiva com sincronização em nuvens.

### 2.2 Funções Principais

- Criação e edição de tarefass
- Organização pro projetos e tags
- Sistema  de notificação 
- Relatórios de Produtividade

## 3. Requisitos Específicos 

### 3.1 Requisitos Funcionais

#### RF-001: Criação de Tarefas

**Descrinção**: Osisitema deve permitir que usuários criemm tarefas com título, descrinção, data de vencimento e prioridade.
**Prioridade**: Alta
**Versão**: 1.0
**Data**: 2026-03-27
**Rastreabilidade**: Derivando da necessidade do stakeholders NS-001

**Critérios de Aceitação**:

- [ ] Tarefas podem ser atribuidas um ou nehum projeto
- [ ] Visualização filtrada por projeto
- [ ] Usuário pode criar, renomear e excluuir projetos

#### RF-002: Organização por Projetos

**Descrição**: O sistema deve permitir agrupar tarefas em projetos personalizados
**Prioridade**: Média.
**Versão**: 1.0
**Data**: 2026-03-27
**Rastreabilidade**: Derivado da necessidade do stakeholder NS-002

**Critérios de Aceitação**:

- [ ] Usuário pode criar , renomear e xcluir projetos 
- [ ] Tarefas podem ser atribuidasa um ou nenhum projeto
- [ ] Visualização filtrada por projeto

**Dependências**: RF-001

---

#### RF-003: Alterar a Tarefa Para Concluído

**Descrição**: O sistema deve permitir alterar a tarefa para concluída
**Prioridade**: Média.
**Versão**: 1.0
**Data**: 2026-04-10
**Rastreabilidade**: Derivado da necessidade do stakeholder NS-001

**Critérios de Aceitação**:

- [ ] Usuário pode alterar a tarefa para concluída
- [ ] tarefas podem retornar para não concluídas
- [ ] Visualização filtrada por status (concluídas e não-concluídas)

**Dependências**: RF-001

### 3.2 Requistos Não-Funcionais

#### RNF-001: Desempenho

**Descrição**: O Sistema deve carregar a lista de tarefas em menos de 1 segundo para até 100 tarefas.
**Categoria: Desempenho 
**PRioridade**: Alta.
**Versão**:1.0
**Métrica**:Tempo de Reposta <1s para 95% das requisiçoes.

---
#### RNF-002: Segurança


**Descrição**: O Sistema deve implementar autenticação OAuth 2.0 e criptografia TLS 1.3.
**Categoria**: Segurança.
**Prioridade**: Crítica.
**Conformidade**: LGPD, ECADigital

---

## 4. Controle de Versões

### 4.1 Histórico de Alterações

| Versão | Data | Autor | Modificação |
|--------|------|--------|------------|
| 1.0    |2026-03-27| Equipe de Análise | Versão inicial do documento |
| 1.1 | 2026-04-10 | Equipe de Desenvolvimento | Inclusão da RF-003| 


### 4.2 Rastrabilidade

Infográfico de Rastreabilidade do Requisito

```mermaid

graph LR

        NS001["NS-001: Necessidade SatakeHolder"] --> RF001["RF-001: Criação Tarefas"]  
        RF001 --> TC001["TC-001: Teste de Criação"]


``` 

## 5. Aprovação

Matriz de Aprovação

| Alteração | Data | Autor | Aprovador |
| -   | - | - | - |
| 1.0 | 2026-03-27 | Equipe de Análise | Stakeholder |
| 1.1 | 2026-04-10 | Equipe de Desenvolvimento |
Equipe de Análise |