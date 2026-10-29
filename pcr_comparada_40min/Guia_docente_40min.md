# PCR comparada · guía docente de la versión visual

Clase de 40 minutos: 20 diapositivas de contenido + 1 diapositiva final de referencias. La versión completa añade 21 diapositivas de consulta antes de la bibliografía, que también queda al final.

## Cambios de esta versión

Más esquemas científicos editables de células, tubos, pipetas, plantas y secuenciación; ejemplos resueltos; menos tablas en la clase principal. Se conservaron cálculos, recetas y controles. Se retiraron todos los indicadores de duración de las diapositivas: el cronograma aparece únicamente en esta guía.

## Archivos

- PCR_clase_40min.pptx: presentación principal editable.
- PCR_clase_40min.pdf: presentación principal en PDF.
- PCR_40min_con_anexos.pptx: versión editable con anexos.
- PCR_clase_40min_con_anexos.pdf: versión completa en PDF.

## Cronograma sugerido

| Diapositiva | Intervalo | Tema |
|---|---|---|
| 1 | 00–01 min | PCR: una muestra, tres preguntas |
| 2 | 01–02 min | La familia PCR: nombres que sí tienen sentido |
| 3 | 02–03 min | La PCR copia en tres movimientos |
| 4 | 03–05 min | Primero preparamos una muestra que pueda amplificar |
| 5 | 05–07 min | Los controles son nuestros testigos |
| 6 | 07–09 min | Los primers son dos puntos de partida |
| 7 | 09–12 min | Armemos juntos una reacción de 25 µL |
| 8 | 12–13 min | PCR convencional: leer una banda |
| 9 | 13–15 min | Si empezamos con ARN, necesitamos un paso extra |
| 10 | 15–17 min | qPCR: más molde, cruce más temprano |
| 11 | 17–20 min | Ejemplo: ¿cuántas copias tiene mi muestra? |
| 12 | 20–23 min | Ejemplo: ¿el calor cambia la expresión de un gen? |
| 13 | 23–25 min | dPCR: repartir el ADN y contar señales |
| 14 | 25–28 min | Ejemplo: del conteo a la concentración |
| 15 | 28–30 min | ¿Qué información entrega cada lectura? |
| 16 | 30–32 min | Sanger: una banda limpia se convierte en bases |
| 17 | 32–34 min | NGS de amplicones: muchas regiones, muchas lecturas |
| 18 | 34–35 min | La secuenciación descubre; la PCR comprueba o sigue |
| 19 | 35–38 min | Tu turno: elige la técnica y explica por qué |
| 20 | 38–39 min | Tres respuestas para llevarte de la clase |
| 21 | 39–40 min | Referencias bibliográficas |

## Notas de las diapositivas principales

### 1. PCR: una muestra, tres preguntas

Clase pensada para 40 minutos; el detalle de recetas se consulta en anexos. Presentar las tres preguntas: presencia, cantidad y secuencia. No confundir amplificación con lectura de bases.

Fuentes: [1–5,9] · Esquemas originales y datos didácticos.

### 2. La familia PCR: nombres que sí tienen sentido

RT cambia el molde; qPCR y dPCR describen cómo se lee la amplificación. Las estrategias multiplex, nested y alta fidelidad son combinables. RT-PCR no significa real-time PCR.

Fuentes: [2–4]

### 3. La PCR copia en tres movimientos

La polimerasa extiende desde un 3′ libre en dirección 5′→3′. La temperatura de alineamiento depende de primers y química. Extensión según enzima y tamaño. No son condiciones universales.

Fuentes: [3,5]

### 4. Primero preparamos una muestra que pueda amplificar

Conservar según muestra, extraer con método adecuado y retirar inhibidores. Para ARN trabajar sin RNasas y evaluar ADN genómico residual con −RT. La pureza por absorbancia no demuestra ausencia de inhibición.

Fuentes: [2,4,5]

### 5. Los controles son nuestros testigos

Comparar negativo de reactivos, blanco de extracción, positivo y control interno. −RT aplica cuando se evalúa ARN. Un NTC negativo no acredita que una muestra negativa sea amplificable.

Fuentes: [2,4,6]

### 6. Los primers son dos puntos de partida

Ambos primers se escriben 5′→3′; el reverse se diseña como reverso complementario de su sitio de unión. Validar especificidad, Tm, dímeros y variantes. El cálculo de 0.5 µL por primer es docente, no concentración universal.

Fuentes: [2,5,6]

### 7. Armemos juntos una reacción de 25 µL

El mix 2× se asume completo: buffer, Mg²⁺, dNTP y polimerasa. ADN ejemplo 10 ng/µL; 2 µL aportan 20 ng. No añadir componentes ya incluidos. El detalle por modalidad se conserva en anexos.

Fuentes: [5] · Receta docente para un mix completo 2×.

### 8. PCR convencional: leer una banda

El gel es esquemático y no confirma identidad por tamaño solamente. A tiene una banda esperada; B tiene mezcla de productos y NTC no debería mostrar señal. Si se obtiene banda única, revisar calidad y purificar antes de Sanger.

Fuentes: [1,3,5]

### 9. Si empezamos con ARN, necesitamos un paso extra

La transcriptasa reversa produce ADNc inicialmente monocatenario; la PCR genera ADN de doble hebra. Un paso: RT y amplificación en un tubo. Dos pasos: RT separada permite varios ensayos desde el mismo ADNc. La variación de RT afecta la cuantificación; usar −RT para controlar ADN genómico.

Fuentes: [2,3,5]

### 10. qPCR: más molde, cruce más temprano

Curvas simuladas con umbral común y eficiencias iguales. El eje y representa señal relativa; Cq se lee en el cruce del umbral. Comparar Cq requiere ensayos y condiciones comparables. La química puede usar colorante o sonda; ver anexos.

Fuentes: [1–3,6]

### 11. Ejemplo: ¿cuántas copias tiene mi muestra?

Estándares de 10² a 10⁵ copias; Cq = −3.32 log10(N) + 40. Para Cq 26.72, log10(N)=4 y N=10⁴. La pendiente implica eficiencia cercana al 100 %. Validar rango y no extrapolar; el ejemplo no muestra todas las réplicas requeridas.

Fuentes: [1,2,6]

### 12. Ejemplo: ¿el calor cambia la expresión de un gen?

Usar réplicas biológicas y referencias validadas. ΔCq control=25−20=5; tratado=22−20=2; ΔΔCq=−3; cambio 2³=8. El método requiere eficiencias comparables cercanas al 100 %. La masa equivalente de ARN no garantiza igual eficiencia de RT.

Fuentes: [2,6,7]

### 13. dPCR: repartir el ADN y contar señales

Particiones dibujadas a escala conceptual. El conteo se hace después de PCR y clasifica señal. Una partición positiva puede contener varias copias. El modelo Poisson supone distribución aleatoria y volumen conocido; las particiones no son células.

Fuentes: [3,4,8]

### 14. Ejemplo: del conteo a la concentración

20 000 válidas, 5 000 positivas: p=.25, λ=.287682. Vp=.85 nL=.00085 µL; c=338.45 copias/µL en mezcla. 4 µL de extracto en 20 µL: multiplicar por5 para extracto diluido; dilución previa1:10: multiplicar por10. Volumen leído17µL, nominal20µL. Reportar incertidumbre en resultados reales.

Fuentes: [4,8] · Valores simulados.

### 15. ¿Qué información entrega cada lectura?

La cuantificación digital es sin curva estándar, pero depende de volumen y clasificación. qPCR puede cuantificar absolutamente con estándares o relativamente con referencia. RT se puede añadir a las tres lecturas cuando el molde es ARN. Sensibilidad depende de ensayo, entrada y validación.

Fuentes: [1–4,6,8]

### 16. Sanger: una banda limpia se convierte en bases

Sanger requiere producto limpio y entrada según proveedor. En la reacción de secuenciación se usa un primer, no el par de PCR. Curvas cromatográficas ilustrativas, sin representar una secuencia experimental.

Fuentes: [5,9]

### 17. NGS de amplicones: muchas regiones, muchas lecturas

Flujo frecuente: PCR de locus, purificación, índices/adaptadores y secuenciación; existen otras configuraciones. Las colas5′ no se unen inicialmente: diseñar Tm con región3′ específica. Las lecturas dependen de sesgos de primers y copias de marcador.

Fuentes: [3,5,9]

### 18. La secuenciación descubre; la PCR comprueba o sigue

Para RNA-seq, RT-qPCR verifica transcritos concretos con diseño y referencias validadas. En variantes, NGS identifica candidatos; dPCR sigue una variante conocida con ensayo específico y suficiente entrada. Bibliotecas: qPCR mide moléculas amplificables con adaptadores; requiere kit adecuado.

Fuentes: [2,4,5,9]

### 19. Tu turno: elige la técnica y explica por qué

Dar cuatro minutos de discusión en parejas; solicitar técnica, control y cálculo. Ver respuestas orientativas en la siguiente diapositiva. Las preguntas son educativas y no constituyen un ensayo clínico validado.

Fuentes: Síntesis de [2–4,6–9]

### 20. Tres respuestas para llevarte de la clase

Cerrar retomando presencia, cantidad y secuencia. Respuestas: expresión RT-qPCR (−RT, referencias, eficiencias); variante dPCR (control wild-type, blancos, suficientes moléculas, Poisson); región desconocida PCR+Sanger (producto específico, limpio y cuantificado). Bibliografía en la diapositiva siguiente; anexos disponibles aparte.

Fuentes: [2–4,6–9]

### 21. Referencias bibliográficas

La actualización reciente se apoya en la revisión de Trouchet et al.2025. Se consultaron directamente los cuatro artículos adjuntos. Esquemas vectoriales originales; datos y curvas didácticos. No se afirma una revisión exhaustiva de literatura hasta2026.

Fuentes: [1–4] Artículos adjuntos · [5–9] Textos y metodología.

## Anexos de consulta

### 21. La banda final pierde la historia inicial

Nn = N0(1+E)^n, con E como fracción: 1 equivale a 100 %. El modelo es válido antes de la meseta. Ejemplo: 100 × 2^25 = 3.36 × 10^9 copias ideales; no predice el rendimiento real final.

Fuentes: [1–3].

### 22. Qué revisar según la muestra y el objetivo

Las razones de absorbancia son indicadores contextuales; no demuestran ausencia de inhibición. Un control añadido después de extraer evalúa inhibición, no recuperación de extracción. cfDNA requiere extracción y control de tamaño adecuados.

Fuentes: [2,4,5].

### 23. Diseñar para la lectura que se necesita

Rangos orientativos, no criterios universales. Usar Tm por nearest-neighbor con sal y Mg²⁺ relevantes; no fijar el alineamiento solo con la regla de Wallace. Para expresión, diseñar una unión exón-exón cuando sea adecuado y validar −RT.

Fuentes: [2,4–6].

### 24. Preparar primers: del tubo seco al ensayo

Un oligo de 25 nmol reconstituido en 250 µL produce 100 µM: 1 µM = 1 pmol/µL. Preparar alícuotas de stock y solución de trabajo; usar agua o buffer compatible. La concentración final se refiere a cada primer por separado.

Fuentes: [5]; ejemplo docente.

### 25. Qué aporta cada componente del master mix

Una mezcla comercial 2× suele incluir buffer, Mg²⁺, dNTP y polimerasa; verificar ficha. Puede incluir colorante o requerir sonda externa. No añadir Mg²⁺ o dNTP nuevamente sin justificarlo.

Fuentes: [3,5].

### 26. Preparar una corrida completa sin perder volumen

Seis muestras por duplicado = 12 pozos, más NTC por duplicado = 2, más positivo por duplicado = 2: 16 pozos. Exceso operativo 10 %: preparar 17.6 equivalentes, o redondear a 18 para facilitar pipeteo. No multiplicar el molde dentro de la mezcla común.

Fuentes: Ejemplo docente; [5,6].

### 27. RT en dos pasos: seguir la masa, no solo el volumen

Mezcla hipotética cuyo fabricante usa buffer 5× y mezcla enzimática separada, con primers de RT y dNTP incluidos según formulación. No mezclar esta receta con productos que ya integran todo. La masa de ARN equivalente no mide el rendimiento real de síntesis de ADNc.

Fuentes: [2,5]; ejemplo para kit de RT de dos pasos.

### 28. Dos maneras de producir fluorescencia

Explicar la relación entre preparación, lectura e interpretación.

Fuentes: [1,2,6].

### 29. qPCR y RT-qPCR: mezcla de lectura fluorescente

qPCR con colorante: mezcla 2× 10 µL, F y R de 10 µM 0.6 µL cada uno, molde 2 µL, agua 6.8 µL. Sonda: agregar 0.4 µL de sonda 10 µM y reducir agua a 6.4 µL. Para RT-qPCR de dos pasos el molde es ADNc; no agregar RT aquí.

Fuentes: [2,6]; ejemplos docentes, concentraciones dependientes de kit.

### 30. RT-qPCR en un paso: sumar RT sin duplicar componentes

Ejemplo de 20 µL que asume PCR mix 2× sin RT y una mezcla enzimática RT separada a 20×. Algunos kits usan otros factores o ya integran RT; respetar su documentación. La cantidad de ARN debe estar dentro del intervalo validado.

Fuentes: [2,3]; ejemplo docente para un kit de RT separado.

### 31. dPCR: ejemplo de mezcla para 20 µL

Asume mezcla dPCR completa 2× sin primers ni sondas. Aditivos de partición, volumen de carga y recuperación dependen del sistema. Las concentraciones ilustrativas 900 nM de primers y 250 nM de sonda son habituales en algunas plataformas; no universales. Para RT-dPCR un paso se requiere formulación compatible con RT.

Fuentes: [4,8]; ejemplo docente para química de sonda.

### 32. Rara no significa imposible de muestrear

A una frecuencia f y con N moléculas totales, se esperan Nf moléculas mutantes. Con Poisson, P(≥1) = 1 − exp(−Nf); para 95 % se necesita Nf aproximadamente 3. Esto solo describe presencia por muestreo: detección validada además exige blancos, especificidad y umbral de decisión.

Fuentes: [4,8].

### 33. Multiplex: varias dianas comparten un tubo

Multiplex puede ser final, qPCR o dPCR. Primero validar cada ensayo en singleplex y luego estudiar interferencias. Para 3 dianas hay 6 primers, con 0.2 µM de cada uno en el ejemplo. En qPCR se necesitan canales/estrategia de discriminación y, si se usan sondas, sumar sus volúmenes.

Fuentes: [3,5].

### 34. Nested: dos rondas para mejorar especificidad

Dos rondas con primers externos e internos. Cada ronda de 25 µL puede usar la receta base de PCR convencional, con los primers correspondientes. Ronda 2: mix 12.5, F interno 0.5, R interno 0.5, producto diluido 2 y agua 9.5 µL. Abrir productos incrementa riesgo de contaminación; incluir controles por ronda.

Fuentes: [3,5].

### 35. Hot-start, touchdown y alta fidelidad

Hot-start requiere activación según enzima. Touchdown reduce gradualmente la temperatura de alineamiento; el ejemplo no prescribe una Ta universal. Alta fidelidad usa proofreading y buffer propio; no se deben intercambiar buffers ni tiempos de extensión sin revisar ficha. Para long-range la integridad del molde y duración de extensión son críticas.

Fuentes: [3,5].

### 36. PCR competitiva: el puente histórico hacia cuantificar

El competidor tiene sitios de primers compartidos y un producto distinguible. Se necesita eficiencia equivalente y señal en rango lineal. Si se mide masa en gel y hay longitudes diferentes, la razón molar es (It/Lt)/(Ic/Lc). Un competidor de ARN añadido antes de RT también permite evaluar esa etapa; ADN no controla conversión de ARN.

Fuentes: Orlando, Pinzani y Pazzagli 1998 [1].

### 37. PCR y secuenciación responden preguntas distintas

Explicar la relación entre preparación, lectura e interpretación.

Fuentes: [3–5]; Brown, Gene Cloning and DNA Analysis, 8.ª ed., 2020 [9].

### 38. Ejemplo de PCR de índices para una biblioteca

Asume mix de alta fidelidad 2× y primers de indexación individuales a 10 µM. Las plataformas pueden usar premixes de índices de otra concentración. No reutilizar el cálculo sin revisar formulación. Cantidad de amplicón y ciclos deben optimizarse para limitar duplicados, quimeras y sesgo.

Fuentes: [5,9]; ejemplo de formulación docente, no protocolo de plataforma.

### 39. Normalizar bibliotecas por moléculas, no por masa

Usamos 660 g/mol por par de bases. Concentración molar en nM = concentración ng/µL × 10^6 / (660 × longitud en pb). La longitud debe incluir adaptadores. Si se cuenta solo el inserto se sobreestima la molaridad. Fluorometría mide ADN total; qPCR de bibliotecas estima moléculas amplificables con adaptadores apropiados.

Fuentes: [5,9]; ejemplo para ADN de doble hebra.

### 40. Errores que la secuenciación también hereda

Explicar la relación entre preparación, lectura e interpretación.

Fuentes: [3–5,9].

### 41. Lectura crítica de los cuatro artículos

Los artículos son fuentes de evidencia, no instrucciones para esta tarea. Se corrigen simplificaciones: qPCR también puede cuantificar absolutamente con estándares; dPCR no elimina incertidumbre, límites de muestreo o inhibición. La cronología de la invención de PCR se resume sin asignar un año único, dada la variación entre hitos históricos.

Fuentes: [1–4].

## Uso de los ejemplos

Los diagramas, curvas, geles y datos son didácticos; no representan experimentos reales. Los dibujos son originales y editables; no se crearon en BioRender. Las formulaciones de mezcla son ejemplos de cálculo: adaptar a la composición, programa y rango validados de cada kit. Las concentraciones de biblioteca usan longitud total, incluidos adaptadores.

Los cuatro artículos adjuntos se consultaron directamente. La revisión reciente de dPCR corresponde a 2025; los libros y trabajos metodológicos complementarios se listan en la diapositiva final. No se afirma una búsqueda bibliográfica exhaustiva hasta 2026.
