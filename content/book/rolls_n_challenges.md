---
title: "Rolagens e Desafios"
weight: 2
---

## Rolagem de dados

Por padrão a rolagem de dados tem como base dados de 6 lados. Considere que sempre que aparecer uma número seguido da letra mínuscula "d" significa uma rolagem de dados de 6 lados.

Ex¹.: "2d" equivale à "dois dados de seis lados".

Ex².: "4d" equivale à "quatro dados de seis lados".

## Desafios (Rolagem de Teste)

Sempre que um jogador decidir que seu personagem realizará uma ação cuja a falha seja relevante para a narrativa construida pelo mestre do jogo, ele deverá realizar um *Rolagem de Teste* (RT) com dados contra a *Rolagem Dificuldade* (RD) do **DESAFIO**.

O teste do Desafio é feito da seguinte forma:
1. A RD do **Desafio** é estabelecida pelo mestre de antemão e é representada por valores fixos e uma rolagem de dados. Sendo então rolada.

2. Para o desafio o personagem soma o valor do **Verbo** utilizado na descrição da ação com o **Talento** relacionado à mesma ação, e o resultado representa a quantidade de dados que serão rolados pelo jogador.

3. Compare o dado mais alto do jogador com o dado mais alto do **Desafio** (Sendo o dado fixo ou não). Se o dado do jogador for maior, adicione-o ao *Valor Resultado* (VR), se for menor ou igual descarte o dado. Repita então o processo com o próximo par de dados até que não seja mais possível comparar.

4. Quaisquer dados restantes do Jogador são somados ao VR e dados restantes do **Desafio** são deduzidos do VR.

5. Se o VR for superior ao *Valor Dificuldade* (VD) a ação do jogador é bem sucedida. Se não, a ação falha.

6. Além disso, para cada Multiplo de VD que seu VR ultrapassa além do primeiro o jogador ganha uma **Ampliação** em seu resultado.

> Calculo das ampliações:
> $$ \lfloor\dfrac{VD}{VR}\rfloor -1 $$ 

### Exemplos de desafios

> *João (Mestre), Maria e André estão jogando uma sessão de DICEPUNK e os personagens de Maria e André encontram uma porta de castelo trancada*
>
> **JOÃO:** *Ok, o que vocês fazem?*
>
> **ANDRÉ:** *Eu tento derrubar a porta com um Chute*
>
> **MARIA:** *Aff, ok...*
>
> **JOÃO:** *Certo, para derrubar a porta no chute pode ser LUTAR ou FORÇAR*
>
> **ANDRÉ:** *Meu FORÇAR é maior*
>
> **JOÃO:** *Tudo bem, vou rolar o desafio da porta*
>
> *A Rolagem Dificuldade (RD) da porta é [5 5 4d] ou seja [5 5] como valores fixos e uma rolagem de 4d, com Valor Dificuldade (VD) de 6*
>
> *João rola os 4 dados e como resultado obtem [6 3 3 1]. então o resultado da RD é [5 5] + [6 3 3 1] = [6 5 5 3 3 1];*
>
> **JOÃO:** *Pode rolar ANDRÉ*
>
> *O personagem de André tem CORPO 2 e FORÇAR 3 totalizando uma Rolagem de Teste (RT) de (2+3)d ou 5d*
>
> *André rola os 5 dados e como resultado da RT obtem [5 4 4 4 2];*
>
> *As comparações são as seguintes: [**6**:5] [**5**:4] [**5**:4] [3:**4**] [**3**:2] [**1**:-] ;*
>
> *As comparações em que os dados de André são menores descartam seus dados. [**6**:5] [**5**:4] [**5**:4] [**3**:2] [**1**:-] ;*
>
> *As comparações em que os dados de André são maiores somam o Valor Resultado (VR) de André. [3:**4**]. Logo o VR é 4*
>
> *Por fim compara-se o VR 4 de André contra o Valor Dificuldade (VD) 6 da porta, Resultado: Falha.*
>
> **ANDRÉ:** *Droga...*
>
> **MARIA:** *Sabia!*
>
> **JOÃO:** *Você faz um jogo de corpo contra a porta, mas ela é resistênte demais, é feita para resistir a ataques e cercos.*
>
> **MARIA:** *Ok, então eu vou pegar minhas ferramentas e destrancar a porta*
>
> **JOÃO:** *Hmm.. Ok, sem muitas opções, tem que ser ROUBAR*
>
> **MARIA:** *Sem problemas, sou uma ladra profissional*
>
> *Novamente João rola a Rolagem Dificuldade (RD) da porta (5 5 4d) e como resultado nos dados obtem [5 4 3 2]. então o resultado da RD é [5 5] + [5 4 3 2] = [5 5 5 4 3 2];*
>
> *O personagem de Maria tem Manha 3 e ROUBAR 5 totalizando uma Rolagem de Teste (RT) de (3+5)d ou 8d*
>
> *Maria rola os 8 dados e como resultado da RT obtem [6 6 5 5 4 3 1 1];*
>
> *As comparações são as seguintes: [5:**6**] [5:**6**] [**5**:5] [4:**5**] [3:**4**] [2:**3**] [-:**1**] [-:**1**];*
>
> *Maria descarta apenas um dado: [**5**:5];*
>
> *Todos os demais dados somam o VR de Maria: 6 + 6 + 5 + 4 + 3 + 1 + 1 = 26!*
>
> *Então Maria tem 26 contra o VD da Porta que é 6.*
>
> *O calculo de ampliações é feito pela quociente inteiro da divisão entre VR e VD menos um:*
>
> *$$ \lfloor\dfrac{VD}{VR}\rfloor -1 = \lfloor\dfrac{26}{6}\rfloor -1 $$*
>
> *Resultado de Maria: Sucesso + 3 ampliações.*