# "The Annotated Transformer" en Español

Traducción al español del notebook
["The Annotated Transformer" de Harvard NLP](https://nlp.seas.harvard.edu/2018/04/03/attention.html),
donde se explica e implementa el paper ["Attention Is All You Need"](https://export.arxiv.org/abs/1706.03762).

<img src="https://nlp.seas.harvard.edu/images/the-annotated-transformer_0_0.png" alt="logo" width="400"/>

## Objetivo
En primer lugar entender cada una de las piezas que componen la arquitectura transfomers. 
Para ello lo ideal sería hacer una implementación de cada una de las piezas/cajas que lo componen:

- [ ] Positional encoding
- [ ] Multi-head attention
- [ ] Masked multi-head attention
- [ ] Feed Foward
- [ ] Add & Norm
- [ ] Linear 
- [ ] Softmax

La implementación y explicación de estas cajas/piezas deberían ser auto-contenidas, utilizando aunque sea una entrada ficticia y una salida ficticia. 

Finalmente nuestra intención es replicar el tutorial original en español a diferentes niveles de abstracción:
- El nivel más bajo sería utilizando solo `numpy`
- El nivel intermedio sería utilizando frameworks como `pytorch` y `tensorflow`
- El nivel más alto sería utilizando la librería `transformers` de Hugging Face

## Cómo contribuir
Para contribuir a este tutorial:
1. Elige una de las secciones del notebook original y la librería con la que quieres trabajar
2. Clona este repositorio
3. Crea una rama llamada `the_annotated_transformer/<libreria_utilizada>/<seccion>`
(e.g. `the_annotated_transformer/pytorch/model_architecture`)
4. Añade tu sección al notebook correspondiente
3. Abre una Pull Request cuando hayas terminado para que otro contribuyente pueda revisar la nueva sección
