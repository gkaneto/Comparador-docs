---
hide:
  - navigation
---

# Testando e reportando

Há duas possibilidades de teste. Fique a vontade pra seguir qualquer caminho:

- uso mais geral no dia a dia
- teste mais detalhado, passando pelo [Checklist](checklist.md).

Se reparar algo errado ou tiver alguma sugestão, você pode me enviar uma mensagem.

Já adianto que há probleminhas já conhecidos, infelizmente...

## Limitações e erros conhecidos

### Erro de arredondamento

O programa no momento arredonda tudo pra duas casas decimais. Então, às vezes acontece de o valor recalculdado mudar sozinho para algo que você não digitou.

Eu não mudei ainda porque preciso mudar um trecho grande do código, pra separar os dados armazenados dos dados exibidos.

### Opção de produto com desrição vazia

Ao criar uma nova opção, o usuário não consegue salvá-la se o campo "Descrição" estiver vazio. Mas se apertar "voltar" (na tela ou usando o botão do celular) sem alterar nada, será criada uma opção "vazia". 

No momento, estou vendo o melhor jeito de lidar com isso, sem atrapalhar outras funcionalidades ou complicar demais. Para contornar, é possível entrar na opção vazia e apertar "Excluir".

### Outros problemas e melhorias

Estou montando uma listinha no Github:

- no [formato lista](https://github.com/gkaneto/Comparador-bugs-e-melhorias/issues){:target="_blank"}
- no [formato quadro](https://github.com/users/gkaneto/projects/1/views/1){:target="_blank"}

Você pode só entrar e olhar. Mas, se quiser - só pela diversão - pode criar um usuário no github e incluir você mesmo um problema nessa lista. 

*[diversão]: Uau! Que ótima forma de gastar um tempinho do final de semana!

Para isso, basta usar o botão "New issue" e escolher se quer indicar um *bug* ou uma melhoria.

Ainda dá pra acompanhar como eu vou priorizar resolver seu probleminha e se ele já foi solucionado.