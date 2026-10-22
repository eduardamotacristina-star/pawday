# PawDay 🐾

Aplicativo web progressivo (PWA) simples para organizar cuidados com pets, com visual rosa pastel.

## O que está incluído
- Cadastro, edição e exclusão de pets.
- Rotina diária com tarefas e marcação de conclusão.
- Registros de alimentação.
- Histórico de saúde e próximas datas.
- Lista de lembretes dentro do app.
- Exportação e importação de backup JSON.
- Manifesto PWA, service worker e ícones.

## Publicar grátis com GitHub Pages
1. Entre em https://github.com/ e crie uma conta, se precisar.
2. Clique em **+** → **New repository**.
3. Dê o nome `pawday` e escolha **Public**.
4. Faça upload de **todos os arquivos e pastas** deste ZIP para a raiz do repositório. É importante que `index.html`, `manifest.json` e `service-worker.js` fiquem na raiz, e que a pasta `icons` seja enviada inteira.
5. Na página do repositório, abra **Settings** → **Pages**.
6. Em **Build and deployment**, selecione **Deploy from a branch**. Em Branch, escolha `main` e a pasta `/(root)`, depois clique em **Save**.
7. Aguarde alguns minutos. O endereço geralmente será `https://SEU-USUARIO.github.io/pawday/`. Substitua `SEU-USUARIO` pelo seu nome de usuário no GitHub.
8. Abra o endereço e teste o cadastro de um pet e uma tarefa. Se não carregar, aguarde mais um pouco e confira se os arquivos estão na raiz e se Pages está ativo.

## Como enviar os arquivos pelo site do GitHub
- Abra seu repositório `pawday`.
- Clique em **Add file** → **Upload files**.
- Extraia o ZIP no computador antes de enviar.
- Arraste os arquivos e a pasta `icons` para a área de upload.
- Role até **Commit changes** e confirme.

## Instalar no Android
1. Abra o endereço HTTPS do site no Google Chrome do Android.
2. Toque no menu `⋮`.
3. Escolha **Instalar app** ou **Adicionar à tela inicial** (o texto pode variar).
4. Confirme. O ícone PawDay aparecerá na tela inicial.

## Dados e privacidade
- Os registros são guardados localmente no navegador do dispositivo por `localStorage`; não são enviados a um servidor por este projeto.
- Limpar os dados do navegador, usar outro navegador ou trocar de dispositivo pode fazer os registros deixarem de aparecer. Use **Dados → Exportar backup** e guarde o arquivo JSON em local seguro.
- O botão de importar substitui os dados atuais após confirmação.
- A lista de lembretes é exibida dentro do app; esta versão não envia notificações push ou alertas em segundo plano.
- Este app é um organizador e não substitui a orientação veterinária.

## Antes de publicar na Play Store
Esta versão é um ponto de partida e precisa ser testada em dispositivos reais. Publicar na Google Play exige cumprir os requisitos atuais da loja, criar a listagem, fornecer política de privacidade adequada e passar pela análise do Google. Não há publicação automática incluída neste ZIP.
