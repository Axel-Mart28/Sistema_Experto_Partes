2. Módulo de Adquisición de Conocimiento
¿Qué es?
Es el subsistema de software que actúa como filtro y traductor entre el entorno exterior y las bases internas del sistema.

¿Para qué sirve?
Sirve para recibir, validar, estructurar y controlar el flujo del nuevo conocimiento o de los datos en bruto, asegurando que solo entre información coherente y útil a la base de conocimiento o a la memoria de trabajo.

¿Cómo funciona?
Toma las reglas dictadas por los expertos o los datos brutos de los sensores, evalúa si es conocimiento nuevo o redundante, verifica su consistencia (mediante un control de coherencia) y lo empaqueta en un formato que el sistema pueda almacenar y procesar.

Ejemplo Práctico:
Un script que recibe los pulsos del encoder magnético y los grados de desviación ingresados por el investigador. El módulo evalúa si la lectura tiene un formato válido y rechaza datos anómalos o imposibles físicamente antes de guardarlos.