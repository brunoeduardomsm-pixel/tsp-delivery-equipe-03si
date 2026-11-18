# Tabela de testes

Responsável: Wellington Braga (Analista de Qualidade e Teste)

| Tela | O que testar | Resultado esperado | Resultado obtido |
|---|---|---|---|
| Início | A página abre sem erro | Carrega normal | abriu normal o botão “ver cardápio” funcionou. |
| Cardápio | A lista de pratos aparece | Pratos visíveis | Abriu normal os 6 pratos aparecem com foto e os botões levam ao carrinho. |
| Carrinho | Os itens e o total aparecem | Lista e total corretos | Abriu normal o botão finalizar pedido levou até o acompanhar. |
| Acompanhar pedido | As etapas do pedido aparecem | Etapas visíveis | Abriu e as etapas com o entregador apareceram. |

## Revisão
Wellington revisou as telas feitas pelo Lucas (carrinho e acompanhar) e pelo Gabriel (CSS).

## Problema encontrado e corrigido
Ao abrir o cardápio no celular, as fotos dos pratos ficaram grandes e estouravam a tela. O Gabriel colocou o CSS dos pratos (tamanho fixo e foto ajustada) e depois testamos de novo e ficou certo.

## Observação
O carrinho é fixo (não muda quando clica em "Pedir"). É uma limitação do protótipo.
