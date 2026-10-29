# Entre Páginas — blog literário

Site estático de página única (`index.html`), com roteamento por hash (`#/resenhas`, `#/livro/...`).
Os conteúdos (livros, autores, listas) ficam nas constantes `B`, `AUTH` e `LISTAS` dentro do `<script>`.

## Publicar na Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Na Vercel: Add New > Project > importe o repositório.
3. Framework Preset: Other. Sem build command e sem output directory. Deploy.
Cada `git push` na branch principal gera um novo deploy automaticamente.

## Observações
- Conteúdo ainda de demonstração/rascunho: revisar antes do lançamento (editora, ano, tradutor, biografias).
- Formulários validam no navegador e gravam só em localStorage; envio real exige backend.
- Painel administrativo não implementado (ver página #/admin).
