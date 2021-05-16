A Cascata (cascading)
    A escolha do browser de qual regra aplicar, caso haja muitas regras para o mesmo elemento.
        - Seu estilo é lido de cima para baixo

        - É elevado em consideração d 3 fatores:
        1. Origem do estilo
            inline > tag Style > tag link

        2. Especifidade
            É um calculo matemático, onde, cadda tipo de selector e origem do estilo, possuem valorres a serem considerados.
                0. Universal selector, combinators e negation pseudo-class (:not())

                1. Element type selector e pseudo-elements (::before, ::after)

                10. Classes e attribte selector ([type="radio"])

                100. ID selector

                1000. Inline


        3. Importância
            É a regra !important
                - cuidado, evite o uso
                - não é considerada uma boa prática
                - Quebra o fluxo natural da cascata

