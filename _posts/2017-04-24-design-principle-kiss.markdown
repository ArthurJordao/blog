---
layout: post
title:  "Design principle: K.I.S.S."
date:   2017-04-24 16:56:49 -0300
categories: Organizacao
excerpt: "Quando nos deparamos com algum desafio, sempre buscamos soluções bem elaboradas e complexas, mas às vezes precisamos de simplesmente um beijo (KISS) para solucionarmos tal problema."
---

Quando nos deparamos com algum desafio, sempre buscamos soluções bem elaboradas e complexas, mas às vezes precisamos de simplesmente um beijo (KISS) para solucionarmos tal problema.

## Mas o que seria KISS?

KISS é um princípio de projeto formado, no decorrer do ano de 1960, pela marinha americana (U. S. Navy) e é acrônimo de “Keep it simple, stupid”, ou, traduzindo para o português, significa: “mantenha isto simples, estupido”. Ele afirma que a maioria dos sistemas trabalha melhor se forem mantidos simples ao invés de elaborados de forma complexa, sendo assim, a simplicidade deveria ser um objetivo no projeto e complexidades não necessárias deveriam ser evitadas.

Esse acrônimo vem sendo adotado por vários militares americanos e tem sido muito utilizado também no campo de desenvolvimento de software.

## Onde utilizar este princípio.

Como desenvolvedor, posso afirmar que este princípio é muito útil, pois ensina a melhorar a organização em seu código e a deixa-lo mais legível, como esses exemplos de pseudocódigo:

```
Exemplo (Não utilizando KISS) 1:

    se banco_arrumado e luzes_funcionando e retrovisor_ajustado e cinto_colocado então
      dirigir()
```
```
Exemplo (Utilizando KISS) 2:

    se esta_pronto_para_dirigir então
      dirigir()
```

Podemos observar que no primeiro exemplo temos de verificar todos os requisitos um a um para dirigir, enquanto no segundo, nós só perguntamos se tudo está pronto para dirigir o que faz com que o código seja mais legível e fácil de se entender e caso você tenha de verificar novamente, um por um, para saber se está apto a dirigir ou não, você poderá simplesmente perguntar, novamente, à variável: esta_pronto_para_dirigir e ela terá a resposta.

Agora,  você pode estar se perguntando “Mas… eu não sou desenvolvedor. Onde eu poderia usar isso?”.

Como na programação, a vida real apresenta várias formas de você resolver o mesmo problema, então, por que não encontrar a mais simples ao invés da mais complexa?

## Como encontrar a solução mais simples?

Existem várias formas de você encontrar a solução mais simples para um problema, então listei algumas aqui para te ajudar:

- **DRY: Don’t repeat yourself (Não repita a si mesmo).** Se existem ferramentas que possam te ajudar a solucionar esse problema, use-as. Não tente reinventar a roda ou cometer ambiguidades em seu projeto.
- **Analise sua solução criticamente.** Não tente encontrar uma solução muito rápido e achar que ela é a perfeita. Analise-a, veja seu grau de complexidade, compare com outras ideias etc, tenha certeza de um resultado eficaz.
- **Veja como outras soluções foram implementadas.** Muitas vezes a solução de seu problema já foi inventada e você só quer aperfeiçoa-la, ou é uma solução bem parecida com a que você precisa, então analise essa solução, aprenda com os erros dela, pois é melhor aprender observando o erro dos outros do que repeti-los.
- **Faça uma lista de soluções.** Liste todas as soluções possíveis para seu problema, então escolha a que for mais simples.

## Conclusão

Há várias formas de você encontrar uma solução mais simples e eficaz, explore-as, tenha o hábito de sempre tentar encontra-la, depois de um tempo de prática, ela aparecerá para você quase que instantaneamente.

Saiba que a solução mais simples pode estar mais próxima do que você imagina.

![Frase de Leonardo da Vinci: "A simplicidade é o último grau de sofisticação"]({{ site.url }}/{{ site.baseurl }}/assets/images/2017/april/simplicidade-leonando-da-vinci.jpg)
