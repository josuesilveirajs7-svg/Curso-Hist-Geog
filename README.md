# Brasil a Fundo — Curso de História e Geografia

Curso gratuito e aprofundado de **História e Geografia do Brasil**, com o essencial de **História Geral** e **Geografia Geral**. Tudo em um único arquivo `index.html` (HTML + CSS + JavaScript), sem dependências.

## Trilhas (154 aulas, todas completas)
1. 📜 História do Brasil — 66 aulas
2. 🗺️ Geografia do Brasil — 33 aulas
3. 🌍 História Geral — o essencial — 37 aulas (inclui África, Ásia e Américas antes de 1500, Pérsia, Han e Gupta, Império Otomano, unificação alemã, Restauração Meiji, tráfico atlântico, EUA no séc. XIX, ordem de 1945, América Latina na Guerra Fria, Oriente Médio e história do comércio mundial)
4. 🌐 Geografia Geral — o essencial — 18 aulas (inclui módulo de geopolítica e relações internacionais)

Cada aula traz: objetivo, por que importa, explicação aprofundada, dados e números-chave com fonte, linha do tempo, conceitos e personagens, mitos e confusões comuns, conexão Nordeste/Ceará, resumo e links gratuitos para aprofundar.

## Recursos
- **App instalável (PWA)**: instala no celular e no computador, com ícone próprio, e funciona offline depois da primeira visita
- Tela de abertura animada (mapa do Brasil desenhado ao vivo, linha do tempo em movimento) com botão "Continuar de onde parei"
- Tela inicial para escolher a trilha
- Sumário lateral clicável (Trilha › Período › Módulo › Aula), com busca e destaque da aula atual
- Botões "Aula anterior" / "Próxima aula"
- Marcar aula como concluída e barra de progresso (salvo no navegador)
- Modo claro/escuro
- Funciona no celular (menu recolhível)

## Publicar no GitHub Pages (5 minutos)
1. Entre em [github.com](https://github.com) e clique em **New repository**.
2. Dê um nome (ex.: `brasil-a-fundo`), deixe **Public** e clique em **Create repository**.
3. Clique em **uploading an existing file** e arraste **todo o conteúdo desta pasta**: `index.html`, `manifest.webmanifest`, `sw.js`, os 6 ícones `.png`, `README.md` e `PROMPT.md`. Clique em **Commit changes**.
   - Os arquivos `manifest.webmanifest`, `sw.js` e os 6 ícones `.png` são o que torna o curso **instalável** — não deixe de enviá-los.
   - O `.nojekyll` começa com ponto, fica oculto no computador e é opcional.
4. Vá em **Settings › Pages**. Em **Source**, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e clique em **Save**.
5. Em 1–2 minutos o site estará em `https://SEU-USUARIO.github.io/brasil-a-fundo/`.

## Como instalar o app
- **Android (Chrome)**: abra o site, toque em **⬇ Instalar app** (ou no menu ⋮ › **Instalar app**).
- **Computador (Chrome/Edge)**: clique no ícone de instalar na barra de endereço ou no botão **⬇** do topo.
- **iPhone (Safari)**: toque em **Compartilhar** › **Adicionar à Tela de Início**.

Ao publicar uma atualização, mude o nome do cache em `sw.js` (ex.: `brasil-a-fundo-v2`) para os aparelhos baixarem a versão nova.

## Como adicionar novas aulas
No `index.html`, procure a linha:

```
// >>> COLE NOVAS AULAS ACIMA DESTA LINHA <<<
```

Cole o bloco da nova aula **logo acima** dela. O id da aula (ex.: `'hb-07'`) precisa ser o mesmo que aparece no `PLANO`; assim ela deixa de aparecer como "em breve" automaticamente. Depois, no GitHub, abra o `index.html`, clique no lápis (Edit), cole, e faça **Commit changes**.

## Prompt usado
O arquivo `PROMPT.md` tem o prompt completo para continuar gerando as aulas com o mesmo padrão.

---
Desenvolvido por **Josué Silveira**.
