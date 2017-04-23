---
layout: post
title:  "Por que jekyll?"
date:   2017-04-22 10:12:35 -0300
categories: Desenvolvimento
excerpt: Motivos para eu ter escrito o blog em jekyll.
---
Quando temos a ideia de escrever um blog sempre vem a mente em fazê-lo com o famoso wordpress, mas nem sempre
precisamos de uma ferramenta tão sofisticada quanto o wordpress e esse foi meu caso e talvez seja o seu também,
então vejamos quais foram os pontos que me levaram a usar o jekyll.

## Introdução ao Jekyll
Jekyll é um gerador de blog estático. Isto significa que ao invés de você ter um programa feito em uma linguagem
como PHP, você usa a linha de comando para gerar arquivos estáticos para você (HTML, CSS, JavaScript, etc).

Os arquivos estáticos são gerados a partir de alguns arquivos de configuração, templates e arquivos markdown para
páginas fixas e posts.

Você pode depois simplesmente fazer o upload para qualquer servidor web e seu blog estará funcionando.

## 1. Custo de host.
Quando fazemos um blog em wordpress uma das coisas que encarece o custo é o host, onde pagamos algo em torno de 10
reais ao mês para um blog de pequeno porte.

Enquanto isso você consegue host totalmente grátis com o jekyll como o do GitHub, pois o jekyll usa html estático,
então elimina a necessidade de um servidor php que exige mais processamento e memória que um servidor de arquivos
estáticos.

## 2. Jekyll é mais rápido.
O WordPress é processado de forma dinâmica, então toda a solicitação feita ao servidor demanda de chamadas ao
banco de dados, processamento de variáveis etc. Enquanto o jekyll é totalmente estático, então não necessita de
nenhum processamento de dados no servidor e o jekyll ainda oferece otimização como:
* Host inteiramente em nginx.
* Minificação do CSS e HTML.
* Evita o uso de plugins pesados para cacheamento.
* Tem melhor controle nos temas.

## 3. WordPress é complexo.
WordPress hoje em dia é um grande framework PHP para blogs, sites etc o que leva a uma grande quantidade de
ferramentas que para um blog simples não é necessário.

Jekyll, por outro lado oferece ferramentas simples que faz com que o desenvolvimento do blog seja fácil então:
* Jekyll tem tudo que você precise para um blog e não tem nada que você não precise.
* **Escrever um post é muito fácil e flexível.** Por usar arquivos markdown você pode usar qualquer editor de texto
que você quiser. Eu uso o Visual Studio Code, mas você pode usar qualquer outro como o próprio bloco de notas,
o editor do GitHub, ou o Sublime Text.
* **É muito mais difícil você quebrar o seu site.** Por você conseguir gerenciar os templates, variáveis etc bem
mais facilmente do que o WordPress o seu blog fica bem mais em seu controle, o que facilita a manutenção nele e
prevenir que ele quebre.

## 4. Wordpress é um grande alvo para hackers.
Por vários sites no mundo inteiro serem feitos em WordPress, ele acaba sendo um grande alvo de ataques de todos os
tipos.

Jekyll, em contrapartida serve somente arquivos estáticos, então não haverá nenhum arquivo dinâmico que poderá
ser explorado por ataques hackers.

## 5. Jekyll é fácil para aprender.
Jekyll tem vários temas prontos e fáceis de se customizar em poucas linhas de código sem você precisar saber muito
mais do que simples html.

## Conclusão
Se você precisa de um blog simples sem necessidades de APIS, chamadas no back-end etc, você pode usar o jekyll tranquilamente, pois é uma ótima forma de desenvolver um blog sem complicações com somente alguns comandos.

Se você já tem um site feito em WordPress, talvez seja interessante você migra-lo para jekyll, porém tem que
analisar se as vantagens irão compensar seu esforço de migrar-lo para uma nova plataforma.
