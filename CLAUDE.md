# privacy

Política de privacidade única dos apps 1000apps: `index.html` (PT-BR e EN no mesmo arquivo, com alternador de idioma).
Publicada em https://the1000apps.github.io/privacy/ por GitHub Pages (build `legacy`, branch `main`, raiz). **Não existe
branch `gh-pages`: deploy = push na `main`** (leva ~30 s; confira com `gh api repos/the1000apps/privacy/pages/builds/latest`).

## Ambiente

Site estático sem build: abra `index.html` no navegador ou sirva com `python -m http.server` (qualquer SO).
Nada depende de caminho da máquina.

## Regras

- Quando um app ganha permissão, SDK ou chamada de rede, atualize a tabela e a seção correspondente **nos dois idiomas**
  e a data de "Last updated".
- Novo app = nova linha na tabela de apps.
- Commit/push só quando o usuário pedir.
