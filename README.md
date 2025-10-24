# FAQ - Consultoria FAPESB

Site simples com perguntas frequentes para apoiar submissões de editais.

## Deploy no Vercel

1. Se você ainda não tem, crie uma conta em https://vercel.com e instale o Vercel CLI (opcional).
2. No painel do Vercel, crie um novo projeto e conecte o repositório `faq-ciencia-mesa` (ou arraste e solte a pasta local).
3. O Vercel detecta sites estáticos automaticamente. Caso necessário, use as configurações de build padrão. O `vercel.json` já inclui o build para arquivos estáticos.

Deploy com Vercel CLI (opcional):

```bash
npm i -g vercel
vercel login
vercel
```

## Execução local

Basta abrir `index.html` no navegador ou usar um servidor estático como `live-server` ou `python -m http.server`:

```bash
# com Python 3
python -m http.server 3000
# então abra http://localhost:3000
```

## Notas

- Arquivo `styles.css` contém o estilo principal.
- O site é intencionalmente leve e sem dependências.