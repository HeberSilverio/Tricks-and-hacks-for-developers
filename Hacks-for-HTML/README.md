
#### Atalho para construção rápida de html


<p align="center">Hacks emmte</p>

| Comando                                                     | O que faz?                  | Observação                     |
| ----------------------------------------------------------- | --------------------------- | ------------------------------------ |
| `header+main+nav+aside`                                     | Cria um seções              |                                      |
| `div.text+div.text`                                         | Cria div e classes          |                                      |
| `p>lorem15`                                                 | Cria parágrafo com lorem    |                                      |
| `ul>li*5>lorem3`                                            | Cria lista com lorem        |                                      |
| `div.container>div.row>div.col-3{Coluna $}*3`               | veja imagem                 |![](https://i.imgur.com/Te2r2kk.jpg)  |
| `div.container>p.h${.h$ - Classe de Título de Nível $}*6`   | veja imagem                 |![](https://i.imgur.com/s3u3zx0.jpg)  |
| `div.container>h1.display-${Display $}*6   `                | 6 h1 com classe dinamicas   |![](https://i.imgur.com/uMRQTwt.jpg)  |
| `div.container>ul>li.icone-${$}*3`                          | 3 li com classes diferentes | ![](https://i.imgur.com/tsfyMWM.jpg)|
| `dl>(dt{termo $}+dd{Descrição do termo $})*5`               | lista de termo | ![](https://i.imgur.com/Xw8dAQa.jpg)|
| `p>lorem10`                                                 | paragrafo com dez palavras  | ![]()|
| Tags HTML mark,del,s,ins,u,small,strong,em                  | ![](https://i.imgur.com/lnv2vsd.jpg)  | ![](https://i.imgur.com/Mq59r5w.jpg)|
| `<figure>  <blockquote> <figcaption <cite> `               |  ![](https://i.imgur.com/ad4XhPR.jpg)  | ![](https://i.imgur.com/i4muOml.jpg)|
| ``                          |                         | ![]()|

###### Imagem de preview ao compartilhar link do site no whatsapp

Quando recebemos ou enviamos um link de um site (no whatsapp por exemplo), é gerado uma imagem de "preview" ou até mesmo a logo do site. Para adicionar no seu site adicione a seguinte linha de código no head do html da página:

    <meta property="og:image" content="url_da_imagem">
|  |  |
|-------|--------|
| Com isso seus links ficarão mais atraentes e chamativos! | ![Example](https://uploaddeimagens.com.br/images/004/650/354/thumb/image-link-compartilhavel.JPG?1698513036) |



#### Incluindo caracteres especiais em HTML
| Personagem literal | Equivalente de referência de caractere | -- |
|--------------------|--------------------------------------|--------------------|
| <                  | &lt;                                 | &amp;lt;           |
| >                  | &gt;                                 |
| "                  | &quot;                               |
| '                  | &apos;                               |
| &                  | &amp;                                |

| Personagem literal | Equivalente de referência de caractere |
|--------------------|--------------------------------------|
| <                  | &amp;lt;                             |
| >                  | &amp;gt;                             |
| "                  | &amp;quot;                           |
| '                  | &amp;apos;                           |
| &                  | &amp;amp;                            |