# Traduciendo Géneros

## Resumen
A partir de una base de datos de subtítulos de películas vamos a transformar cualquier texto al estilo de un género cinematográfico específico. Utilizando técnicas de minería de datos, crearemos un modelo de cada género, que al ingresar un texto, el usuario puede seleccionar el género deseado y el programa reescribirá el contenido, adaptándolo al género elegido.

## Hipótesis de trabajo
Las formas de hablar y expresarse en cada género cinematográfico son tan características que se convierten en una marca distintiva del mismo. Por esta razón, es posible crear modelos que puedan traducir prácticamente cualquier contenido a un estilo propio de una categoría de película particular preservando el contenido. Esto nos permitiría adaptar diálogos, narrativas o incluso situaciones cotidianas al lenguaje y los códigos visuales que definen a cada tipo de cine.

## Objetivos preliminares
- **Desarrollo de un modelo específico para un género**: Construcción de un modelo de lenguaje especializado en capturar las características de un género en particular.
- **Extensión a múltiples géneros**: Expansión del enfoque para cubrir una variedad de géneros mediante el ajuste de modelos específicos para cada uno. Esto permitirá traducir cualquier texto a diversos estilos.
- **Análisis de errores y refinamiento del modelo**: Evaluación de los errores de adaptación entre géneros y de preservación del contenido de los subtítulos.

## Técnicas relevantes para aplicar
- Fine-tune para adaptar el modelo a las particularidades de cada género.
- Latent Dirichlet Allocation (LDA) para topic modeling.
- Semantic Textual Similarity (STS) para medir qué tan bien el contenido original se preserva durante la traducción entre géneros.

## Referencias
- [Semantic Textual Similarity (SBERT.net)](https://www.sbert.net/docs/sentence_transformer/usage/semantic_textual_similarity.html)
- [Movie Genre Prediction from Subtitles](https://github.com/pranav88/Movie-Genre-Prediction-from-Subtitles)
- [Content Representation and Similarity of Movies based on
Topic Extraction from Subtitles](https://kbogas.github.io/publ/setn_2016.pdf)

## Planificación
