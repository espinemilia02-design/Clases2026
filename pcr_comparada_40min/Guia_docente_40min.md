# PCR comparada · clase de 40 minutos

20 diapositivas principales + 24 de consulta. El PowerPoint incluye ambos bloques; el PDF breve contiene solo la clase. Figuras originales editables, de estilo científico vectorial; no generadas en BioRender. Datos y curvas ilustrativos.

## Plan de clase

| Diapositiva | Tiempo | Contenido |
|---|---|---|
| 1 | 00–01 min | PCR: de una muestra a una decisión |
| 2 | 01–03 min | Los nombres describen ejes diferentes |
| 3 | 03–04 min | Un ciclo: separar, reconocer, copiar |
| 4 | 04–06 min | La calidad empieza antes del termociclador |
| 5 | 06–08 min | Los controles explican un resultado negativo |
| 6 | 08–10 min | Los primers delimitan lo que podrás observar |
| 7 | 10–13 min | Receta base: PCR convencional en 25 µL |
| 8 | 13–14 min | PCR convencional: ¿hay un producto del tamaño esperado? |
| 9 | 14–16 min | RT-PCR: convertir ARN en un molde amplificable |
| 10 | 16–18 min | qPCR: leer la amplificación mientras ocurre |
| 11 | 18–20 min | Cuantificar con una curva estándar |
| 12 | 20–22 min | Expresión relativa: comparar contra una referencia |
| 13 | 22–24 min | PCR digital: contar particiones y corregir ocupación |
| 14 | 24–27 min | De particiones positivas a copias en el extracto |
| 15 | 27–29 min | Comparación central: elegir por la pregunta |
| 16 | 29–31 min | Sanger: partir de un amplicón único y limpio |
| 17 | 31–33 min | NGS de amplicones: enriquecer, indexar, agrupar |
| 18 | 33–35 min | RNA-seq y variantes: dónde encaja cada PCR |
| 19 | 35–39 min | Caso integrador: una muestra, tres preguntas |
| 20 | 39–40 min | Respuestas y comprobación de aprendizaje |

## Notas por diapositiva

### 1. PCR: de una muestra a una decisión

Ruta de 40 minutos con anexos para lectura y práctica fuera de clase. Esquemas originales, no elaborados en BioRender. Todas las curvas y datos numéricos son didácticos, no resultados experimentales.

Fuentes: Base: Orlando 1998 [1]; Bustin y Mueller 2005 [2]; Zhu et al. 2020 [3]; Trouchet et al. 2025 [4].

### 2. Los nombres describen ejes diferentes

RT-PCR = PCR con transcripción reversa; no significa real-time. En esta presentación usamos RT-qPCR para ARN cuantificado en tiempo real. Nested, multiplex y hot-start pueden combinarse con otros formatos.

Fuentes: [2–4].

### 3. Un ciclo: separar, reconocer, copiar

Temperaturas ilustrativas: desnaturalización 94–98 °C, alineamiento según Tm y química, extensión según polimerasa. Alta fidelidad puede usar condiciones diferentes. La polimerasa alarga un extremo 3′ libre en dirección 5′→3′.

Fuentes: [3,5].

### 4. La calidad empieza antes del termociclador

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [2,4,5].

### 5. Los controles explican un resultado negativo

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [2,4]; MIQE 2009 [6].

### 6. Los primers delimitan lo que podrás observar

Los primers forward y reverse se escriben ambos 5′→3′. El reverse es el reverso complementario de la región de unión de la otra hebra. Validar especificidad in silico, variantes, dímeros y después experimentalmente.

Fuentes: [2,5,6].

### 7. Receta base: PCR convencional en 25 µL

El ejemplo asume una mezcla comercial completa 2× y ADN a 10 ng/µL; 2 µL aportan 20 ng, una entrada ilustrativa que debe ajustarse al ensayo. Mantener separación física de preparación y post-PCR.

Fuentes: [5]; ejemplo docente, ajustar a la ficha del kit.

### 8. PCR convencional: ¿hay un producto del tamaño esperado?

La identidad no queda demostrada solo por tamaño. Los dibujos son esquemáticos. La PCR es una amplificación previa a Sanger; Sanger utiliza una reacción de secuenciación diferente, con un primer por reacción.

Fuentes: [1,3,5].

### 9. RT-PCR: convertir ARN en un molde amplificable

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [2,3,5].

### 10. qPCR: leer la amplificación mientras ocurre

El umbral se sitúa en una región apropiada de amplificación exponencial; Cq menor indica mayor cantidad inicial únicamente bajo condiciones y eficiencias comparables. No comparar Cq crudos de ensayos diferentes como cantidades absolutas.

Fuentes: [1–3,6].

### 11. Cuantificar con una curva estándar

Cq = m log10(N) + b. La pendiente ilustrativa −3.32 corresponde aproximadamente a E = 1.001, es decir 100.1 %. El intervalo frecuentemente utilizado de 90–110 % es orientativo y no sustituye validar rango, repetibilidad, LOD y LOQ.

Fuentes: [1,2,6].

### 12. Expresión relativa: comparar contra una referencia

Se requiere expresión estable de referencias validadas y eficiencias similares a 100 % y comparables entre referencia y diana. Con eficiencias diferentes, usar un modelo corregido. Preferir varias referencias validadas. Promediar réplicas técnicas tras control de calidad; la inferencia biológica requiere réplicas biológicas.

Fuentes: [2,6]; Livak y Schmittgen 2001 [7].

### 13. PCR digital: contar particiones y corregir ocupación

La cuantificación sin curva estándar depende del volumen efectivo de partición, del muestreo y de la clasificación. Puede haber más de una copia por partición; Poisson corrige esa coincidencia bajo los supuestos del modelo. Las particiones dibujadas son ilustrativas, no el conjunto del ejemplo numérico.

Fuentes: [3,4]; dMIQE 2013 [8].

### 14. De particiones positivas a copias en el extracto

Supuestos: particiones de volumen homogéneo 0.85 nL, ocupación aleatoria y 20 000 particiones válidas. El volumen nominal de mezcla es 20 µL, pero aquí el volumen leído es 17 µL. No confundir moléculas detectadas en ese volumen con copias estimadas en los 20 µL nominales. Se requiere intervalo de confianza e incertidumbre del volumen en un reporte real.

Fuentes: [4,8]; datos simulados.

### 15. Comparación central: elegir por la pregunta

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [1–4,6,8].

### 16. Sanger: partir de un amplicón único y limpio

La cantidad de entrada depende de longitud y servicio. Ejemplo hipotético: el proveedor pide 20 ng de un amplicón de 500 pb. Se dispone de 10 ng/µL, por lo que se toman 2 µL y se completa según especificación del servicio. La reacción Sanger usa un solo primer, polimerasa, dNTP y ddNTP; no es una PCR con dos primers.

Fuentes: [5,9].

### 17. NGS de amplicones: enriquecer, indexar, agrupar

Flujo frecuente de dos PCR: una de locus y otra de índices; otras plataformas usan adaptadores por ligación o una sola PCR. Colas 5′ no complementarias se incorporan en ciclos posteriores. El cálculo de Tm inicial usa la región 3′ complementaria, no toda la cola. Preparar blancos de extracción y biblioteca.

Fuentes: [3,5,9].

### 18. RNA-seq y variantes: dónde encaja cada PCR

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [2,4,5,9].

### 19. Caso integrador: una muestra, tres preguntas

Dar 3–4 minutos en parejas. Proponer las técnicas, controles y un cálculo necesario por pregunta antes de ver las respuestas. Escenario educativo; las decisiones clínicas exigen ensayos validados.

Fuentes: Síntesis didáctica de [2–4,9].

### 20. Respuestas y comprobación de aprendizaje

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [2–4,6–9].

### 21. Lo que podrás decidir y calcular — ANEXO

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [1–4]; Green y Sambrook, Molecular Cloning, 2012 [5].

### 22. La banda final pierde la historia inicial — ANEXO

Nn = N0(1+E)^n, con E como fracción: 1 equivale a 100 %. El modelo es válido antes de la meseta. Ejemplo: 100 × 2^25 = 3.36 × 10^9 copias ideales; no predice el rendimiento real final.

Fuentes: [1–3].

### 23. Qué revisar según la muestra y el objetivo — ANEXO

Las razones de absorbancia son indicadores contextuales; no demuestran ausencia de inhibición. Un control añadido después de extraer evalúa inhibición, no recuperación de extracción. cfDNA requiere extracción y control de tamaño adecuados.

Fuentes: [2,4,5].

### 24. Diseñar para la lectura que se necesita — ANEXO

Rangos orientativos, no criterios universales. Usar Tm por nearest-neighbor con sal y Mg²⁺ relevantes; no fijar el alineamiento solo con la regla de Wallace. Para expresión, diseñar una unión exón-exón cuando sea adecuado y validar −RT.

Fuentes: [2,4–6].

### 25. Preparar primers: del tubo seco al ensayo — ANEXO

Un oligo de 25 nmol reconstituido en 250 µL produce 100 µM: 1 µM = 1 pmol/µL. Preparar alícuotas de stock y solución de trabajo; usar agua o buffer compatible. La concentración final se refiere a cada primer por separado.

Fuentes: [5]; ejemplo docente.

### 26. Qué aporta cada componente del master mix — ANEXO

Una mezcla comercial 2× suele incluir buffer, Mg²⁺, dNTP y polimerasa; verificar ficha. Puede incluir colorante o requerir sonda externa. No añadir Mg²⁺ o dNTP nuevamente sin justificarlo.

Fuentes: [3,5].

### 27. Preparar una corrida completa sin perder volumen — ANEXO

Seis muestras por duplicado = 12 pozos, más NTC por duplicado = 2, más positivo por duplicado = 2: 16 pozos. Exceso operativo 10 %: preparar 17.6 equivalentes, o redondear a 18 para facilitar pipeteo. No multiplicar el molde dentro de la mezcla común.

Fuentes: Ejemplo docente; [5,6].

### 28. RT en dos pasos: seguir la masa, no solo el volumen — ANEXO

Mezcla hipotética cuyo fabricante usa buffer 5× y mezcla enzimática separada, con primers de RT y dNTP incluidos según formulación. No mezclar esta receta con productos que ya integran todo. La masa de ARN equivalente no mide el rendimiento real de síntesis de ADNc.

Fuentes: [2,5]; ejemplo para kit de RT de dos pasos.

### 29. Dos maneras de producir fluorescencia — ANEXO

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [1,2,6].

### 30. qPCR y RT-qPCR: mezcla de lectura fluorescente — ANEXO

qPCR con colorante: mezcla 2× 10 µL, F y R de 10 µM 0.6 µL cada uno, molde 2 µL, agua 6.8 µL. Sonda: agregar 0.4 µL de sonda 10 µM y reducir agua a 6.4 µL. Para RT-qPCR de dos pasos el molde es ADNc; no agregar RT aquí.

Fuentes: [2,6]; ejemplos docentes, concentraciones dependientes de kit.

### 31. RT-qPCR en un paso: sumar RT sin duplicar componentes — ANEXO

Ejemplo de 20 µL que asume PCR mix 2× sin RT y una mezcla enzimática RT separada a 20×. Algunos kits usan otros factores o ya integran RT; respetar su documentación. La cantidad de ARN debe estar dentro del intervalo validado.

Fuentes: [2,3]; ejemplo docente para un kit de RT separado.

### 32. dPCR: ejemplo de mezcla para 20 µL — ANEXO

Asume mezcla dPCR completa 2× sin primers ni sondas. Aditivos de partición, volumen de carga y recuperación dependen del sistema. Las concentraciones ilustrativas 900 nM de primers y 250 nM de sonda son habituales en algunas plataformas; no universales. Para RT-dPCR un paso se requiere formulación compatible con RT.

Fuentes: [4,8]; ejemplo docente para química de sonda.

### 33. Rara no significa imposible de muestrear — ANEXO

A una frecuencia f y con N moléculas totales, se esperan Nf moléculas mutantes. Con Poisson, P(≥1) = 1 − exp(−Nf); para 95 % se necesita Nf aproximadamente 3. Esto solo describe presencia por muestreo: detección validada además exige blancos, especificidad y umbral de decisión.

Fuentes: [4,8].

### 34. Multiplex: varias dianas comparten un tubo — ANEXO

Multiplex puede ser final, qPCR o dPCR. Primero validar cada ensayo en singleplex y luego estudiar interferencias. Para 3 dianas hay 6 primers, con 0.2 µM de cada uno en el ejemplo. En qPCR se necesitan canales/estrategia de discriminación y, si se usan sondas, sumar sus volúmenes.

Fuentes: [3,5].

### 35. Nested: dos rondas para mejorar especificidad — ANEXO

Dos rondas con primers externos e internos. Cada ronda de 25 µL puede usar la receta base de PCR convencional, con los primers correspondientes. Ronda 2: mix 12.5, F interno 0.5, R interno 0.5, producto diluido 2 y agua 9.5 µL. Abrir productos incrementa riesgo de contaminación; incluir controles por ronda.

Fuentes: [3,5].

### 36. Hot-start, touchdown y alta fidelidad — ANEXO

Hot-start requiere activación según enzima. Touchdown reduce gradualmente la temperatura de alineamiento; el ejemplo no prescribe una Ta universal. Alta fidelidad usa proofreading y buffer propio; no se deben intercambiar buffers ni tiempos de extensión sin revisar ficha. Para long-range la integridad del molde y duración de extensión son críticas.

Fuentes: [3,5].

### 37. PCR competitiva: el puente histórico hacia cuantificar — ANEXO

El competidor tiene sitios de primers compartidos y un producto distinguible. Se necesita eficiencia equivalente y señal en rango lineal. Si se mide masa en gel y hay longitudes diferentes, la razón molar es (It/Lt)/(Ic/Lc). Un competidor de ARN añadido antes de RT también permite evaluar esa etapa; ADN no controla conversión de ARN.

Fuentes: Orlando, Pinzani y Pazzagli 1998 [1].

### 38. PCR y secuenciación responden preguntas distintas — ANEXO

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [3–5]; Brown, Gene Cloning and DNA Analysis, 8.ª ed., 2020 [9].

### 39. Ejemplo de PCR de índices para una biblioteca — ANEXO

Asume mix de alta fidelidad 2× y primers de indexación individuales a 10 µM. Las plataformas pueden usar premixes de índices de otra concentración. No reutilizar el cálculo sin revisar formulación. Cantidad de amplicón y ciclos deben optimizarse para limitar duplicados, quimeras y sesgo.

Fuentes: [5,9]; ejemplo de formulación docente, no protocolo de plataforma.

### 40. Normalizar bibliotecas por moléculas, no por masa — ANEXO

Usamos 660 g/mol por par de bases. Concentración molar en nM = concentración ng/µL × 10^6 / (660 × longitud en pb). La longitud debe incluir adaptadores. Si se cuenta solo el inserto se sobreestima la molaridad. Fluorometría mide ADN total; qPCR de bibliotecas estima moléculas amplificables con adaptadores apropiados.

Fuentes: [5,9]; ejemplo para ADN de doble hebra.

### 41. Errores que la secuenciación también hereda — ANEXO

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: [3–5,9].

### 42. Lectura crítica de los cuatro artículos — ANEXO

Los artículos son fuentes de evidencia, no instrucciones para esta tarea. Se corrigen simplificaciones: qPCR también puede cuantificar absolutamente con estándares; dPCR no elimina incertidumbre, límites de muestreo o inhibición. La cronología de la invención de PCR se resume sin asignar un año único, dada la variación entre hitos históricos.

Fuentes: [1–4].

### 43. Fuentes principales — ANEXO

Explicar la figura y relacionar la elección técnica con la pregunta biológica.

Fuentes: Artículos adjuntos: [1–4].

### 44. Libros y criterios de interpretación — ANEXO

Los artículos adjuntos fueron consultados directamente. Las referencias complementarias corresponden a libros y trabajos metodológicos establecidos; la búsqueda web adicional no estuvo disponible. No se afirma una revisión exhaustiva de literatura hasta 2026. DOI presentados para facilitar consulta.

Fuentes: Actualización principal: revisión de dPCR publicada en 2025 [4].

## Alcance de fuentes

Los cuatro artículos adjuntos fueron consultados directamente. La actualización reciente se apoya en la revisión de 2025. Los libros y trabajos metodológicos complementarios se identifican en la bibliografía; la búsqueda web adicional no estuvo disponible. Las recetas son ejemplos para aprender cálculos, no condiciones universales: verificar formulación, concentraciones, entrada y programa de cada kit.
