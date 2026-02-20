Racional de decisiones con conexión a principios SWEBOK

1. Enfoque Centrado en el Usuario

Se definió una navegación simple con pocas pantallas principales:

Inicio

Catálogo de productos

Promociones

Carrito

Inicio de sesión

Menú de accesibilidad

Relación con SWEBOK:
Área de Software Requirements → Identificación de necesidades del usuario y experiencia de uso.

Se priorizó:

Acceso rápido a productos.

Reducción de pasos para comprar.

Claridad visual en promociones.

2. Arquitectura Modular de Pantallas

Cada vista funciona como un módulo independiente:

home

productos

promociones

carrito

login

accesibilidad

Esto permite mantenimiento y escalabilidad.

Relación con SWEBOK:
Área de Software Design → Diseño basado en componentes.

3. Navegación Clara y Predecible

Se implementó navegación jerárquica:
Inicio → Exploración → Selección → Compra.

Se evita la sobrecarga cognitiva del usuario.

Relación con SWEBOK:
Área de Human-Computer Interaction Design dentro de Software Quality.


4. Accesibilidad como Requisito Funcional (Enfoque Prioritario)

En este proyecto, la accesibilidad no fue considerada como una característica adicional, sino como un requisito funcional desde la etapa de análisis, es decir, una condición necesaria para que el sistema sea válido y usable por todos los tipos de usuarios.

Desde el diseño inicial se asumió que la plataforma debía ser utilizada por personas con diferentes capacidades físicas, sensoriales y tecnológicas. Por esta razón, el sistema incorpora un Menú de Accesibilidad dedicado, visible y disponible en todo momento, permitiendo que el usuario adapte la interfaz según sus necesidades sin depender de herramientas externas.

Funcionalidades implementadas:

Ajuste del tamaño del texto para usuarios con baja visión.

Navegación completamente funcional mediante teclado (sin necesidad de mouse).

Opciones de alto contraste que mejoran la legibilidad.

Inclusión de subtítulos y apoyo visual en contenidos gráficos.

Interfaz limpia, con baja carga cognitiva, pensada para personas con dificultades de atención.

Diseño responsivo que funciona incluso en dispositivos de bajo rendimiento o conexiones lentas.

Justificación de Ingeniería (SWEBOK)

Esta decisión se alinea con:

Software Requirements: La accesibilidad se definió como requisito verificable, no como mejora opcional.

Software Design: Se diseñaron componentes configurables que permiten personalización sin afectar la arquitectura.

Software Quality: Se aplican principios de usabilidad y estándares WCAG para garantizar inclusión digital.

Software Engineering Process: La accesibilidad se valida durante todo el ciclo de vida, no solo en pruebas finales.

Impacto en el Sistema

Incorporar accesibilidad como requisito funcional:

Reduce la exclusión digital.

Mejora la experiencia general para todos los usuarios, no solo aquellos con discapacidad.

Disminuye la necesidad de rediseños futuros.

Aumenta la calidad del producto desde una perspectiva ética y técnica.
