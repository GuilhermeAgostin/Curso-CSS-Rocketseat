# Codigo HTML: 

<meta charset="UTF-8">

<div id="container" class="m-40">
  <h1>Título da página</h1>
  <h2>Subtítulo</h2>
</div>

# Codigo CSS: 

```css

*{
  margin: 0;
  
  /* Aqui para todos os elementos eu seto a margem de 0*/
}

#container {
  width: 200px;  /*largura*/
}

.m-40 {
  /* Espaçamento da borda */
  margin: 40px;
}

h1, h2
{
    color: green;
    font-size: 60px;
    background: gray;
}

```
_____________________________________________________________________________________

# Codigo HTML: 

<meta charset="UTF-8">

<h1>Evolua rápido</h1>

<p>Descrição</p>

<button> Embarcar</button>

# Codigo CSS: 

```css
h1 {
  border: 1px solid red;
  margin: 20px; 
  padding: /*Preenchimento interno, espaço por dentro da caixa*/
}

```
________________________________________________________________________________________

# Codigo HTML: 

<meta charset="UTF-8"> 
<style>
  h1{
    color: gray;
  }
</style>
<h1 style="color: green">Evolua rápido</h1> 

<p>Descrição</p>
<button> Embarcar</button>

# Codigo CSS: 

```css

h1 { color: red; } 
h1 { color: blue;}

``` 


________________________________________________________________________________________________________________________________

# Codigo HTML: 

<meta charset="UTF-8"> 
<h1 class="title" id="my-title" style="color: orange;">Título <strong> alo</strong></h1> <!-- Aplicacao do inline -->
<p>parágrafo</p>

```css

    #my-title,
    #my-title strong
    { color: gray; } /* seletor de identificador */

    .title { color: red; } /* seletor de atributo - valor de 10  */

    h1 { color: blue; } /* esse é um type selector no valor de um */


    /*aqui ele sobrescreve a cor ja definida*/ /*ideia de cascata , ele esta caindo, mantem uma cadencia de cima pra baixo*/ 

    *{
    color: green;
    }

    /*evitar uso do important - so usar quando esta consumindo uma lib de fora - ele quebra o fluxo natural da cascata*/


``` 





