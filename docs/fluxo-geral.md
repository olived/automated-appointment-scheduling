## Fluxo da POC

1. Usuário inicia conversa no chatbot (Typebot)
2. Coleta de dados:
   - Nome
   - Telefone
   - Motivo
   - Data desejada
   - Hora desejada
3. Typebot envia dados via Webhook
4. n8n:
   - Recebe webhook
   - Registra dados (Google Sheets)
   - Cria evento no Google Calendar
5. Consulta é automaticamente agendada
