## Conclusiones del análisis

A partir del análisis exploratorio de datos y de los modelos de machine learning implementados, fue posible identificar los factores más relevantes asociados a la cancelación de clientes en Telecom X.

Los resultados muestran que la cancelación no depende de una sola variable, sino de la combinación de factores relacionados con el tipo de contrato, los costos del servicio y el tiempo de permanencia del cliente.

### Factores que más influyen en la cancelación

Los modelos identificaron varias variables con fuerte relación con el churn:

**1. Tipo de contrato**
Los clientes con contratos **mes a mes** presentan una probabilidad significativamente mayor de cancelar el servicio en comparación con aquellos que poseen contratos de uno o dos años. Esto sugiere que los contratos de largo plazo generan mayor fidelización.

**2. Antigüedad del cliente**
La antigüedad tiene una relación inversa con la cancelación. Los clientes que llevan poco tiempo con la empresa tienen una mayor probabilidad de abandonar el servicio, mientras que los clientes con mayor permanencia tienden a mantenerse activos.

**3. Cargos mensuales**
Se observa que clientes con **cargos mensuales más altos** presentan mayor tendencia a cancelar el servicio, posiblemente debido a la percepción de alto costo o baja relación costo-beneficio.

**4. Servicios adicionales**
Servicios como soporte técnico, seguridad en línea o copias de seguridad influyen en la retención de clientes. Los clientes que cuentan con estos servicios adicionales muestran menor probabilidad de cancelar.

**5. Tipo de servicio de internet**
Los clientes con ciertos tipos de servicio, como fibra óptica, muestran mayores niveles de cancelación, lo que puede indicar problemas de satisfacción o expectativas más altas respecto al servicio.

### Evaluación de los modelos

Se utilizaron dos modelos para la predicción de cancelación:

- **Regresión Logística**
- **Random Forest**

La Regresión Logística permitió interpretar claramente la influencia de cada variable en la probabilidad de cancelación mediante el análisis de los coeficientes.

Por otro lado, Random Forest capturó relaciones más complejas entre las variables y permitió identificar la importancia relativa de cada una en el proceso de predicción.

En general, Random Forest mostró un mejor desempeño predictivo al considerar interacciones entre múltiples variables, mientras que la Regresión Logística resultó útil para interpretar el impacto individual de cada factor.

### Análisis de desempeño del modelo

Las métricas evaluadas (accuracy, precisión, recall y F1-score) permitieron comparar ambos modelos. En problemas de churn, el **recall** es particularmente importante, ya que permite identificar la mayor cantidad posible de clientes con riesgo de cancelación.

Detectar tempranamente a estos clientes permite implementar estrategias de retención antes de que abandonen el servicio.

## Estrategias de retención recomendadas

A partir de los resultados del análisis, se pueden proponer las siguientes estrategias para reducir la cancelación de clientes:

**1. Incentivar contratos de largo plazo**
Ofrecer descuentos, beneficios o promociones a clientes que opten por contratos de uno o dos años puede ayudar a reducir la cancelación.

**2. Programas de fidelización para clientes nuevos**
Dado que los clientes con menor antigüedad presentan mayor churn, se recomienda implementar programas de fidelización durante los primeros meses del servicio.

**3. Revisión de la estructura de precios**
Analizar la relación entre el valor del servicio y los beneficios percibidos por el cliente puede ayudar a reducir la cancelación asociada a cargos mensuales elevados.

**4. Promoción de servicios adicionales**
Incentivar la adopción de servicios como soporte técnico o seguridad digital puede aumentar la satisfacción del cliente y reducir la probabilidad de cancelación.

**5. Monitoreo predictivo del churn**
Implementar modelos de machine learning como los desarrollados en este análisis permitiría identificar clientes con alto riesgo de cancelación y aplicar acciones preventivas de retención.

## Conclusión general

El análisis demuestra que la combinación de técnicas de análisis de datos y machine learning permite comprender mejor el comportamiento de los clientes y anticipar posibles cancelaciones.

La implementación de estrategias basadas en datos puede ayudar a Telecom X a mejorar la retención de clientes, optimizar sus servicios y aumentar el valor a largo plazo de su base de clientes.
