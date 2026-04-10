# Sistema de Gerenciamento de Reservas de Hotel

## 1. Introdução @
Esta seção apresenta uma visão geral do documento e do projeto, estabelecendo o contexto para os requisitos que virão a seguir.

### 1.1 Propósito @
O propósito deste documento é formalizar as regras de negócio para o módulo de agendamento e reservas do Sistema de Gerenciamento de Hotéis. O objetivo é garantir que a equipe de desenvolvimento e os stakeholders estejam alinhados sobre como o sistema deve processar diferentes perfis de clientes e prazos de reserva, assegurando a integridade dos dados e a rentabilidade do negócio.

### 1.2 Escopo 

### 1.3 Acrônimos - Definição 

### 1.4 Referências 

## 2. Descrição Geral

## 3. Requisitos Específicos 

### 3.1 Requisito Funcional @ 
ID: RF-010

Descrição: O sistema deve validar os prazos de antecedência das reservas e aplicar taxas dinâmicas conforme o perfil do cliente e a urgência do pedido.

Regras de Negócio:

Reserva Padrão: O sistema deve permitir reservas com antecedência mínima de 24 horas e máxima de 6 meses.

Reserva VIP: Clientes com status VIP autenticado podem realizar reservas com até 1 ano (12 meses) de antecedência.

Reserva de Última Hora: Reservas solicitadas com menos de 2 horas de antecedência são permitidas, desde que o sistema aplique automaticamente uma taxa adicional de 15% sobre o valor total da reserva.


## 4. Controle de Versão @

### 4.1 Histórico de Alterações @
| Versão | Data | Autor | Alteração | Motivo |
| :--- | :--- | :--- | :--- | :--- |
| 1.0.0 | 15/01/2026 | Analista | Criação do RF-010 | Definição inicial. |
| 2.0.0 | 10/02/2026 | Analista | Adição de Regra VIP | Solicitação comercial. |
| 3.0.0 | 05/03/2026 | Analista | Inclusão de Taxa de Urgência | Política de ocupação. |

## 5. Aprovação @
Este documento foi revisado e as regras de negócio do RF-010 foram validadas pelos responsáveis.

Gerente de Produto (PO): Aprovado em 05/03/2026.

Líder Técnico: Aprovado em 05/03/2026.

Gestor Financeiro: Aprovado em 05/03/2026.