## Objetivo
Esse notebook tem como objetivos apresentar as seguintes análises:

1. Quais países de origem do grão resultam na classificação mais alta?
2. A porcentagem ou ingredientes de cacau afetam a classificação?
3. Com classificações altas, quais são as características mais memoráveis?
4. Quais são os fabricantes com barras de chocolate altamente avaliadas ?

O dataset [Chocolate Bar Ratings](https://www.kaggle.com/datasets/evangower/chocolate-bar-ratings) está disponível no Kaggle e possui as seguintes características:

Sistema de classificação de sabor: <br>
4.0 - 5.0 = Outstanding <br>
3.5 - 3.9 = Highly Recommended <br>
3.0 - 3.49 = Recommended <br>
2.0 - 2.9 = Disappointing <br>
1.0 - 1.9 = Unpleasant

#### Informações Técnicas
Utilizou-se as seguintes bibliotecas:
```
import pandas as pd
import seaborn as sns
import numpy as np
from wordcloud import WordCloud, STOPWORDS, ImageColorGenerator
import matplotlib.pyplot as plt
```
Ferramentas e tecnologias:
<div align="center">
<img width="35" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" />
<img width="35" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original-wordmark.svg" />
<img width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" />
<img width="32" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
</div>

### Conclusão
**Quais países de origem do grão resultam na classificação mais alta?** 

*Na média de avaliações: Tobago, China, São Tomé & Príncipe, porém ao observar a participação percentual de produtores no mercado, os com classificação mais altas são: Madagascar, Venezuela e República Dominicana.*

<div align="center" style="display: inline_block">
  <img height="250" width="780" alt="origin_bean_absolute-barchart" src="images/origin_bean_absolute.png">
  <img height="250" width="780" alt="origin_bean_absolute-barchart" src="images/origin_bean_percentual.png">
</div>

**A porcentagem ou ingredientes de cacau afetam a classificação?**

*Não evidências suficientes que provem que a porcentagem de cacau ou o número de ingredientes afetem a classificação*

<div align="center" style="display: inline_block">
  <img height="450" width="520" alt="chocolate-corr" src="images/corr.png">
</div>

**Com classificações altas, quais são as características mais memoráveis?**

<div align="center" style="display: inline_block">
  <img height="250" width="520" alt="chocolate-wordcloud" src="images/wordcloud.png">
</div>

**Quais são os fabricantes com barras de chocolate altamente avaliadas ?**

*Na média de avaliações:Tobago Estate(Pralus), Heirloom Cacao Preservation (Zokoko), Ocelot, porém ao observar a participação percentual de fabricantes no mercado, os com classificação mais altas são: Soma, Arete e Bonnat.*

<div align="center" style="display: inline_block">
  <img height="250" width="780" alt="origin_bean_absolute-barchart" src="images/manufacturer_absolute.png">
  <img height="250" width="780" alt="origin_bean_absolute-barchart" src="images/manufacturer_percentual.png">
</div>

<br>
<br>

<div align="center"> 
Última Atualização: Dez/2022 <br> 
⭐ se você gostou !!
</div>
<div align="center" style="display: inline_block"><br>
  <img height="150" width="280" alt="willy-wonka" src="https://media2.giphy.com/media/d31uZkBBTy9zEVOM/giphy.gif?cid=790b76117d62f20d155acad850b849955716831c4c79b3bd&rid=giphy.gif&ct=g">
  <p><a href="https://giphy.com/gifs/musical-theater-charlie-and-the-chocolate-factory-d31uZkBBTy9zEVOM">via GIPHY</a></p>
</div>