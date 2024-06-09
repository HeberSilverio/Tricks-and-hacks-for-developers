# Bootstrap
Se trata de um framework para desenvolvimento de sites responsivos.
Possui uma vasta biblioteca de componentes que facilita e agiliza o desenvolvimento de páginas web

###  Sugestões de cursos no youtube
> Ricardo Maroquio <a href="https://www.youtube.com/playlist?list=PL0YuSuacUEWuJN3qb6NP15bzqd8w_oAj7">Curso de bootstrap 5</a> 
> Matheus Battisti <a href="https://youtube.com/playlist?list=PLnDvRpP8Bnexu5wvxogy6N49_S5Xk8Cze">Curso de bootstrap 5</a> 

##### Principais classes do bootstrap


##### Breakpoints 
|xs|sm|md|lg|xl|xxl|
|------------|------------|------------|------------|------------|------------|
|<576px|≥576px|≥768px|≥992px|≥1200px|≥1400px|
|Extra small|Small|Medium|Large|Extra large|Extra extra large|

    
##### Infixos de classe
```
O campo propriedade pode ser:

m - para usar margin;
p - para usar padding.
O campo lados pode ser:

t - para usar margin-top ou padding-top;
b - para usar margin-bottom ou padding-bottom;
l - para usar margin-left ou padding-left;
r - para usar margin-right ou padding-right;
x - para usar margem ou padding, tanto na esquerda quanto direita;
y - para usar margem ou padding, tanto na parte superior quanto na inferior;
Deixe o campo em branco, para usar margin ou padding em todos os quatro lados do elemento.
O campo tamanho pode ser:

0 - para remover o padding ou margin;
1 - para usar a margin ou padding com valor de $spacer * .25;
2 - para usar a margin ou padding com valor de $spacer * .5;
3 - para usar a margin ou padding com valor de $spacer;
4 - para usar a margin ou padding com valor de $spacer * 1.5;
5 - para usar a margin ou padding com valor de $spacer * 3;
auto - para usar a margin com valor de auto.
Ps: você pode adicionar mais tamanhos, colocando mais valores no mapa Sass $spacers.
```

|Class infix	|s|e|t|b|x|y|
|------|------|------|------|------|------|------|
||Esquerda|Direita|Topo|baixo|eixo x| eixo y|
|**Class infix**	|**m**|**p**|**col**||||
||margin|padding|coluna||||
|**0**|**1**|**2**|**3**|**4**|**5**|**auto**|
| 0 | .25 | .5 | 1 rem| 1.5 rem| 3 rem| auto|

##### Conteineres
|Classes| resultado|
|---|---|
|container||
|container-fluid| preenche todo espaço|
|container-{brekpoint}||

##### background
|Classe| resultado|
|--|--|
| txt-bg-dark| escuro|
|bg-dark||
|bg-opacity-50||
|bg-opacity-75||

##### Alinhamentos
|Classe| resultado|
|-------|-------|
|**Alinhamento** | **(align) eixo y**|
|class="row align-items-start" | *ao lado da row* (alinhamento y) alinharam no topo |
| align-items-center | *ao lado da row* (alinhamento y) centralizado |
| align-items-end | *ao lado da row* (alinhamento y) em no final|
|**aceita** | **breakpoints**|
|align-items-xxl-center| apenas no breakpoint xxl|
|**Alinhamento** | **(justify) eixo x**|
|class="row justify-items-start" | *ao lado da row* (alinhamento x) alinharam no topo |
| justify-items-center | *ao lado da row* (alinhamento x) centralizado |
| justify-items-end | *ao lado da row* (alinhamento x) em no final|
| justify-items-between | *ao lado da row* (alinhamento x) espaçamento entre as colunas|
| justify-items-around | *ao lado da row* (alinhamento x) entre as colunas, e nas extremidade metade das colunas |
| justify-items-evenly | *ao lado da row* (alinhamento x) espaçamento igual entre as colunas, e nas extremidade |
|**Alinha** | **Individualmente**|
| class="col-3 align-self-start" | em cada div (alinhamento y) em no topo |
| align-self-center | em cada div (alinhamento y) centralizado|
| align-self-end | em cada div (alinhamento y) em no final|
|**Ordem** | **Individualmente**|
| class="col-3 order-first" | ela fica na primeira posição |
| class="col-3 order-last" | ela fica na última posição |
| class="col-3 order-2" | ordens numeradas |

##### Margin Padding e Deslocamentos
| Classe  | Resultado |
| ------------- | ------------- |
| m-3  | colocar margem de 1 rem em todos os lados  |
| ms-3 | margem esquerda | 
| me-3 | margem direita |
| mt-3 | margem top |
| mb-3 | margem bottom |
| mx-3 | margin na direita e na esquerda (eixo x) |
| my-3 | margin no topo e bottom (eixo y) |
| ms-auto | margin esquerda usando todo o tamanho disponível à esquerda|
| mx-auto | margin automatica no eixo x|
| **Pode ser**  | **utilizado com breakpoints** |
| p-3  | coloca padding de 1 rem em todos os lados  |
| ps-3 | padding esquerda | 
| pe-3 | padding direita |
| pt-3 | padding top |
| pb-3 | padding bottom |
| px-3 | padding na direita e na esquerda (eixo x) |
| py-3 | padding no topo e bottom (eixo y) |
| **Deslocamento**  | **utilizado com breakpoints** |
| offset-1 | uma coluna deslocada para direita |
| offset-2 | duas coluna deslocada apartir da coluna anterior|

##### Classes para textos
| Comando                           | O que faz?                  | Observação                     |
| --------------------------------- | --------------------------- | ------------------------------------ |
| `class="lead"`                    | estiliza o paragrafo        | ![](https://i.imgur.com/PC0L07N.jpg) |
| `class="blockquote"`              | paragrafo de citação        | ![](https://i.imgur.com/PC0L07N.jpg) |

##### Estilização para lista
| Comando                           | O que faz?                  | Observação                     |
| --------------------------------- | --------------------------- | ------------------------------------ |
| `class="list-unstyled"`           | retira a estilização        | ![]() |
| `ul class="list-inline" li class="list-inline-item"`            | colocar (li)s em linha        | ![]() |