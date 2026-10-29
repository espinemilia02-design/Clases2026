# Secuenciación: de las bases a los genomas

Clase para quinto semestre de biología molecular. Duración sugerida: 50 minutos.

## Entregables

- Secuenciacion_50min.pptx y PDF: 25 diapositivas de clase y 2 de bibliografía.
- Secuenciacion_50min_con_anexos.pptx y PDF: las mismas diapositivas con 6 anexos técnicos antes de la bibliografía final.
- Esta guía: cronograma, notas, cálculos y enlaces de consulta.

Todos los dibujos son originales y editables en PowerPoint. No se crearon en BioRender. Las gráficas y los números de los ejercicios son didácticos; no son resultados experimentales. Las diapositivas no muestran tiempos.

## Cronograma sugerido

| Diapositiva | Intervalo | Tema |
|---|---|---|
| 1 | 00–01 min | Secuenciación: de las bases a los genomas |
| 2 | 01–02 min | Tres generaciones; tres formas de observar ADN |
| 3 | 02–04 min | Sanger: detener cadenas y ordenar sus tamaños |
| 4 | 04–07 min | Illumina: añadir, fotografiar y volver a empezar |
| 5 | 07–09 min | Paired-end: dos extremos del mismo fragmento |
| 6 | 09–12 min | Nanopore: el ADN modifica una corriente |
| 7 | 12–13 min | PacBio HiFi: volver a mirar la misma molécula |
| 8 | 13–15 min | Illumina y Nanopore: elegir por el resultado |
| 9 | 15–17 min | Antes del kit: diseñar una comparación justa |
| 10 | 17–19 min | La muestra fija el techo de las lecturas |
| 11 | 19–21 min | Bibliotecas: misma muestra, preparaciones distintas |
| 12 | 21–23 min | Cálculo 1: pares de lecturas no son lecturas |
| 13 | 23–26 min | Cálculo 2: la cobertura pertenece a cada genoma |
| 14 | 26–28 min | Tres métricas que contestan preguntas distintas |
| 15 | 28–30 min | Estandarizar es controlar el proceso completo |
| 16 | 30–32 min | Un marcador y un metagenoma no entregan lo mismo |
| 17 | 32–34 min | Dos plataformas llegan a una pregunta común |
| 18 | 34–36 min | Una lectura larga puede cruzar una repetición |
| 19 | 36–38 min | Binning: agrupar contigs que podrían ser un genoma |
| 20 | 38–41 min | ¿Cuándo merece llamarse MAG de alta calidad? |
| 21 | 41–42 min | Asignar nombre y función sin prometer actividad |
| 22 | 42–44 min | Tus artículos: tres aplicaciones con contexto |
| 23 | 44–45 min | Actualización: posibilidades nuevas, validación local |
| 24 | 45–47 min | Tu turno: diseña el estudio de agua y sedimento |
| 25 | 47–48 min | La decisión técnica empieza y termina en la pregunta |
| 26 | 48–49 min | Referencias bibliográficas |
| 27 | 49–50 min | Referencias bibliográficas |

## Notas para explicar la clase

### 1. Secuenciación: de las bases a los genomas

Objetivos: explicar tres generaciones, elegir una plataforma por la pregunta y evaluar cómo se obtiene un MAG. Caso conductor: comparar comunidades de agua y sedimento. Pedir al grupo que distinga leer bases, identificar organismos y recuperar genomas.

Fuentes: [1–5,9–10] · Esquemas originales; datos y ejercicios didácticos.

### 2. Tres generaciones; tres formas de observar ADN

Las generaciones son una clasificación didáctica. Primera: Sanger. Segunda: lectura masiva de fragmentos, con Illumina como ejemplo actual. Tercera: molécula individual, con PacBio y Nanopore. 454 y SOLiD son antecedentes históricos. No hay una plataforma que sustituya a todas las otras para cualquier pregunta.

Fuentes: [1–3,18–19]

### 3. Sanger: detener cadenas y ordenar sus tamaños

Un primer inicia la síntesis. La incorporación de un ddNTP sin grupo 3′-OH detiene la cadena; separar los fragmentos por tamaño permite ordenar las bases. El esquema muestra la versión de lectura fluorescente capilar. Aplicaciones: regiones específicas, clones y confirmación de variantes. Una mezcla de amplicones dificulta la lectura.

Fuentes: [1,19]

### 4. Illumina: añadir, fotografiar y volver a empezar

Las moléculas adaptadas se unen a una flow cell y generan clusters. En SBS se incorpora una base con bloqueo reversible, se detecta la señal y se elimina el bloqueo para continuar. El mecanismo de clusters y el número de canales ópticos dependen del instrumento. Los cuatro colores son un dibujo conceptual, no una codificación universal.

Fuentes: [2–3,15]

### 5. Paired-end: dos extremos del mismo fragmento

Con un inserto de 500 pb, PE150 lee 150 pb desde cada extremo; quedan 200 pb sin leer entre ambos. Se obtienen 300 bases nominales por par, no una lectura continua de 300 pb. Los índices identifican muestras y no forman parte del inserto. UDI ayuda a reconocer combinaciones no válidas por index hopping; no elimina toda contaminación.

Fuentes: [15–16]

### 6. Nanopore: el ADN modifica una corriente

Un motor controla el paso de ADN por un poro. La corriente depende del contexto de varias bases y el basecaller infiere la secuencia a partir de la señal temporal. Conservar POD5 permite revisar modelos y modificaciones. La longitud depende de la integridad del ADN. Usar modelos compatibles con química, tipo de molécula y objetivo.

Fuentes: [4–5,17]

### 7. PacBio HiFi: volver a mirar la misma molécula

Una plantilla SMRTbell permite observar varias pasadas de una misma molécula. CCS combina observaciones para producir una lectura HiFi. No se trata de PCR. No equiparar precisión de lectura bruta, precisión de lectura por consenso y precisión del ensamblaje final.

Fuentes: [18]

### 8. Illumina y Nanopore: elegir por el resultado

La comparación se hace por objetivo, bases útiles, longitud, exactitud y costo total con cómputo. Illumina ofrece datos cortos para perfiles y variantes con diseños adecuados. Nanopore facilita contexto largo y análisis durante la corrida. Los rendimientos y errores no son propiedades fijas de una generación: declarar instrumento, química y modelo.

Fuentes: [4–5,9–10,15–18]

### 9. Antes del kit: diseñar una comparación justa

Las tres muestras por sitio son un ejemplo, no un cálculo de tamaño muestral. Definir unidad biológica, confusores y metadatos. Balancear condiciones entre extracciones y corridas; no poner todo A en un lote y B en otro. Repetir bibliotecas de una sola muestra mide variación técnica, no variación biológica.

Fuentes: [10,14]

### 10. La muestra fija el techo de las lecturas

La lisis debe representar la comunidad sin destruir la longitud necesaria. En ADN de alto peso molecular, una lisis suave puede perder organismos resistentes; una lisis agresiva puede fragmentar. Medir masa por fluorometría, tamaño por gel o electroforesis e inhibición con un ensayo compatible. Absorbancia sola no demuestra ausencia de inhibidores.

Fuentes: [4,8,14]

### 11. Bibliotecas: misma muestra, preparaciones distintas

Illumina puede usar tagmentación o fragmentación y ligación; controlar inserto, adaptadores, índices y PCR cuando exista. Nanopore puede usar ligación o una preparación rápida; la elección afecta longitudes y entradas. Para modificaciones nativas, comprobar la compatibilidad del ensayo: una amplificación copia bases y pierde esa información original.

Fuentes: [4–5,15–18]

### 12. Cálculo 1: pares de lecturas no son lecturas

Diez millones de pares contienen veinte millones de lecturas. PE150 aporta 300 bases por par: 10^7 × 300 = 3 × 10^9 bases = 3 Gb nominales, sin contar índices. Si se supone 80 % de bases útiles, quedan 2,4 Gb. Ese porcentaje es del ejemplo y se debe medir en el piloto.

Fuentes: [15] · Ejemplo didáctico PE150.

### 13. Cálculo 2: la cobertura pertenece a cada genoma

Modelo de planificación: C_i ≈ B × a_i / G_i. B son bases útiles de la comunidad; a_i es fracción de bases atribuida a la especie, no necesariamente fracción de células; G_i es tamaño de su genoma. Con 30 Gb, a=0,001 y G=4 Mb resulta 7,5×. Llegar a 30× ideales requeriría 120 Gb útiles. Extracción, heterogeneidad de cepas y cobertura desigual pueden impedir recuperar un MAG.

Fuentes: [7–10] · Modelo idealizado para diseño.

### 14. Tres métricas que contestan preguntas distintas

Q=-10 log10(p). Q30 equivale a error nominal por base de 0,1 %; comprobar la calibración con evidencia observada. N50 resume continuidad, no exactitud: contigs de 10, 8 y 2 kb suman 20 kb y su N50 es 10 kb. Distinguir N50 de lecturas y de contigs. Reportar profundidad media y amplitud cubierta.

Fuentes: [4,10–12,17]

### 15. Estandarizar es controlar el proceso completo

Construir la SOP a partir de un piloto representativo. Definir controles y criterios antes de procesar toda la cohorte. Un mock celular prueba extracción y etapas posteriores; un mock de ADN no evalúa lisis. El blanco acompaña la extracción. Una réplica técnica mide repetibilidad. Registrar versiones de protocolo, química, modelos, software y bases de datos; verificar desempeño después de cambios.

Fuentes: [11,14–17]

### 16. Un marcador y un metagenoma no entregan lo mismo

16S e ITS son marcadores amplificados y sujetos a sesgos de primers y copias por genoma. Leer 16S completo con Nanopore sigue siendo un estudio de marcador. Shotgun estudia ADN comunitario y permite observar genes y recuperar MAGs si hay datos suficientes. Inferir funciones desde un marcador no equivale a observar esos genes; ADN tampoco demuestra actividad.

Fuentes: [2,7–10]

### 17. Dos plataformas llegan a una pregunta común

Illumina parte de demultiplexado y FASTQ R1/R2. Nanopore parte de señal y basecalling; conservar BAM si se necesitan etiquetas de modificaciones y extraer FASTQ cuando corresponda. Hacer QC, retirar adaptadores y evaluar hospedero. Separar perfil basado en lecturas de ensamblaje y binning. Versionar bases de datos, parámetros, contenedores y registros de ejecución.

Fuentes: [4,7–10,17]

### 18. Una lectura larga puede cruzar una repetición

Una lectura larga puede atravesar una repetición y unir sus flancos únicos. Las lecturas cortas pueden aportar profundidad o corrección; una estrategia híbrida no siempre es necesaria. Elegir ensamblador y pulido compatibles con los datos. Comprobar que no se mezclaron cepas ni se introdujeron cambios incorrectos. Longitud y circularidad por sí solas no validan el resultado.

Fuentes: [7–10]

### 19. Binning: agrupar contigs que podrían ser un genoma

El binning usa composición y cobertura, a menudo entre varias muestras, para agrupar contigs. El gráfico de GC/cobertura ilustra las señales y no representa el algoritmo completo. Genomas próximos, cepas y elementos móviles pueden mezclarse o quedar fuera. Refinar y evaluar la coherencia antes de asignar una categoría de MAG.

Fuentes: [7–9,11–13]

### 20. ¿Cuándo merece llamarse MAG de alta calidad?

MIMAG para borradores HQ de bacterias y arqueas: completitud >90 %, contaminación <5 %, genes rRNA 23S, 16S y 5S y al menos 18 tRNA que representen 18 aminoácidos. La categoría media requiere completitud ≥50 % y contaminación <10 %. CheckM2 estima calidad; GUNC aporta otra evaluación de quimerismo. Revisar además alineamientos y contigs. No aplicar estos umbrales bacterianos directamente a virus.

Fuentes: [11–13]

### 21. Asignar nombre y función sin prometer actividad

Dereplicar evita contar genomas redundantes; declarar umbrales. La taxonomía y anotación dependen de la base de datos y su versión. Un gen no encontrado en un MAG incompleto puede no haberse recuperado. Para abundancia, remapear y revisar lecturas ambiguas; los datos son composicionales. Genes de resistencia requieren contexto y controles, y no prueban por sí solos resistencia fenotípica.

Fuentes: [7–13]

### 22. Tus artículos: tres aplicaciones con contexto

Greninger 2015 es una prueba histórica de identificación viral durante adquisición de datos: no trasladar sus tiempos ni errores a equipos actuales. Singleton 2021 recuperó 1 083 MAGs HQ de 23 plantas de tratamiento y conectó genomas con otra evidencia funcional. Liew 2024 aplicó ensamblaje híbrido a biofilms termales. Usar MIMAG original: el artículo de 2024 simplifica incorrectamente HQ como >80 % y asocia Q20 con un error que no coincide con la definición nominal.

Fuentes: [6–8]

### 23. Actualización: posibilidades nuevas, validación local

Sereika 2025 empleó lecturas largas profundas en 154 muestras de suelo y sedimento para ampliar el catálogo de diversidad. Visci 2026 comparó tres plataformas en un mock de 20 especies: la cobertura, errores y ensamblador cambiaron los resultados. Un mock uniforme no reproduce toda la complejidad ambiental. Comparar la química y los datos realmente utilizados, que pueden preceder al año de publicación.

Fuentes: [9–10]

### 24. Tu turno: diseña el estudio de agua y sedimento

Actividad: comparar genes de resistencia y reconstruir genomas exige shotgun; 16S por sí solo no resuelve esos objetivos. Proponer réplicas biológicas, blanco, mock y piloto. Una especie al 0,1 % de las bases con genoma de 4 Mb recibe 7,5× de cobertura media ideal con 30 Gb útiles. Para continuidad considerar Nanopore con ADN adecuado o una combinación; no prometer MAG HQ por escoger una marca.

Fuentes: Cálculo didáctico · síntesis de [7–17].

### 25. La decisión técnica empieza y termina en la pregunta

Cerrar con tres decisiones: qué inferencia interesa, qué datos y controles exige y cómo se verificará. La comparación de plataformas tiene sentido solo bajo un diseño concreto. Los anexos guardan cálculos y criterios para revisar fuera de la sesión. Bibliografía al final.

Fuentes: [4,9–18]

### 26. Referencias bibliográficas

Bibliografía de fundamentos y ocho artículos compartidos. Varias editoriales limitaron el acceso: se contrastaron títulos, DOI y resúmenes indexados cuando el texto completo no estaba disponible. No se reproduce material gráfico editorial: todos los esquemas son originales.

Fuentes: Enlaces DOI y documentación completos en la guía docente.

### 27. Referencias bibliográficas

Referencias recientes de 2025 y 2026, normas de calidad y documentación oficial. La fecha de consulta es 28 de octubre de 2026. Las páginas latest cambian: al ejecutar un análisis real se debe fijar la versión concreta, el modelo y las bases de datos.

Fuentes: Enlaces DOI y documentación completos en la guía docente.

## Anexos técnicos de consulta

### Anexo 1. Anexo: convertir masa en moléculas de biblioteca

Para ADN de doble hebra: nM = concentración en ng/µL × 10^6 / (660 × longitud en pb). Una biblioteca de 10 ng/µL y 500 pb totales tiene 30,3 nM. Para 20 µL a 4 nM, tomar 2,64 µL y completar con 17,36 µL. Incluir adaptadores en la longitud. No trasladar la fórmula sin ajuste a RNA o ADN monocatenario ni confundir fluorometría total con moléculas amplificables.

### Anexo 2. Anexo: qué registrar en una corrida Nanopore

Registrar flow cell, química, kit, barcodes, tratamiento de ADN, software y nombre completo del modelo. Simplex observa una hebra; duplex combina hebras de la misma molécula cuando se recuperan ambas de forma compatible. No es paired-end de Illumina. La fracción duplex afecta el rendimiento. Los programas históricos de un artículo no deben adoptarse automáticamente. Muestreo adaptativo permite rechazar moléculas durante la corrida; validar recuperación y sesgo.

### Anexo 3. Anexo: criterios de aceptación antes de producir datos

Esta es una plantilla, no un conjunto de umbrales universales. Definir en un piloto la masa útil, integridad, inhibición, tamaño de biblioteca, rendimiento y calidad necesarios para la pregunta. Comparar blancos y mock antes de interpretar señales pequeñas. Un cambio de kit o modelo exige verificar de nuevo el desempeño pertinente. Preservar los resultados de todos los controles.

### Anexo 4. Anexo: ejemplos de herramientas por etapa

Las herramientas son ejemplos de etapas, no un pipeline obligatorio ni un ranking actualizado. Versionar código y bases de datos. Ajustar ensamblador a lecturas cortas o largas; aprovechar coberturas por muestra en binning. Validar métodos de perfiles para el tipo de lectura y comunidad. Los modelos de abundancia de lecturas cortas no deben aplicarse automáticamente a longitudes Nanopore variables.

### Anexo 5. Anexo: N50, completitud y contaminación

N50 no prueba exactitud. Un MAG con estimaciones 95 % de completitud y 2 % de contaminación necesita además rRNA y tRNA para HQ según MIMAG. Ausencia de un gen en un borrador incompleto no demuestra ausencia biológica. Circularidad no verifica pertenencia, contaminación ni precisión de bases. Las métricas deben interpretarse juntas.

### Anexo 6. Anexo: ampliación del caso y respuestas

Si B=30 Gb ya excluye hospedero y datos descartados, la cobertura del caso es 7,5×. Si son 30 Gb brutas, 80 % pasa QC y solo 10 % de las bases restantes es microbiano, B=2,4 Gb de la comunidad y C=0,6×. Declarar siempre los denominadores y no descontar dos veces hospedero o pérdidas. Añadir más lectura puede ayudar, pero no corrige por sí sola sesgos de extracción.

## Respuestas y cálculos para comprobar

- PE150: 10 millones de pares × 2 lecturas/par × 150 bases/lectura = 3 Gb nominales. Con un supuesto de 80 % de bases útiles: 2,4 Gb. No contar índices como bases del inserto.
- Cobertura de una especie: B × a / G. Con 30 Gb útiles, a=0,001 y G=4 Mb, C≈7,5×; para 30× ideales se requerirían 120 Gb útiles bajo los mismos supuestos.
- Si 30 Gb son brutas, pasa 80 % por QC y 10 % de las bases restantes es de la comunidad microbiana: B=2,4 Gb y C≈0,6×.
- Biblioteca ADN ds de 10 ng/µL y 500 pb totales: ≈30,3 nM. Para 20 µL a 4 nM: 2,64 µL de biblioteca + 17,36 µL de diluyente.
- N50 para contigs 10, 8 y 2 kb: total 20 kb, el umbral del 50 % es 10 kb, N50=10 kb.
- Q30 implica p=10^(−3)=0,001 (0,1 % de error nominal por base); Q20 implica p=0,01 (1 %). Verificar calidad observada, sin equiparar lectura y consenso.

## Bibliografía con enlaces

1. McGinn S, Gut IG (2013). DNA sequencing—spanning the generations. New Biotechnol 30:366–372. [Consultar fuente](https://doi.org/10.1016/j.nbt.2012.11.012).

2. Morozova O, Marra MA (2008). Applications of next-generation sequencing technologies in functional genomics. Genomics 92:255–264. [Consultar fuente](https://doi.org/10.1016/j.ygeno.2008.07.001).

3. Su Z et al. (2011). Next-generation sequencing and its applications in molecular diagnostics. Expert Rev Mol Diagn 11:333–343. [Consultar fuente](https://doi.org/10.1586/erm.11.3).

4. Wang Y et al. (2021). Nanopore sequencing technology, bioinformatics and applications. Nat Biotechnol 39:1348–1365. [Consultar fuente](https://doi.org/10.1038/s41587-021-01108-x).

5. Zheng P et al. (2023). Nanopore sequencing technology and its applications. MedComm 4:e316. [Consultar fuente](https://doi.org/10.1002/mco2.316).

6. Greninger AL et al. (2015). Rapid metagenomic identification of viral pathogens in clinical samples by real-time nanopore sequencing analysis. Genome Med 7:99. [Consultar fuente](https://doi.org/10.1186/s13073-015-0220-9).

7. Singleton CM et al. (2021). Connecting structure to function with the recovery of over 1000 high-quality metagenome-assembled genomes from activated sludge using long-read sequencing. Nat Commun 12:2009. [Consultar fuente](https://doi.org/10.1038/s41467-021-22203-2).

8. Liew KJ et al. (2024). Integrating multi-platform assembly to recover MAGs from hot spring biofilms: insights into microbial diversity, biofilm formation, and carbohydrate degradation. Environ Microbiome 19:29. [Consultar fuente](https://doi.org/10.1186/s40793-024-00572-7).

9. Sereika M et al. (2025). Genome-resolved long-read sequencing expands known microbial diversity across terrestrial habitats. Nat Microbiol 10:2018–2030. [Consultar fuente](https://doi.org/10.1038/s41564-025-02062-z).

10. Visci G et al. (2026). Benchmarking short- and long-read sequencing technologies for metagenomic profiling of microbiomes. Sci Rep 16:22610. [Consultar fuente](https://doi.org/10.1038/s41598-026-49725-3).

11. Bowers RM et al. (2017). Minimum information about a single amplified genome (MISAG) and a metagenome-assembled genome (MIMAG) of bacteria and archaea. Nat Biotechnol 35:725–731. [Consultar fuente](https://doi.org/10.1038/nbt.3893).

12. Chklovski A et al. (2023). CheckM2: a rapid, scalable and accurate tool for assessing microbial genome quality using machine learning. Nat Methods 20:1203–1212. [Consultar fuente](https://doi.org/10.1038/s41592-023-01940-w).

13. Orakov A et al. (2021). GUNC: detection of chimerism and contamination in prokaryotic genomes. Genome Biol 22:178. [Consultar fuente](https://doi.org/10.1186/s13059-021-02393-0).

14. Costea PI et al. (2017). Towards standards for human fecal sample processing in metagenomic studies. Nat Biotechnol 35:1069–1076. [Consultar fuente](https://doi.org/10.1038/nbt.3960).

15. Illumina. Documentación técnica. Sequencing technology: sequencing by synthesis. Consulta: 28-10-2026. [Consultar fuente](https://www.illumina.com/science/technology/next-generation-sequencing/sequencing-technology.html).

16. Illumina. Documentación técnica. Unique dual indexes y asignación de muestras. Consulta: 28-10-2026. [Consultar fuente](https://supportassets.illumina.com/techniques/sequencing/ngs-library-prep/multiplexing/unique-dual-indexes.html).

17. Oxford Nanopore Technologies. Dorado: basecalling, modelos y duplex. Consulta: 28-10-2026. [Consultar fuente](https://software-docs.nanoporetech.com/dorado/latest/).

18. PacBio. Documentación técnica. How HiFi sequencing works. Consulta: 28-10-2026. [Consultar fuente](https://www.pacb.com/technology/hifi-sequencing/how-it-works/).

19. Sanger F, Nicklen S, Coulson AR (1977). DNA sequencing with chain-terminating inhibitors. PNAS 74:5463–5467. [Consultar fuente](https://doi.org/10.1073/pnas.74.12.5463).

## Fuentes técnicas complementarias para ampliar Nanopore

- [ONT: guía de muestreo adaptativo](https://nanoporetech.com/document/adaptive-sampling). Permite aceptar o rechazar moléculas durante la corrida; evaluar ganancia útil y sesgo.
- [ONT: preparación de bibliotecas RNA](https://nanoporetech.com/products/prepare/rna-library-preparation/). Distinguir RNA nativo de cDNA y decidir si interesa preservar modificaciones.

## Alcance de la consulta y lectura crítica

Se verificaron títulos y DOI de los ocho artículos enlazados. En ScienceDirect, Taylor & Francis y algunos accesos Nature, la consulta se apoyó en resúmenes y registros PubMed cuando el texto completo no estuvo disponible. Se revisó contenido accesible de los trabajos de Greninger y Liew, resúmenes y registros del trabajo de Singleton, y las publicaciones recientes de Sereika (2025) y Visci (2026), además de fuentes originales de estándares y documentación técnica oficial. El enlace de Google Books con ID YsskBAAAQBAJ no permitió confirmar de forma fiable título, edición o contenido; no se le atribuyen afirmaciones ni se inventa una referencia bibliográfica.

Para MIMAG se usa Bowers et al., no la simplificación de umbral HQ >80 % que aparece en el trabajo de biofilms de 2024. También se distingue Q20 (1 % nominal por base) de una afirmación de error <5 %. No trasladar químicos, algoritmos o tiempos de artículos históricos como recomendaciones actuales. La fecha de consulta es 28 de octubre de 2026; las páginas de documentación latest deben convertirse en versiones fijadas al ejecutar un análisis real.

## Glosario breve

- **Read / lectura:** secuencia observada de una molécula o cluster.
- **Paired-end:** lectura de los dos extremos de un mismo fragmento.
- **Contig:** secuencia continua propuesta por ensamblaje.
- **Bin:** conjunto de contigs agrupados por señales compatibles.
- **MAG:** genoma reconstruido desde un metagenoma y evaluado según criterios declarados.
- **Completeness / completitud:** estimación de fracción del genoma recuperada.
- **Contaminación:** estimación de secuencias ajenas al genoma objetivo; no equivale al número de lecturas del blanco.
- **HQ / MQ:** categorías de borrador de alta y mediana calidad según criterios reportados.
- **SOP:** procedimiento operativo estandarizado y versionado.
- **UDI:** combinación de índices duales únicos para identificar bibliotecas.
- **HMW:** ADN de alto peso molecular.
- **POD5:** archivo de señal Nanopore.
- **Basecaller:** modelo que infiere bases y calidades a partir de señal.
