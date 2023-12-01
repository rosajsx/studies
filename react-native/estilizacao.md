# Estilização no React native

## Caracteristicas

- Quase Css, existem diversas propriedades iguais ou similares as existentes no Css

- Propriedades são definidas em camelCase

- Nossos elementos já flex por padrão, funciona igual ao do Css.

- Por padrão o flexDirection dos elementos é column, ou seja os elementos vão ser posicionados em coluna

- Não existem estilos globais, é necessário estilizar os componentes 1 a 1.
- Não existe herança de estilo, nossos elementos não irão herdar estilos de componentes pai, por exemplo "Temos uma View com font-size de 14px, no Css normal, nossos textos existentes dentro da div irão herdar a font-size, tendo assim 14 pixels", porém no React Native isso não existe, é necessário por 1 a 1.

- Propriedades próprias

  - marginStart
  - marginEnd
  - marginHorizontal
  - marginVertical
  - elevation
  - borderCurve
  - shadowColor
  - shadowOffset
  - ...

- Nota: Não é uma boa pratica por estilos in-line no JSX, prezando por manutenabilidade. Outro ponto importante é, performance. A cada renderização o componente estaria criando/re-criando o objeto de estilos.

## Como criar estilos e atribuir

- No React native, podemos atribuir através da propriedade `style`

- Podemos criar estilos simplesmente construindo um objeto, porém não possuimos o `intelisense`, ou seja um auxilio muito util para nós desenvolvedores, as possiveis propriedades que podemos escolher.

- Para isso, o `react-native` disponibiliza um objeto chamado `StyleSheet`.

- Para criar um objeto de estilos, basta utilizar o `StyleSheet.create({})`

- Até a versão atual, não existe nenhum outro beneficio além do `intelisense` na utilização do `StyleSheet.create`
