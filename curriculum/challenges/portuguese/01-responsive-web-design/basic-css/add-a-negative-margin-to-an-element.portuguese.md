---
id: bad87fee1348bd9aedf08823
title: Add a Negative Margin to an Element
challengeType: 0
guideUrl: 'https://portuguese.freecodecamp.org/guide/certificates/add-a-negative-margin-to-an-element'
videoUrl: ''
localeTitle: Adicione uma margem negativa a um elemento
---


## Descrição
<section id="description"> O elemento <code>margin</code> controla a quantidade de espaço entre o elemento <code>border</code>  e os elementos adjacentes. Se você definir o elemento <code>margin</code> com um valor negativo, o elemento ficará maior. </section>

## Intruções
<section id="instructions"> Tente definir a <code>margin</code> para um valor negativo como o da caixa vermelha. Altere a <code>margin</code> da caixa azul para <code>-15px</code>, para preencher toda a largura horizontal da caixa amarela em torno dela.</section>

## Testes
<section id='tests'>

```yml
tests:
  - text: Sua classe <code>blue-box</code> deve fornecer elementos de <code>-15px</code> de <code>margin</code> .
    testString: 'assert($(".blue-box").css("margin-top") === "-15px", "Your <code>blue-box</code> class should give elements <code>-15px</code> of <code>margin</code>.");'

```

</section>

## Desafio
<section id='challengeSeed'>

<div id='html-seed'>

```html
<style>
  .injected-text {
    margin-bottom: -25px;
    text-align: center;
  }

  .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }

  .yellow-box {
    background-color: yellow;
    padding: 10px;
  }

  .red-box {
    background-color: crimson;
    color: #fff;
    padding: 20px;
    margin: -15px;
  }

  .blue-box {
    background-color: blue;
    color: #fff;
    padding: 20px;
    margin: 20px;
  }
</style>

<div class="box yellow-box">
  <h5 class="box red-box">padding</h5>
  <h5 class="box blue-box">padding</h5>
</div>

```

</div>



</section>

## Solução
<section id='solution'>

```js
// solution required
```
</section>
