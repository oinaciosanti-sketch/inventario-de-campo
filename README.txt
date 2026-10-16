INVENTÁRIO DE CAMPO — WEB APP v1

PUBLICAÇÃO (HTTPS)
1. Envie o conteúdo DESTA PASTA para um serviço de hospedagem de site estático com HTTPS, como Vercel ou Netlify.
2. Acesse o endereço publicado no Safari do iPhone.
3. Compartilhar > Adicionar à Tela de Início.
4. Abra o app instalado ao menos uma vez com internet antes da visita. Depois teste em modo avião.

FUNCIONALIDADES
- Cadastros com foto(s), item, quantidade, destino livre e observações.
- Rascunhos salvos localmente via IndexedDB, inclusive sem internet depois do primeiro carregamento.
- CSV para Excel e relatório imprimível/salvável em PDF com fotos.
- Backup completo em JSON com fotos; faça backups periódicos e ao final.
- Botão Preparar e-mail abre aplicativo de e-mail com resumo pré-preenchido; não envia sozinho nem anexa fotos.

CUIDADOS
- Sem hospedagem HTTPS, a instalação offline como PWA pode não funcionar. Abrir o index.html local não instala corretamente o service worker.
- Safari pode apagar dados em certas condições (ex.: armazenamento sob pressão). Backup JSON é indispensável.
- O app não sincroniza entre aparelhos.
- Envio AUTOMÁTICO de relatório com anexos requer backend e serviço de e-mail com credenciais protegidas.
- A data, unidade, destinatário e responsável ficam no navegador.
