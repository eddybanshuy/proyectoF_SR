# proyectoF_SR
Trabajo académico final escrito: Implementación de un sistema de recomendación basado en filtrado colaborativo


Planteamiento de la actividad


El objetivo de este proyecto es implementar y evaluar un sistema de recomendación utilizando técnicas de filtrado colaborativo y un dataset proporcionado por el docente. El sistema deberá ser capaz de generar recomendaciones personalizadas a usuarios en función de sus preferencias o comportamientos pasados.


El trabajo final se desarrollará en grupo de dos personas, considerando las siguientes fases:


Fase 1: Análisis y preparación de los datos



En base al conjunto de datos proporcionado por su docente, explore la estructura del dataset y examine qué tipo de información tiene su conjunto de datos. Luego:
Realice una descripción del dataset.

Describa las características de su conjunto de datos: número de usuarios, número de ítems, cantidad de calificaciones (ratings), porcentaje de escasez, etc.

Utilice gráficas o tablas para visualizar la información que caracteriza su dataset, por ejemplo, distribución de ratings, estadísticas descriptivas (media, mediana, desviación estándar de ratings, etc.), detección de outliers (usuarios con demasiadas o muy pocas interacciones, ítems que casi nadie ha valorado).

Prepare el conjunto de datos realizando lo siguiente:

Seleccionar usuarios que han calificado/interactuado con al menos 20 ítems.

Eliminar ítems que han sido valorados por muy pocos usuarios.

Conversión de datos (si aplica)

Normalizar los datos (si aplica)

Transformación y construcción de la matriz de utilidad

Fase 2: Experimentación


Aplicar un algoritmo de FC basado en memoria.

Aplicar un algoritmo de FC basado en modelos.

Fase 3: Evaluación


Evaluar el rendimiento de los algoritmos de FC utilizando al menos dos métricas. Interpretar resultados de las métricas.

Ajustar parámetros si es necesario.

Seleccionar el algoritmo con mejor desempeño y mostrar las recomendaciones para un usuario específico.

Si el modelo lo permite, brindar una explicación de las recomendaciones o proporcionar detalles de los ítems recomendados.

Finalmente, el maestrante debe preparar un informe que describa en detalle las fases realizadas, los resultados obtenidos en cada fase y la evaluación del sistema de recomendación. Si desea, puede incluir la documentación en el propio notebook.

