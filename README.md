# ESSENZIA — Presença Digital Essencial

Projeto independente da Gabriella.Net para briefing de pequenos negócios.

## Objetivo
Formulário responsivo com identidade visual premium, sete etapas e campos de briefing opcionais. As respostas servem à produção de um site institucional de uma página. O cliente poderá indicar que precisa de auxílio com logomarca, fotografias e registro de domínio.

## Configuração
Site estático em `index.html`, `styles.css` e `app.js`. Publique os arquivos em hospedagem HTTPS. Para processar respostas e anexos com segurança e enviá-los a **contato@gabriella.net.br**, é necessário integrar um backend com envio SMTP/API transacional e armazenamento privado de arquivos. Não use `mailto:` para anexos nem inclua segredos no frontend.

**Atenção:** a versão inicial do formulário gera uma prévia estruturada para o cliente copiar e enviar à agência, sem alegar envio automático. Não há coleta de dados em servidor nesta versão.

Antes de publicar: configurar um endpoint seguro com validação, limite de arquivos, proteção antispam, política de privacidade e teste de entrega; revisar os textos contratuais e de LGPD.

Marca: ESSENZIA, uma iniciativa Gabriella.Net.
