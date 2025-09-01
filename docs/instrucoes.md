---
hide:
  - navigation
---

# Manual de uso

Reiterando: a leitura desta parte é opcional. Tentei manter o aplicativo simples, de modo que funcione sem manual. 

Além disso, eu queria ter colocado algumas dessas instruções em botões de ajuda dentro do próprio aplicativo, mas acabei esquecendo antes de enviar pra a Google Play, e como a aprovação lá demora um pouco... vai aqui por fora, mesmo.

## Funções básicas

### Tela: Lista de produtos 


Esta tela inclui:

- Botão para incluir novos produtos
- Toque longo para renomear ou excluir produto

Escolhendo um produto, abre a tela com as opções de compra para cada produto.

<div markdown = "1" class='container'>

<div markdown = "block">
### Tela: Lista de opções de um produto

![Tela: lista de opções](assets/tela_opcoes_300px.jpg#right)

Esta tela mostra as opções ordenadas por "preço relativo", ou seja, o preço calculado para determinada quantidade do produto.

No botão `Configurar` é possível ajustar algumas coisinhas: a unidade usada no cálculo do "preço relativo" e a quantidade de casas decimais.

A conversão entre unidades é importante pois você pode incluir, por exemplo, uma opção em litros e outra em mililitros. Convenientemente, os resultados podem ser mostrados todos na mesma unidade, facilitando comparações.

Tocando em uma opção de produto, abre a tela com os detalhes dela.

</div>
</div>

<div markdown = "1" class='container'>
<div markdown = "block">
### Tela: Detalhes da um opção de produto

![Tela: lista de opções](assets/tela_detalhe_opcao_300px.jpg#right)

Nesta tela, você pode inserir e editar:

  - nome da opção {--(obrigatório)--} {==(edit: 31.ago)==}
  - loja que está vendendo {--(opcional)--} {==(edit: 31.ago)==}
  - valores e quantidades
  - unidade de medida

Com base nos valores indicados, o aplicativo calcula o preço relativo.

Conforme você edita alguns valores, outros são recalculados. Então, há duas formas básicas de incluir as informações, dependendo da situação e do objetivo.

- Incluir preço unitário e a quantidade por unidade, desconsiderando o campo "Unidades por pacote" (deixar `1`).
- Incluir preço do pacote, unidades por pacote e quantidade em cada unidade. Esta forma é bastante útil para o exemplo do papel higiênico (pacote com `X` rolos de `Y` metros), por exemplo.

</div>

</div>

### Unidade de medida

![Modal: unidade de medida](assets/modal_unidade_250px.jpg#right)

A escolha da unidade de medida é bem importante, pois é a base de comparação para o preço relativo.

- Além das unidades de massa e volume predefinidas , você pode escolher `Outra:` e digitar uma unidade de quantificação qualquer, como `folhas` ou `parafusos`.
- Para comprimento, o aplicativo por enquanto reconhece `m`, `cm` e `km` para posterior conversão entre essas unidades de medida. Para dar certo, precisa ser em letras minúsculas (é uma limitação boba que reparei ontem; simples de corrigir na próxima versão).
- Para palavras, você pode inserir singular e plural separados por vírgula: `parafuso,parafusos`, por exemplo. Daí, o aplicativo tenta mostrar a forma correta conforme necessário. Esse recurso é importante para que os revisores não pirem ao usar o aplicativo. 
- Também planejo inserir unidades fora do sistema métrico, mas isso não é uma prioridade.