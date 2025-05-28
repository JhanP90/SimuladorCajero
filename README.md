# Introducción

En el contexto actual de globalización y creciente movilidad financiera, el desarrollo de aplicaciones que integren funcionalidades multimoneda se ha vuelto una necesidad cada vez más relevante. Este proyecto tiene como objetivo diseñar e implementar una aplicación tipo cajero automático (ATM) que permita realizar retiros en diversas monedas extranjeras, a partir de un valor de entrada en pesos colombianos (COP).

La aplicación está enfocada en ofrecer al usuario la conversión automática del monto ingresado a monedas como el dólar estadounidense (USD), el euro (EUR) y otras divisas de países latinoamericanos, considerando las tasas de cambio vigentes.

El desarrollo se realizó como parte de un proyecto académico del área de programación, aplicando principios de lógica computacional, estructuras de control, manejo de variables, paradigmas de programación y diseño de interfaces. Se buscó simular una experiencia cercana a la de un cajero automático real, optimizando la precisión de los cálculos y priorizando la facilidad de uso para el usuario.

La aplicación representa una solución práctica para situaciones en las que se requiere conocer el equivalente de una cantidad de dinero local en divisas extranjeras de forma rápida y confiable.

# Propósito

El propósito de este proyecto es desarrollar una aplicación que simule el funcionamiento de un cajero automático, diseñada para facilitar el retiro de dinero en diferentes monedas extranjeras a partir de un valor ingresado en pesos colombianos (COP). Esta herramienta realizará la conversión de forma automática, utilizando tasas de cambio definidas, y ofrecerá al usuario la posibilidad de retirar el equivalente en monedas como el dólar estadounidense (USD), el euro (EUR) y divisas de países latinoamericanos.

La aplicación está especialmente pensada para personas que poseen una cuenta bancaria en Colombia pero que se encuentran en el extranjero, y que frecuentemente enfrentan dificultades al realizar conversiones de moneda para sus gastos o transacciones diarias. Al brindar una simulación precisa y accesible, se pretende ofrecer una solución orientada a mejorar la experiencia del usuario frente al cambio de divisas.

Además del desarrollo técnico, este proyecto resalta la importancia de una documentación clara, estructurada y completa. Cada fase del proceso (desde el análisis del problema hasta el diseño, codificación, pruebas y validación) será debidamente documentada. Esto no solo garantiza la mantenibilidad y escalabilidad del sistema, sino que también evidencia el proceso lógico y metodológico aplicado en la construcción del software.

En el contexto académico, este proyecto busca integrar conocimientos de programación, lógica computacional y diseño de software, con buenas prácticas de documentación técnica, fortaleciendo tanto las competencias tecnológicas como la capacidad de comunicar y justificar soluciones de manera profesional.

# Alcance

Este proyecto contempla el desarrollo de una aplicación de simulación de cajero automático que permita realizar conversiones monetarias a partir de un valor ingresado en pesos colombianos, con salida en diferentes monedas extranjeras. El sistema estará dirigido a personas con cuentas bancarias colombianas que se encuentren en el extranjero.

> **Nota:** No se contempla la conexión real con entidades financieras ni la actualización automática de tasas de cambio desde internet; las tasas serán definidas manualmente para efectos de simulación.

# Descripción general

## Perspectiva del producto

Desarrollar una aplicación tipo cajero automático que permita realizar retiros en diferentes monedas extranjeras (USD, EUR y divisas latinoamericanas), a partir de un monto ingresado en pesos colombianos, utilizando tasas de cambio actualizadas.

## Funcionalidad del producto

### Funciones principales

- Ingreso del monto en pesos colombianos (COP).
- Selección de la moneda de destino (USD, EUR, MXN, ARS, etc.).
- Cálculo de la conversión según tasas predefinidas.
- Visualización del monto convertido.
- Simulación del retiro del dinero (por ejemplo, con mensaje de confirmación).
- Registro de la transacción (opcional, para mostrar historial o guardar en archivo).

### Funciones secundarias

- Validación de entradas (asegurar que el monto ingresado sea numérico y mayor a cero).
- Mostrar las tasas de cambio utilizadas.
- Menú de selección de divisa de moneda.
- Posibilidad de hacer varias conversiones sin cerrar la aplicación.

### Roles
