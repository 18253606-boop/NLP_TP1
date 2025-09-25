\# Análisis de NLP \[Analisis de discursos presidenciales]



\## Descripción

Análisis de los contenidos del discurso presidencial a lo largo del tiempo: Podemos conocer los principales objetivos, intereses, preocupaciones y necesidades de la ciudadania y su evolucion a lo largo del tiempo a partir del contenido de los discursos? Estudio del contenido de los Mensajes Presidenciales de Apertura de Sesiones Ordinarias ante la Asamblea Legislativa Este discurso se produce una vez por año en ocasion de la apertura de las sesiones ordinarias a principio del año. Los textos se publican en la pagina del honorable congreso deliberante de la Nacion: https://www2.hcdn.gob.ar/secparl/dgral\_info\_parlamentaria/dip/documentos/mensajes\_presidenciales.html 

La fuente proviene de los documentos roducidos por el cuerpo de taquigrafos del congreso. 

He incluido los textos de los presidents a partir del retorno de la democracia 1984 hasta el 2025. Son 42 documentos en formato pdf. 

El mayor inconveniente fue el pasaje de esos textos en formato pdf a formato txt. Ya que habia varios caracteres que provocaban que la transcripcion ocasionara cortes de palabras y union de dos o mas palabras, en forma arbitraria. Lo intente con el codigo presente arriba, abriendolos con word y convirtiendolos con un conversor online I love PDF, y en todos los casos tuve el mismo problema. Por lo tanto opte por copiar y pegar uno a uno en el notepad. Esto me permitio verificar rapidamente si alguna palabra se copiaba con errores ya que el notepad los marcaba.



OBJETIVOS: Identificar las palabras y temas más recurrentes por año Analizar la evolución de su vocabulario relacionado a necesidades, problematicas intereses y preocupaciones de la ciudadania a lo largo del tiempo Encontrar cambios en los reclamos de la ciudadania en los aspectos mencionados, a partir de cambios en los patrones de los discursos. Visualizar estos hallazgos de manera comprensible.





\## Información del Corpus

\- Tipo \[MúsicaLiteraturaPeriodismoDigital]

\- Tamaño X textos, aproximadamente de 30kb a 100kb entre 5000 y 20000 palabras

\- Fuentes principales \[Listar las fuentes más importantes]

\- Período temporal 1984 a 2025

\- Criterios de selección: estos textos estan disponibles en version texto en formato pdf. Los anteriores a 1984 son fotografias de publicaciones en papel, con lo cual habria que preprocesarlos con ocr.  



\## Técnicas de NLP Aplicadas

\- Preprocesamiento de texto (limpieza, tokenización, stop words)

\- Análisis con Bag of Words (BoW) y TF-IDF

\- Análisis con Word Embeddings (spaCy)

\- \[Técnica complementaria aplicada POSSentimentNER] excedio mis conocimientos y tiempo para aplicar dicha tecnica.



\## Principales Hallazgos

\- apenas tuve el tiempo suficiente para analiarlo. Evaluando los contextos historicos de la epoca resultan llamativas y significativas algunas palabras mas frecuentes  y algunas similitudes entre discursos de distintos presidentes en cuanto a frecuencia de terminus y otras muy distintas acorde a las necesidades / demandas y problematicas.  



\## Tecnologías Utilizadas

\- Python 3.x

\- pandas, numpy

\- scikit-learn

\- spaCy

\- matplotlib, seaborn

\- \[Otras librerías específicas que hayas usado]



\## Instrucciones de Reproducción

1\. Clonar este repositorio

2\. Instalar dependencias `pip install -r requirements.txt`

3\. Ejecutar el notebook `jupyter notebook notebooksanalisis\_integrador.ipynb`



\## Limitaciones y Trabajo Futuro

\- \[Principal limitación encontrada]

\- \[Qué análisis te gustaría hacer en el futuro]



\## Autor

Carlos Sanchez - 18253606@ifts24.edu.ar

Trabajo Integrador - NLP - \[25-09-2025]

