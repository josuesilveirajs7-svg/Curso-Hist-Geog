# Brasil a Fundo — Curso de História e Geografia

Curso gratuito e aprofundado de **História e Geografia do Brasil**, com o essencial de **História Geral** e **Geografia Geral**. Tudo em um único arquivo `index.html` (HTML + CSS + JavaScript), sem dependências.

## Trilhas (133 aulas, todas completas)
1. 📜 História do Brasil — 66 aulas
2. 🗺️ Geografia do Brasil — 33 aulas
3. 🌍 História Geral — o essencial — 23 aulas
4. 🌐 Geografia Geral — o essencial — 11 aulas

Cada aula traz: objetivo, por que importa, explicação aprofundada, dados e números-chave com fonte, linha do tempo, conceitos e personagens, mitos e confusões comuns, conexão Nordeste/Ceará, resumo e links gratuitos para aprofundar.

## Recursos
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
3. Clique em **uploading an existing file** e arraste os arquivos desta pasta: `index.html`, `README.md`, `PROMPT.md` e `.nojekyll`. Clique em **Commit changes**.
   - O `.nojekyll` começa com ponto e pode ficar oculto no seu computador; ele é opcional.
4. Vá em **Settings › Pages**. Em **Source**, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e clique em **Save**.
5. Em 1–2 minutos o site estará em `https://SEU-USUARIO.github.io/brasil-a-fundo/`.

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
