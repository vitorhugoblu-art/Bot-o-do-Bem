# ESTOU BEM — protótipo publicável

## Publicar
Faça upload da pasta no GitHub e importe o repositório na Vercel como projeto estático (Framework Preset: Other). Também pode hospedar o index.html em qualquer hospedagem estática.

## O que funciona
- Layout responsivo acessível com botão grande.
- Registro de até três períodos por dia no armazenamento local do navegador.
- Nome e telefone salvos no dispositivo.
- Abertura do WhatsApp com mensagem preenchida, exigindo que o usuário confirme o envio.

## Limitações importantes
- Não envia mensagens automaticamente.
- Não avisa familiares em caso de ausência de confirmação.
- Não possui autenticação, banco de dados remoto nem sincronização entre dispositivos.
- O registro pode ser perdido se os dados do navegador forem apagados.
- Não deve ser utilizado como serviço de emergência ou monitoramento de saúde.

## Próxima versão para produção
Backend com autenticação, consentimento e LGPD, banco de dados, agendamento de lembretes e alertas, provedor de mensagens (WhatsApp Business API ou SMS), logs de entrega, configuração de horários e fuso horário, testes e monitoramento.
