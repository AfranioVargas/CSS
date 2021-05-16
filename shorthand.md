Shorthand
    - junção de propriedades
    - resumido
    - legível

''' exemplos no css
{
    /*background properties*/
        background-color: #000;
        background-image: url(images/bg.gif);
        background-repeat: no-repeat;
        background-position: left top;
    /*background shorthand*/
    background: #000 url(images/bg.gif) no-repeat left top;

    /*font properties*/
        font-sytle: italic;
        font-weight: bold;
        font-size: .8em;
        line-height: 1.2;
        font-family: Arial, sans-serif;
    /* font shorthand*/
font: bold italic .8em/1.2 Arial, sans-serif

DETALHES
    - não irá considerar propriedades anteriores
    - valores não especificados irão assumir o valor padrão
    - geralmente, a ordem descrita não importa, mas, se houver muitas propriedades com valores semelhantes, poderemos encontrar problemas.

PROPRIEDADES QE ACEITAM SHORTHAND
    animation, background, border, border-bottom, boder-color, border-left, border-radius, border-right, border-style, border-top, border-width, column-rule, columns, flex, flex-flow, font, grid, grid-area, grid-column, grid-row, grid-template, list0-style, margin, offset, outline, overflow, padding, place-content, place-items, place-self, text-decoraton, transition

    **https://developer.mozilla.org/en-US/docs/Web/CSS/Shorthand_properties**