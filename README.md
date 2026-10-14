# ESTOU BEM — protótipo com autenticação Supabase

## Publicação
1. Crie um projeto no Supabase.
2. Em Project Settings / API, copie a Project URL e a chave pública anon (ou publishable key compatível). Nunca use service_role ou secret key no navegador.
3. Edite `config.js` com os valores públicos do seu projeto.
4. Em Authentication / URL Configuration, defina Site URL com a URL final da Vercel e adicione a URL de redirecionamento autorizada.
5. Habilite Email/Password em Authentication / Providers e configure entrega de e-mails SMTP para produção.
6. Envie `index.html` e `config.js` para a raiz do repositório GitHub e importe na Vercel com Framework Other.

## Funcionalidade
Login real, cadastro por e-mail, confirmação de e-mail (conforme configuração do Supabase), link para redefinir senha e logout.

## Limitações críticas
Os registros do botão ainda são armazenados somente no navegador (localStorage), **não estão vinculados ao usuário no servidor**. O envio pelo WhatsApp é manual e não existem alertas de ausência nem monitoramento remoto. Não usar como sistema de emergência ou acompanhamento de saúde. Para produção, implementar banco com RLS, consentimento LGPD, vínculo seguro entre familiar e idoso, notificações e auditoria.
