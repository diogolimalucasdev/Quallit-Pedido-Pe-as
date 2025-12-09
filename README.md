# Portal Quallit – Peças (Estoque e Pedido)

Frontend estático em HTML/CSS/JS puro, responsivo e leve, no padrão visual do portal Quallit.

## Conteúdo
- `index.html`: tela inicial com links para estoque e pedido.
- `estoque.html`: informar quantidades em estoque e gerar mensagem pronta para WhatsApp/E-mail.
- `pedido.html`: solicitar peças com prioridade, observações e resumo pronto para envio.
- Lista de peças carregada localmente via array JS (fácil de trocar por planilha/JSON).
- Botões de envio: WhatsApp (+55 11 97877-7597) e E-mail (diogo.lima@quallit.com.br, henrique.ferreira@quallit.com.br).
- Seleção de CD/Estoque com opção “Outro” (obriga nome/região).
- Formatação da mensagem em texto simples (quebra de linha real).

## Uso local
Abra `index.html` no navegador (desktop ou mobile). Links relativos levam para estoque/pedido.

## Publicação rápida
Arraste a pasta no [Netlify Drop](https://app.netlify.com/drop) para gerar um link público e compartilhar no WhatsApp. Também funciona em GitHub Pages ou Vercel (projeto estático).

## Ajustes rápidos
- Trocar peças: editar o array `pecas` em `estoque.html` e `pedido.html`.
- Alterar contatos/WhatsApp: editar os links no fim dos scripts.
- Adicionar PDF/Imprimir: incluir `window.print()` com CSS de impressão (opcional).

