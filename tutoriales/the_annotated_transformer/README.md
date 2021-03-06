# "The Annotated Transformer" en Español

Traducción al español del notebook
["The Annotated Transformer" de Harvard NLP](https://nlp.seas.harvard.edu/2018/04/03/attention.html),
donde se explica e implementa el paper ["Attention Is All You Need"](https://export.arxiv.org/abs/1706.03762).

<img src="https://nlp.seas.harvard.edu/images/the-annotated-transformer_0_0.png" alt="logo" width="400"/>

## Objetivo
En primer lugar, nuestro objetivo es entender todas las piezas que componen la arquitectura Transformer. 
Para ello, vamos a explicar e implementar cada una de ellas:

- [ ] [Positional Encoding](https://github.com/mariagrandury/nlp-es-hugging-face/issues/3)
- [ ] [Multi-Head Attention](https://github.com/mariagrandury/nlp-es-hugging-face/issues/4)
- [ ] [Masked Multi-Head Attention](https://github.com/mariagrandury/nlp-es-hugging-face/issues/5)
- [ ] [Feed Forward](https://github.com/mariagrandury/nlp-es-hugging-face/issues/6)
- [ ] [Add & Norm](https://github.com/mariagrandury/nlp-es-hugging-face/issues/7)
- [ ] [Linear](https://github.com/mariagrandury/nlp-es-hugging-face/issues/8)
- [ ] [Softmax](https://github.com/mariagrandury/nlp-es-hugging-face/issues/9)

La implementación de estas piezas debe ser auto-contenida. Se pueden utilizar, por ejemplo, una entrada y una salida ficticias. 

Una vez comprendida la arquitectura Transformer, nuestra intención es replicar el tutorial original en español a diferentes niveles de abstracción:
- El nivel más bajo sería utilizando solo `numpy`
- El nivel intermedio sería utilizando frameworks como `pytorch` y `tensorflow`
- El nivel más alto sería utilizando la librería `transformers` de Hugging Face

## Cómo contribuir
Para facilitar la organización de las tareas y poder visualizar el avance del proyecto, este tutorial está asociado a un
[tablero](https://github.com/mariagrandury/nlp-es-hugging-face/projects/1).

Para contribuir al repositorio, primero clónalo y después crea una rama donde añadir tu aportación.

Para contribuir a la explicación de la arquitectura Transformer:
1. Elige una de las piezas de la arquitectura
2. Crea una rama llamada `the_annotated_transformer/<pieza>` 
(e.g. `the_annotated_transformer/positional_encoding`)
3. Añade tu implementación de la pieza correspondiente al notebook `arquitectura_transformer.ipynb`
4. Abre una Pull Request cuando hayas terminado y menciona el Issue correspondiente para que otro contribuyente pueda revisar tu aportación

Para contribuir a la traducción del tutorial:
1. Elige una de las secciones del notebook original y la librería con la que quieres trabajar
2. Crea una rama llamada `the_annotated_transformer/<libreria_utilizada>/<seccion>`
(e.g. `the_annotated_transformer/pytorch/model_architecture`)
3. Añade tu sección al notebook correspondiente (`the_annotated_transformer_<libreria>.ipynb`)
4. Abre una Pull Request cuando hayas terminado para que otro contribuyente pueda revisar la nueva sección
