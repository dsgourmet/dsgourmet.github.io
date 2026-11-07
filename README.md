# DS Gourmet

Landing page da **DS Gourmet**, confeitaria do Davy Soares.

- Instagram: [@ds_gourmet__](https://www.instagram.com/ds_gourmet__/)
- WhatsApp: (19) 99963-1042
- Endereço: Rua João Guimarães, nº 117 – Haise Maria

## O que tem na página

- Logo animado e interativo, com efeito 3D e faíscas ao clicar
- Cardápio com os doces (brownie, bolos, bolo no pote, morango do amor e pão de mel), cartões que viram e filtros
- Montador de encomenda que gera a mensagem pronta para o WhatsApp
- Depoimentos em carrossel e áudio de uma cliente
- Contato, mapa e Instagram

## Estrutura

```
index.html                 site completo (HTML, CSS e JS em um arquivo; o áudio já vai embutido)
assets/agradecimento.mp3   trecho do áudio da cliente, separado para edição
```

## Como publicar

O site é um único arquivo estático, então funciona em qualquer hospedagem.

**GitHub Pages:** em *Settings › Pages*, escolha *Deploy from a branch*, branch `main` e pasta `/ (root)`. O site fica em `https://<usuario>.github.io/ds-gourmet/`.

**Netlify Drop:** arraste o `index.html` para [app.netlify.com/drop](https://app.netlify.com/drop).

## Editar

Os textos, o número de WhatsApp e a lista de doces ficam no próprio `index.html`. Os doces e depoimentos estão nas listas `PRODUCTS` e `REV`, dentro do `<script>` no fim do arquivo.
