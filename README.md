# OdontoTech
# Ecossistema de Atendimento Inteligente para Clínica Odontológica

Projeto de estágio que implementa um ecossistema de agentes autônomos
para atendimento, agendamento, cobrança e recuperação de clientes
via WhatsApp.

## Visão Geral

O sistema não é um chatbot simples.
Ele funciona como um funcionário digital completo,
orquestrando múltiplos workflows independentes.

## Arquitetura

- n8n como orquestrador de agentes
- PostgreSQL como memória de longo prazo e fila de controle
- OpenAI para interpretação de intenções
- Google Calendar para gestão de agenda
- Asaas para cobranças e Pix
- Chatwoot como central de atendimento

## Organização dos Workflows

- 00 - Configurações gerais
- 01 - Secretária Inteligente (orquestrador)
- 03 - Busca inteligente de janelas de agendamento
- 04 - Criação e atualização de eventos no Google Calendar
- 06 - Integração financeira com Asaas
- 07 - Humanização e controle de envio de mensagens
- 08 - Assistente interno da clínica
- 09 - Cancelamento e alertas
- 11 - Agente ativo de lembretes de consulta
- 12 - Agente de recuperação de leads

## Controle de Mensagens Encavaladas

O PostgreSQL é utilizado para:
- Controlar estado por usuário
- Garantir ordem das mensagens
- Evitar múltiplas execuções simultâneas
- Permitir retomada de contexto

## Resultados

- Atendimento 24/7
- Redução de faltas (no-show)
- Recuperação automática de clientes
- Menor custo operacional

## Segurança

Credenciais e dados sensíveis não fazem parte do repositório.
Em produção, são armazenados no cofre de credenciais do n8n.
