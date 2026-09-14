Boa noite! Para um blog de games com o **Nikola**, os comandos mais usados ficam principalmente nestas categorias:

 ### Comandos essenciais

 - `nikola init` — cria um novo site/projeto Nikola.
- `nikola build` — gera o site estático a partir dos arquivos-fonte.
- `nikola serve` — inicia um servidor local para visualizar o site.
- `nikola auto` — monitora alterações e recompila automaticamente.
- `nikola check` — verifica problemas no site.
- `nikola deploy` — publica o site conforme a configuração de deployment.
- `nikola clean` — remove arquivos gerados pelo Nikola.
- `nikola status` — mostra informações sobre o estado do site.
- `nikola help` — exibe ajuda sobre comandos e opções.

 ### Para posts

 - `nikola new_post` — cria um novo artigo.
- `nikola new_page` — cria uma página estática, como “Sobre”.
- `nikola list_posts` — lista os posts existentes.
- `nikola new_post -t "Título"` — cria um post já especificando o título.

 ### Fluxo típico

```
nikola init
cd meu-blog
nikola new_post -t "Meu primeiro review"
nikola build
nikola serve
```

 Depois, durante o desenvolvimento, `nikola auto` é especialmente conveniente porque recompila o site conforme você altera os arquivos.