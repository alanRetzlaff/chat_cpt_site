# Motryz Tech Landing Page

Landing page estática da Motryz Tech para apresentar soluções de RPA, automação inteligente e contato comercial.

## Como ver a prévia

Este projeto é composto apenas por arquivos estáticos (`index.html`, `styles.css` e `script.js`), então você pode visualizar de duas formas:

### Opção 1: abrir o arquivo diretamente

1. Baixe ou clone este repositório na sua máquina.
2. Abra o arquivo `index.html` no navegador.

### Opção 2: rodar um servidor local

Na raiz do projeto, execute:

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

Depois acesse no navegador:

```text
http://localhost:4173/
```

> Importante: se o servidor estiver rodando em um container/ambiente remoto, `127.0.0.1` aponta para a máquina de quem está abrindo o navegador, não para o container. Nesse caso, use o recurso de **port forwarding** da sua ferramenta para expor a porta `4173`, ou rode o comando acima diretamente na sua máquina.

## Estrutura

```text
.
├── index.html   # Conteúdo e estrutura da landing page
├── styles.css   # Estilos, layout responsivo e identidade visual
└── script.js    # Interação simples do formulário de contato
```
