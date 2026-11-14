# Numerical — site pessoal

Site estático, responsivo e navegável. Usa os arquivos originais de identidade visual e inclui o e-book gratuito.

## Visualizar localmente

Abra `index.html` no navegador. Os links internos usam rotas com `#`, compatíveis com hospedagem estática.

## Publicar na Vercel

1. Crie um repositório no GitHub e envie o conteúdo desta pasta para a raiz.
2. Na Vercel, selecione **Add New > Project**, importe o repositório.
3. Em Framework Preset, escolha **Other**. Não há comando de build nem dependências.
4. Faça Deploy. Em Settings > Domains, adicione `numerical.com.br` e siga os registros DNS apresentados pela Vercel.

## Conteúdo

Os artigos iniciais são resumos editoriais para demonstrar a navegação. Antes da publicação definitiva, amplie e revise os textos, inclua fontes e datas de atualização. As áreas de IA e Tecnologia & Negócios estão preparadas, mas sem artigos publicados.

## Arquivos

- `index.html`: interface, estilos, navegação e artigos de demonstração.
- `assets/logo.png`: logo original Numerical.
- `assets/icone.png`: ícone original Numerical.
- `assets/guia-tokenizacao.pdf`: e-book gratuito.

## Próxima evolução

Separar os artigos em arquivos MDX e migrar para Next.js se houver necessidade de SEO por artigo, edição frequente, busca ou CMS. Esta versão é propositalmente estática e simples, sem login nem banco de dados.
