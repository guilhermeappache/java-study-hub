# Java Study Hub

Biblioteca estática de estudos Java: um `index.html` com CSS/JS embutidos, `conteudo.json` e mapas mentais na pasta `imagens/`.

## Publicar no GitHub Pages

1. Envie os arquivos para a raiz da branch `main` do repositório.
2. Em **Settings → Pages**, selecione **Deploy from a branch**, branch `main` e pasta `/ (root)`.
3. Aguarde a publicação e abra `https://guilhermeappache.github.io/java-study-hub/`.

## Executar localmente

Use um servidor HTTP local (por exemplo, `python -m http.server 8000`) e abra `http://localhost:8000`. Abrir o HTML diretamente com `file://` pode bloquear o `fetch` do JSON.

## Atualizar conteúdo

Edite `conteudo.json`, mantendo IDs únicos por assunto. Para adicionar um mapa mental, salve a imagem na pasta `imagens/` e atualize o campo `mapaMental` do assunto. Os caminhos atuais são espaços reservados: até que as imagens sejam adicionadas, a página mostrará um aviso discreto.

Não há backend, login, rastreamento ou dependências externas.