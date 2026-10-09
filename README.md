# Publicar a apresentação e o retorno Shopee

Estes arquivos ainda são locais. Publique somente o conteúdo desta pasta, nunca a pasta do aplicativo, banco, configurações ou chaves.

1. Na conta GitHub **LukGames**, crie um repositório público chamado **3dlabz-studio**.
2. Envie `index.html`, `callback.html`, `studio-demo.png` e `.nojekyll` para a raiz do repositório. O README pode ser enviado também.
3. Em **Settings → Pages**, selecione **Deploy from a branch**, branch **main** e pasta **/(root)**. Salve e aguarde a publicação.
4. Abra o endereço que o GitHub informar e confirme que a página carregou. Use HTTPS.

Endereços previstos, válidos somente depois da publicação:

- Apresentação / Product URL: `https://lukgames.github.io/3dlabz-studio/`
- Test/Live Redirect URL Domain no Console Shopee: `https://lukgames.github.io`
- URL de retorno nas Configurações da V9: `https://lukgames.github.io/3dlabz-studio/callback.html`

O retorno será manual: o vendedor autoriza na Shopee, clica Copiar retorno nesta página e cola no diálogo da V9. A V9 valida domínio/caminho, state, validade, uso único e loja antes de trocar o código com a API. A página não troca tokens e não contém Partner Key. Não usa analytics, recursos externos, cookies ou armazenamento local. O código temporário é recebido pela hospedagem HTTPS; não envie URLs de retorno em chats, commits ou logs.

GitHub Pages fornece hospedagem estática gratuita para repositórios públicos. A aprovação Go Live e a aceitação final dos domínios dependem da Shopee. O programa é desktop: não invente usuário ou senha de uma aplicação web no Product Brief; explique que o teste é feito no Windows e inclua a captura demonstrativa.

Depois da aprovação Live, preencha Partner ID/Key de produção na V9, selecione `live`, salve e autorize sua loja brasileira. Os tokens anteriores são limpos na troca de contexto; o cache continua separado por loja/ambiente.
