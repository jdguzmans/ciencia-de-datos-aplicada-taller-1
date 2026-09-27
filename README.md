
# ciencia-de-datos-aplicada-taller-1

**Integrantes:**
| Nombre | Código |
|---|---|
| Juan Guzmán | 2 |
| Andrés Felipe Méndez | 200611694 |


**Objetivo**
Analizar el comportamiento histórico de los contratos de compraventa y suministro registrados en el conjunto de datos, con el propósito de identificar patrones que permitan establecer algunas recomendaciones para la supervisión de los contratos públicos. A partir de estos resultados, se busca proponer a la Oficina de Control Interno un conjunto de criterios de focalización que permita priorizar los contratos que pueden requerir mayor seguimiento, considerando e identificando los atributos más relevantes aplicables.

**Alcance**
Inicialmente, el análisis del presente ejercicio se basa en el set de datos disponible de los contratos de compraventa en el periodo descrito, sin un procesamiento de calidad previo identificado y sin insumos o reglas adicionales de negocio.

Se establecerán algunos supuestos o premisas que ayuden a limitar o aclarar el ejercicio, cuando sea necesario, para dar solución a cualquier estado donde esto ayude al desarrollo del ejercicio.

**Conclusiones (Insights)**
Los resultados recomiendan adoptar una supervisión diferenciada y basada en riesgo. Los contratos de régimen especial con ofertas deberían priorizarse para verificar la ejecución de recursos y el cierre contractual, especialmente en los sectores Salud, Educación Nacional, Interior y Ciencia Tecnología. Las licitaciones públicas requieren mayor seguimiento de cronogramas y adiciones de plazo. Por su parte, los contratos de mínima cuantía, debido a su elevado volumen, deberían controlarse mediante alertas automatizadas y muestras periódicas. Estas cifras representan señales para orientar la supervisión y no constituyen, por sí mismas, evidencia de irregularidades.

- La modalidad de contratación permite identificar diferentes necesidades de supervisión. Los contratos de régimen especial con ofertas presentan una alta incidencia de señales relacionadas con recursos y liquidación, mientras que las licitaciones públicas requieren mayor atención sobre el cumplimiento de cronogramas y las adiciones de plazo. En el caso de la mínima cuantía, aunque las tasas son cercanas o inferiores al comportamiento general, su elevado volumen hace recomendable implementar alertas automatizadas y revisiones por muestreo.

- El sector también representa un criterio relevante. Salud concentra el mayor número de contratos con señales de riesgo, mientras que sectores como Interior y Ciencia Tecnología presentan tasas elevadas en algunas combinaciones de con la modalidad. Por esta razón, la focalización debe considerar conjuntamente ambos factores y evitar decisiones sustentadas exclusivamente en uno de ellos.

- El destino del gasto permite definir el énfasis de la supervisión. En los contratos de funcionamiento resulta conveniente revisar la ejecución de recursos, los pagos y el cumplimiento de obligaciones. En los contratos de inversión debe darse mayor atención al plazo, los entregables y la liquidación. Cuando el destino no se encuentra definido, se recomienda verificar la calidad y correcta clasificación del registro.

- Los contratos de valor alto presentan una mayor incidencia de adiciones de plazo y representan una exposición fiscal superior. Sin embargo, el valor no debe utilizarse de manera aislada como indicador de riesgo, sino como un criterio adicional para priorizar la revisión de contratos que también presentan condiciones asociadas con el sector o la modalidad.

- Como resultado, se recomienda aplicar un esquema de focalización por niveles: seguimiento intensivo para los contratos que reúnen al menos dos criterios estructurales; revisión periódica para aquellos que presentan un criterio; y muestras aleatorias de control para los demás contratos.

**Organización del repositorio**


**Instrucciones de ejecución**

- Informe ejecutivo
  

  Abrir el archivo \Informe_Control_Interno_pbi\Informe_Control_Interno.pbip con Power BI Desktop (Distribución gratuita de Microsoft).

  El modelo se conecta al archivo Parquet público del repositorio del taller y aplica automáticamente la limpieza y el universo de análisis usados en el notebook.