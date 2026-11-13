# 🎨 Pasta `css/`

Contém todos os estilos do site.

## 📁 Conteúdo

| Caminho | Função |
| --- | --- |
| `contato.css` | CSS que estiliza `contato.html`. |
| `filmes.css` | CSS que estiliza `filmes.html`. |
| `header.css` | CSS que estiliza o header de todas as páginas HTML. |
| `index.css` | CSS que estiliza `index.html`. |
| `sobre.css` | CSS que estiliza `sobre.html`. |
| `filmes/` | CSS exclusivo de cada filme, organizado em subpastas por gênero (`acao`, `aventura`, `comedia`, `ficcao-cientifica`, `romance`, `animacao`, `terror`). |

## 📌 Regras

- 🎞️ Há **um arquivo CSS para cada filme** (35 no total), com o mesmo nome da página HTML. Exemplo: `css/filmes/terror/psicose.css` é usado por `filmes/terror/psicose.html`.
- 🌈 Os CSS dos filmes definem a paleta de cores, o tema visual e a imagem de fundo ou filme de fundo da obra. Exemplo: terror usa tons de verde-escuro, preto e vermelho.
- 🚫 Não tem nos CSS dos filmes estilos de header e nav. Isso fica em `header.css`.
- 🎭 Em `filmes.html`, a paleta de cores muda de acordo com o gênero selecionado, seguindo a mesma ideia.
