# Naucoólicos

Protótipo estático do site dos Naucoólicos, torcida do Náutico. Esta versão serve para apresentar a ideia, recolher opiniões da torcida e alinhar conteúdo e layout antes da próxima etapa do projeto.

## Conteúdo atual

- Apresentação da torcida, história, identidade e escudo.
- Fotos da arquibancada e artes da torcida.
- Próximos jogos cadastrados diretamente no HTML.
- Prévia de produtos da torcida, marcados como “Em breve”.
- Link para o Instagram e formulário de interesse.

O formulário **não envia nem armazena dados**: após a validação, ele informa que esta é uma demonstração. Os jogos também são dados fixos; o JavaScript oculta partidas cuja data final já passou. Antes de cada apresentação, confira se a agenda ainda está correta.

## Estrutura

```text
index.html  Página completa, com CSS e JavaScript incorporados
img/        Imagens utilizadas pela página
```

Não há dependências, instalação ou etapa de compilação. Para visualizar localmente, abra `index.html` no navegador. Também é possível servir a pasta com `python -m http.server 3000` e abrir `http://localhost:3000/`.

## Publicação na Vercel

1. Importe o repositório `joseiltonjunior/naucoolicos` na Vercel.
2. Use a raiz do repositório como **Root Directory**.
3. Selecione **Other** em **Framework Preset**.
4. Deixe o **Build Command** vazio e use `.` como **Output Directory**.

A Vercel servirá o `index.html` e a pasta `img/` diretamente. O formulário continuará demonstrativo nessa publicação.

## Próxima etapa

Após a apresentação, revisar conteúdo e layout com a torcida. A conversão para React e a adoção dos padrões do projeto `sonoriza-contatcs` ficam para uma etapa posterior.

Este é um site de torcida e não o site oficial do Clube Náutico Capibaribe.
