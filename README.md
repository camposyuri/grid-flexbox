# CSS GRID

## GRID

- Bimensional
- Divisao de toda a páina em linhas e colunas
- Colocar elementos onde quiser nessa divisão

---

## GRID OU FLEXBOX

- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (ou coluna ou linha)
- Um completa o trabalho do outro
- Verificar quais navegadores ainda não estão aceitando o Grid

---

## PROPRIEDADES

Vamos separar em 2 grupos:
`container` e `item(s)`

## CONTAINER

- display: grid;
- grid-template-columns;
- grid-template-rows;
- gap
  - grid-rows-gap
  - grid-column-gap
- grid-template-areas;

... e mais 4 propriedades e **alinhamento**

---

## ITEM(s)

- grid-column
  - grid-column-start
  - grid-column-end
- grid-row
  - grid-row-start
  - grid-row-end
    -grid-area

... e mais 2 propriedades de **alinhamento**

# Grid: Aliamento

---

Existem 6 propriedades para aliamento:
`justify-content`
`align-content`
`justify-items`
`align-items`
`justify-self`
`align-self`

Vamos separá-los em 2 grupos

1. `justify` e `align`
2. `content`, `items` e `self`

---

## Justify e Align

Sabendo que o grid é bidimensional, nós temos o eixo x e o y.

O **eixo x** é o posicionamento horizontal, da esquerda para a direita.

O **eixo y** é o posicionamento vertical, de cima para baixo.

---

### Content, Items e Self

Juntando o `justify`, ou `align`, com esses
elementos: `content`, `items` e `self`;
nós observamos nossas propridades.

---

### Content
