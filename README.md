# Meu Pet — Área de Aulas

Versão estática pronta para publicar no GitHub e conectar ao Vercel.

## Conteúdo do pacote

Este ZIP contém somente:

- `index.html` — aplicação completa, com estilos, JavaScript e imagens de capa embutidos;
- `README.md` — instruções de publicação.

A área possui:

- 27 aulas de cachorrinhos;
- 10 aulas de gatinhos;
- 37 videoaulas no total;
- navegação entre aula anterior e próxima aula;
- acesso direto à coleção seguinte;
- layout mobile-first.

## Publicar no GitHub

1. Crie um repositório novo no GitHub.
2. Extraia este ZIP.
3. Envie `index.html` e `README.md` para a raiz do repositório.
4. Confirme o commit.

Não crie pasta `src`, `assets`, `public` ou `dist`. Todo o projeto necessário já está dentro do `index.html`.

## Publicar no Vercel

1. Entre no Vercel.
2. Clique em **Add New → Project**.
3. Importe o repositório do GitHub.
4. Em **Framework Preset**, selecione **Other**.
5. Não informe comando de build.
6. Não altere o diretório de saída.
7. Clique em **Deploy**.

Como o site é estático, o Vercel publicará diretamente o `index.html`.

## Observações

- As capas principais estão embutidas no arquivo.
- As miniaturas e os players são carregados pelo YouTube.
- A plataforma precisa de internet para reproduzir as videoaulas.
- Se o proprietário de algum vídeo bloquear a incorporação em sites externos, esse vídeo poderá continuar indisponível dentro da plataforma, mesmo que abra normalmente no YouTube.
