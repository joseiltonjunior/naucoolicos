# Naucoólicos

Protótipo estático do site dos Naucoólicos, torcida do Náutico. Esta versão serve para apresentar a ideia, recolher opiniões da torcida e alinhar conteúdo e layout antes da próxima etapa do projeto.

## Conteúdo atual

- Apresentação da torcida, história, identidade e escudo.
- Fotos da arquibancada e dos encontros da torcida.
- Próximos jogos cadastrados diretamente no HTML.
- Apresentação inicial dos planos Individual e Família, sem valores definidos.
- Prévia de produtos e espaço para notícias, ainda sem catálogo ou matérias reais.
- Link para o Instagram oficial e aviso de que um canal direto de contato será disponibilizado em breve.
- Header branco fixo, faixa de frases entre a história e a logo, mosaico de fotos clicáveis e entrada suave dos elementos uma vez; o movimento é reduzido conforme a preferência do navegador.
- Logo e mascote v2 na página, ícone v2 na aba e versão da logo com fundo na prévia de compartilhamento.

O contato direto ainda não está ativo: por enquanto, a página aponta para o Instagram oficial e informa que um canal será anunciado em breve. Quando a torcida definir se usará WhatsApp, e-mail ou outro destino, o formulário poderá ser integrado. Os planos **não têm cadastro ou pagamento ativo**. Os jogos também são dados fixos; o JavaScript oculta partidas cuja data final já passou. Antes de cada apresentação, confira se a agenda ainda está correta.

O texto de história foi escrito a partir do contexto inicial fornecido pela torcida e precisa de validação antes de ser tratado como texto oficial. Também faltam confirmação dos valores e benefícios dos planos, fotos e preços dos produtos, notícias reais e número do WhatsApp oficial.

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

A Vercel servirá o `index.html` e a pasta `img/` diretamente. O contato direto ainda não está ativo nesta versão.

## Próxima etapa

Após a apresentação, revisar conteúdo e layout com a torcida. A conversão para React e a adoção dos padrões do projeto `sonoriza-contatcs` ficam para uma etapa posterior.

Este é um site de torcida e não o site oficial do Clube Náutico Capibaribe.
