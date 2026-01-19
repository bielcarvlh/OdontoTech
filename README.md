# OdontoTech
Sistema de atendimento inteligente para clínica odontológica usando n8n, IA e PostgreSQL.

# Ecossistema de Atendimento Inteligente para Clínica Odontológica

Este projeto implementa um ecossistema de agentes autônomos para atendimento,
agendamento, cobrança e recuperação de clientes em uma clínica odontológica.

## 🎯 Objetivo
Automatizar o atendimento via WhatsApp, reduzir faltas, recuperar leads e
centralizar a operação da clínica com uso de IA e automação.

## 🧠 Arquitetura
- n8n como orquestrador de workflows
- PostgreSQL como memória de longo prazo e controle de estado
- OpenAI para interpretação de intenções
- Google Calendar para agenda
- Asaas para pagamentos
- Chatwoot como central de atendimento

## 🧩 Workflows
- 01 - Secretária Inteligente (orquestrador)
- 03 - Agendamento inteligente
- 06 - Financeiro (Pix e cobranças)
- 11 - Lembretes automáticos
- 13 - Recuperação de leads

## 🗃️ Banco de Dados
O PostgreSQL é utilizado para:
- Persistência de contexto
- Controle de fila por usuário
- Prevenção de mensagens encavaladas
- Recuperação automática de clientes

## 🚀 Resultados
- Atendimento 24/7
- Redução de no-show
- Recuperação de vendas
- Menor custo operacional

## ⚠️ Observações
Credenciais e dados sensíveis foram removidos por segurança.
