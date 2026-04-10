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

Inserir aqui o Requisito Funcional

## 4. Controle de Versão @

### 4.1 Histórico de Alterações @

## 5. Aprovação @