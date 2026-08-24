# Iamylla Prata's — site

Site estático (sem custo de hospedagem), feito para rodar no **GitHub Pages**.

## Estrutura
- `index.html` — o site inteiro (catálogo, sacola, checkout via WhatsApp, painel da loja)
- `data.json` — suas joias e configurações (nome da loja, WhatsApp, senha do painel)
- `logo.png` — a logo da marca

## Como publicar pela primeira vez
1. Crie um repositório novo no GitHub (pode ser público).
2. Suba estes 3 arquivos (`index.html`, `data.json`, `logo.png`) para a raiz do repositório.
3. Vá em **Settings → Pages**, em "Source" escolha a branch `main` e a pasta `/ (root)`, salve.
4. Em 1-2 minutos seu site estará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Como atualizar as joias depois
1. Abra o site publicado e entre em **Área da loja** (senha inicial: `prata123` — troque isso em Configurações assim que entrar).
2. Cadastre, edite ou remova as joias e ajuste as configurações normalmente.
3. Vá na aba **Publicar no ar** e clique em **Baixar data.json atualizado**.
4. No GitHub, abra o arquivo `data.json` do repositório, clique no ícone de lápis (editar) ou use "Add file → Upload files" para substituí-lo pelo arquivo baixado.
5. Clique em **Commit changes**. O site atualiza sozinho para todo mundo em 1-2 minutos.

## Importante
- Antes de divulgar o site, configure o número de WhatsApp em Configurações (só números, com DDI 55 + DDD, ex: `5518999999999`).
- A senha do painel é uma proteção simples do lado do navegador — não é segurança de nível bancário, mas é suficiente para impedir acesso casual.
- Toda alteração feita no painel fica só no seu navegador até você baixar e subir o `data.json` — assim o site continua gratuito, sem precisar de servidor.
