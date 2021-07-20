# At-rules

* Está relacionado ao comportamento do CSS
* Começa com o final de `@` seguido do identificador e valor


## Exemplos comuns

- @import       /* incluir um css externo */

- @media        /* regras condicionais para dispositivos */

- @font-face    /* fontes externas */

- @keyframes    /* Animation */

```css

@import "http://local.com/style.css";

/*  ou @import url("http://local.com/style.css");  */

@media (min-width: 500px) {
    /*regras aqui*/
}

@font-face{
    /*regras aqui*/
}

@keyframes nameofanimation {
    /*regras aqui*/
}