# OdontoTech

## Ecossistema de Atendimento Inteligente para Clínica Odontológica

Projeto de estágio que implementa um ecossistema de agentes autônomos para atendimento, agendamento, cobrança e recuperação de clientes via WhatsApp, utilizando automação, inteligência artificial e integração com serviços externos.

---

## 🎯 Objetivo do Projeto

Criar um sistema que vá além de um chatbot tradicional, funcionando como um **funcionário digital completo**, capaz de executar tarefas reais da clínica de forma autônoma, organizada e escalável.

---

## 🧠 Visão Geral da Solução

O sistema é baseado em uma arquitetura modular, onde cada responsabilidade é isolada em workflows independentes, orquestrados por um agente central inteligente.

Principais características:

- Atendimento automático 24/7
- Controle de concorrência de mensagens no WhatsApp
- Agendamento inteligente de consultas
- Geração e acompanhamento de cobranças
- Lembretes automáticos de consultas
- Recuperação ativa de leads inativos
- Escalonamento para atendimento humano quando necessário

---

## 🏗️ Arquitetura

- **n8n**: Orquestração dos fluxos e agentes
- **PostgreSQL**: Memória de longo prazo, fila de mensagens e controle de estado
- **OpenAI**: Interpretação de intenções e tomada de decisão
- **WhatsApp**: Canal principal de comunicação
- **Chatwoot**: Centralização do atendimento humano
- **Google Calendar**: Gestão de agenda
- **Asaas**: Cobrança e pagamentos
- **Whisper / ElevenLabs**: Áudio e voz (quando aplicável)

---

## 📸 Imagens do Projeto

As imagens do sistema (prints do Chatwoot, WhatsApp, fluxos do n8n e estrutura do banco de dados) estão disponíveis no Google Drive:

👉 https://drive.google.com/drive/folders/15zMaPbFSfB1Z98JsGNxbf1j6FC0x-8f7?usp=sharing

---

## 🎥 Vídeo de Demonstração

O vídeo abaixo demonstra o funcionamento completo do sistema em um cenário real, incluindo atendimento, agendamento, pagamento, cancelamento e escalonamento para humano:

👉 https://youtu.be/bc-bUDF7NU4

---

## 📂 Estrutura dos Workflows

Os arquivos `.json` presentes neste repositório representam os workflows do n8n, organizados por responsabilidade, como:

- Configuração inicial do ambiente
- Agente central (Secretária Inteligente)
- Agendamento
- Financeiro
- Lembretes automáticos
- Recuperação de clientes
- Integração com atendimento humano

---

## ⚠️ Observações Importantes

- Arquivos de mídia (imagens e vídeos) não estão versionados neste repositório para manter o projeto leve.
- Credenciais, tokens e dados sensíveis foram removidos dos arquivos `.json`.
- O projeto foi desenvolvido com foco em ambiente real de produção.

---

## 🧑‍💻 Autor

Projeto desenvolvido como trabalho de conclusão de curso / estágio supervisionado.
Gabriel Silva Carvalho e Vitor (DS3 2025)

---

## 📌 Conclusão

Este projeto resolve problemas reais enfrentados por clínicas odontológicas, utilizando automação e IA de forma prática, estruturada e aplicável ao mercado.
