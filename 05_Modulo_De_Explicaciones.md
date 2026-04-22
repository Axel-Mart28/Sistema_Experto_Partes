5. Módulo de Explicaciones
¿Qué es?
Es el subsistema encargado de la transparencia y la trazabilidad de las decisiones del sistema experto.

¿Para qué sirve?
Sirve para justificar ante el usuario por qué el motor de inferencia llegó a una conclusión específica o por qué tomó una determinada acción. Es crucial para dar confianza al investigador sobre los resultados.

¿Cómo funciona?
Rastrea hacia atrás las reglas que el Motor de Inferencia activó para llegar a un resultado y las traduce a un lenguaje comprensible para el ser humano.

Ejemplo Práctico:
Si el sistema detiene la simulación del brazo robótico, el investigador puede pedir detalles. El módulo mostrará en pantalla: "Simulación detenida porque el encoder registró una desviación de 0.6°, superando el umbral de 0.5° establecido en la regla de holgura de engranajes."