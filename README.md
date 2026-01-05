# MFD_ES
## 1. Introducción
Este repositorio contiene un diccionario léxico de Fundamentos Morales en español (MFD_ES). Cuenta con 1.972 palabras etiquetadas según su pertenencia a los distintos fundamentos morales y está orientado a análisis exploratorios de texto, procesamiento de lenguaje natural y estudios en psicología social y ciencias sociales en contextos de habla hispana.

El diccionario se construyó a partir de la exportación de los términos del *Moral Foundations Dictionary 2.0* (desarrollada por Filmer et al., 2019)a una hoja de cálculo. Las palabras fueron traducidas automáticamente mediante la función de Google Translator y, posteriormente, se realizó un proceso de depuración: las expresiones compuestas por más de una palabra fueron adaptadas a una sola forma léxica y se eliminaron términos repetidos .

## 2. Teoría de los Fundamentos Morales

La Teoría de los Fundamentos Morales (TFM) propone que el razonamiento moral humano se apoya principalmente en intuiciones automáticas y emocionales, más que en procesos puramente racionales (Graham et al., 2008). Desde esta perspectiva, los juicios morales cumplen una función social y estratégica, orientada a justificar acciones y coordinar vínculos sociales, y están moldeados por experiencias personales y normas culturales (Duhalde et al., 2025).

### Fundamentos morales

- **Cuidado / Daño**: se centra en la protección del bienestar ajeno y en la evitación del sufrimiento, la crueldad y el daño.
- **Equidad / Engaño**: refiere a la justicia, la reciprocidad y el trato justo, así como al rechazo del fraude y la injusticia.
- **Lealtad / Traición**: alude al sentido de pertenencia, compromiso y cooperación con el grupo propio, frente a la deslealtad o la traición.
- **Autoridad / Subversión**: implica el respeto por las jerarquías, las normas y la tradición, en contraposición a la desobediencia y el caos.
- **Santidad / Degradación**: se relaciona con la pureza física y moral, y la aversión hacia aquello percibido como impuro o degradante.

Estos fundamentos pueden agruparse en dos grandes dimensiones: los **Fundamentos Individualizantes** (Cuidado y Equidad), que priorizan el bienestar y los derechos individuales, y los **Fundamentos Vinculantes** (Lealtad, Autoridad y Santidad), que enfatizan la cohesión grupal, la tradición y el orden social (Roca et al., 2023).

### Diccionario de Fundamentos Morales

Los diccionarios de Fundamentos Morales permiten operacionalizar esta teoría en el análisis de textos, clasificando palabras según el fundamento moral que evocan. Cada fundamento se organiza en dos polos: **virtue** y **vice**. El polo *virtue* agrupa términos asociados a conductas valoradas positivamente, mientras que el polo *vice* incluye términos vinculados a su transgresión o ausencia. Ambos polos representan dimensiones complementarias de una misma preocupación moral.

### Ejemplos de fundamentos morales

| Fundamento | Virtue (ejemplos) | Vice (ejemplos) |
|----------|------------------|----------------|
| Cuidado | cuidar, ayudar, proteger | dañar, herir, sufrir |
| Equidad | justicia, igualdad, equidad | engaño, fraude, injusticia |
| Lealtad | lealtad, compromiso, unión | traición, deserción |
| Autoridad | respeto, obediencia, orden | subversión, desobediencia |
| Santidad | pureza, sagrado, limpio | degradación, impureza |




## 3. Ejemplo de uso

Como ejemplo ilustrativo del uso del diccionario MFD_ES, se analizaron discursos políticos de dos figuras históricas con perfiles ideológicos y retóricos contrastantes: Ernesto “Che” Guevara y Francisco Franco. Los textos fueron procesados mediante técnicas estándar de análisis de contenido —tokenización, eliminación de signos de puntuación y números y construcción de una matriz documento-término— y posteriormente se aplicó el diccionario de Fundamentos Morales para identificar la proporción de palabras asociadas a cada fundamento moral. Las frecuencias fueron normalizadas por la longitud total de los textos y los resultados se agregaron por personaje.

Los resultados muestran que, en ambos casos, el fundamento Cuidado/Daño presenta una alta proporción relativa, especialmente en su polo vice, lo que sugiere un énfasis discursivo en el sufrimiento, el daño y la denuncia de situaciones percibidas como injustas o violentas. Asimismo, se observa una presencia relevante del fundamento Lealtad, particularmente en su polo virtue, consistente con discursos orientados a la construcción de identidades colectivas, la cohesión grupal y el compromiso con una causa común. En el caso de Franco, los fundamentos Autoridad y Santidad exhiben proporciones relativamente más altas que en los textos de Guevara, lo que resulta congruente con un discurso que enfatiza el orden, la jerarquía y valores morales tradicionales.

Un contraste particularmente relevante aparece en el fundamento Equidad/Engaño. Los discursos del Che muestran una mayor proporción de términos asociados a este polo negativo —vinculados al engaño, la injusticia y la explotación— en comparación con los de Franco. Esta diferencia sugiere que el lenguaje moral del Che se apoya con mayor intensidad en la denuncia de violaciones a la equidad y en la crítica a relaciones sociales percibidas como injustas, mientras que en los textos de Franco este tipo de referencias ocupa un lugar menos central dentro de su repertorio moral explícito.

En conjunto, este ejemplo ilustra cómo MFD_ES permite identificar patrones diferenciales en el uso del lenguaje moral entre distintos actores políticos y contextos históricos. Si bien los resultados deben interpretarse de manera exploratoria y descriptiva, el diccionario se presenta como una herramienta útil para el análisis comparativo de discursos en español, facilitando la operacionalización empírica de la Teoría de los Fundamentos Morales en investigaciones de psicología social, ciencia política y estudios del discurso.

**Figura 1**
*Comparaciónde fundamentos morales según el Che Guevara y Franco*

<img width="388" height="248" alt="Rplot" src="https://github.com/user-attachments/assets/6fddf471-0e33-4e2b-b8da-c220975c1cff" />

## 4. Limitaciones
Una primera limitación de este diccionario es inherente a todo enfoque léxico: la detección de contenido moral se basa exclusivamente en la presencia de palabras aisladas, sin considerar el contexto sintáctico, pragmático o discursivo en el que aparecen. Esto implica que términos moralmente relevantes pueden ser utilizados de manera irónica, descriptiva o incluso crítica sin que el método pueda distinguir estos usos. Asimismo, el diccionario no capta construcciones morales implícitas ni razonamientos normativos complejos que no estén directamente asociados a las palabras incluidas, lo que puede llevar a subestimar ciertas expresiones morales presentes en los textos (Rizzole et al., 2025).

Una segunda limitación se relaciona con el proceso de traducción y adaptación lingüística (Cheng & Zhang, 2023). Aunque el diccionario se construyó a partir del MFD 2 y fue traducido de manera sistemática, las diferencias semánticas y culturales entre el inglés y el español pueden afectar la equivalencia conceptual de algunos términos. Además, el uso de una única forma por palabra puede dejar fuera variantes morfológicas o regionales del español. Futuras mejoras podrían incluir la validación empírica del diccionario en distintos países de habla hispana, la incorporación de lematización y expresiones multi-palabra, y la integración con enfoques basados en aprendizaje automático o modelos de lenguaje que permitan capturar el contexto y la estructura del discurso moral de manera más precisa.
## 5. Conclusión

El diccionario **MFD_ES** permite la operacionalización sistemática de la Teoría de los Fundamentos Morales en corpus en lengua española mediante un enfoque léxico basado en conteo y normalización de frecuencias. Su estructura, que distingue entre polos virtue y vice para cada fundamento, facilita análisis comparativos intra- e inter-grupales, así como la integración con flujos de trabajo estándar de análisis textual en R, particularmente a través de representaciones *bag-of-words* y *document-feature matrices*.

No obstante, los indicadores derivados del uso de MFD_ES deben interpretarse como medidas de saliencia léxica y no como inferencias directas sobre procesos cognitivos o juicios morales subyacentes. El enfoque diccionario-basado es sensible a la selección del corpus, a la longitud de los textos y a las decisiones de preprocesamiento, y no capta dependencias sintácticas, negaciones ni usos pragmáticos del lenguaje. En consecuencia, se recomienda utilizar **MFD_ES** como herramienta exploratoria o complementaria, junto con métodos contextuales (por ejemplo, modelos de tópicos, embeddings semánticos o análisis supervisados), con el objetivo de mejorar la validez interpretativa y la robustez de los análisis del discurso moral en español.
## 6. Referencias

Cheng, C. Y., & Zhang, W. (2023). C-mfd 2.0: Developing a chinese moral foundation dictionary. Computational Communication Research, 5(2), 1.https://doi.org/10.5117/CCR2023.2.10.CHEN

Duhalde, N. H. E., Roca, M. A., Jaume, L. C., Rodriguez, F. A., & Biglieri, J. (2025). Factores cognitivos y Morales del prejuicio y el punitivismo en el contexto argentino. In XVII Congreso Internacional de Investigación y Práctica Profesional en Psicología. XXXII Jornadas de Investigación XXI Encuentro de Investigadores en Psicología del MERCOSUR. VII Encuentro de Investigación de Terapia Ocupacional. VII Encuentro de Musicoterapia. Facultad de Psicología-Universidad de Buenos Aires. https://www.aacademica.org/000-004/787

Graham, J., Nosek, B. A., Haidt, J., Iyer, R., Spassena, K., & Ditto, P. H. (2011). Moral Foundations Questionnaire (MFQ) [Database record]. APA PsycTests.
https://doi.org/10.1037/t05651-000

Frimer, J. A., Boghrati, R., Haidt, J., Graham, J., & Dehgani, M. (2019). Moral Foundations Dictionary for Linguistic Analyses 2.0 https://provalisresearch.com/products/content-analysis-software/wordstat-dictionary/moral-foundations-dictionary/?utm_source=chatgpt.com

Rizzoli, V., Sarrica, M., Bobbio, A., Carraro, L., & Alparone, F. R. (2025). The Words of Morality: An Italian Adaptation of the Moral Foundations Dictionary 2.0 for the Linguistic Inquiry Word Count. Journal of Language and Social Psychology, 0261927X251386477.

Roca, M. A., Espósito Santamaría, A., Duhalde, N., Casella, F., & Jaume, L. C. (2023). Los fundamentos morales y su correlato religioso. Trabajo presentado en las XX Jornadas Internacionales de Investigación en Psicología UCES y XXII Jornadas Internacionales de Actualización del Algoritmo David Liberman, Universidad de Ciencias Empresariales y Sociales (UCES), Buenos Aires, Argentina. https://dspace.uces.edu.ar/jspui/handle/123456789/6942
