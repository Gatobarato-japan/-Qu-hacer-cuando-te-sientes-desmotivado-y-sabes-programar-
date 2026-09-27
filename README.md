¿Qué hacer cuando te sientes desmotivado y sabes programar?
Bitácora del experimento: problema real → investigación → IA → MVP
1. La idea del experimento
La idea fue aprovechar un momento de inspiración nocturna para hacer un proyecto pequeño en lugar de quedarse esperando motivación. La regla principal: no inventar un problema solamente para tener algo que programar. Primero había que encontrar una fricción real y comprobar que fuera suficientemente pequeña para convertirla en un MVP de una noche.
2. Flujo de trabajo
ChatGPT: investigar y descubrir un problema real.
Claude: elaborar una posible solución y estructura.
Yo: programar y convertir la idea en algo funcional.
Stanley Studio: preparar un clip para mostrar el resultado en TikTok.
El objetivo no era crear una startup completa. Era comprobar si una observación real podía convertirse rápidamente en software funcional.
3. Reglas para encontrar el problema
Máximo 10 minutos de observación pasiva por comunidad.
No entrevistar ni preguntar directamente a los miembros.
Buscar frases o situaciones que indiquen fricción: “no puedo…”, “tengo que…”, “necesito…”, “¿cómo hago…?”, “¿alguien tiene…?”, “me gustaría…”.
Descartar problemas demasiado grandes, ambiguos o difíciles de programar en una noche.
Si una comunidad no produce suficiente señal, cambiar de comunidad.
No construir antes de tener una señal razonable.
4. Primer intento: Discord
La primera comunidad investigada fue un servidor de fans de Tokomaru. La actividad era principalmente conversación de fandom, memes, personajes y proyectos personales.
Una conversación sobre desahogarse terminó con la idea de necesitar un canal de desahogo.
Varios usuarios comentaron sobre ocultar hobbies a familiares por miedo a ser juzgados.
Un creador estaba desarrollando una novela visual y proyectos relacionados.
Apareció una búsqueda de un archivo de contenido de YouTube que no parecía estar disponible públicamente.
Conclusión: había conversaciones interesantes, pero no un problema pequeño, concreto y claramente programable. El resultado fue válido: la comunidad no dio suficiente señal.
5. Segundo intento: Reddit
Reddit parecía más adecuado porque muchas publicaciones describen directamente frustraciones, dificultades o cosas que los usuarios desearían resolver.
Primero se probó una búsqueda demasiado directa de ideas de software. Eso se descartó porque convertía la investigación en pedirle a Reddit que diera ideas de productos. Después se decidió buscar problemas dentro de comunidades concretas.
6. Prueba con anime
Se investigaron comunidades relacionadas con anime. Mission: Yozakura Family produjo críticas sobre ritmo, bromas repetitivas y preferencias narrativas, pero eran principalmente opiniones sobre la obra, no problemas prácticos que justificaran programar una herramienta.
Tougen Anki tampoco produjo una señal útil con las búsquedas realizadas.
Conclusión: cambiar de tema otra vez.
7. El cambio importante: buscar creadores
En lugar de buscar un fandom específico, se decidió investigar directamente a creadores. La búsqueda se orientó a frases como “as a creator” y “I hate”, buscando frustraciones reales.
Ahí apareció una publicación sobre Karat y las finanzas de creadores.
8. El problema encontrado
El creador explicaba que su sistema bancario funcionaba técnicamente, pero que odiaba la cantidad de energía mental necesaria para seguir los pagos y explicar depósitos aleatorios. No buscaba funciones sofisticadas: quería que el proceso funcionara silenciosamente en segundo plano.
Esta fue la primera señal suficientemente concreta para pasar a construir.
9. Definición del problema
Un creador recibe múltiples movimientos de dinero y debe gastar esfuerzo mental identificando de dónde vienen, especialmente cuando aparecen depósitos que no reconoce inmediatamente.
Revisar movimientos manualmente.
Identificar depósitos desconocidos.
Recordar o explicar de dónde proviene cada movimiento.
Automatizar lo repetitivo y dejar al usuario solamente lo que requiere revisión.
La publicación de Reddit fue una señal inicial, no una prueba de que todos los creadores tengan esta necesidad.
10. Decisión de MVP
Se eligió una aplicación web sencilla. No se intentó conectar cuentas bancarias ni crear una plataforma financiera.
Entrada mínima: movimientos monetarios con fecha, descripción y monto. Salida: clasificación automática, identificación de movimientos desconocidos y posibilidad de guardar patrones.
11. Evolución del MVP
Importación de archivos CSV.
Detección de ingresos y gastos.
Cálculo de ingresos, gastos y resultado neto.
Explicación de por qué un movimiento fue clasificado.
Panel de movimientos que requieren atención.
Resolución rápida de movimientos desconocidos.
Guardado de patrones en el navegador.
Desglose de ingresos por fuente.
Búsqueda de movimientos.
Exportación a CSV y JSON.
La versión actual implementa este flujo en un único archivo HTML con JavaScript y almacenamiento local.
12. Flujo final
Importar movimientos → procesarlos → detectar patrones → clasificar → separar desconocidos → resolver los que requieren atención → guardar el patrón → reutilizarlo en el futuro.
La idea central no es hacer contabilidad. Es reducir la cantidad de trabajo mental necesario para entender movimientos de dinero.
13. Lo que NO se construyó
Conexión directa con bancos.
APIs bancarias.
Sistema de cuentas o login.
Aplicación móvil.
Base de datos externa.
Sistema de pagos.
Una plataforma financiera completa.
Estas funciones quedaron fuera porque el objetivo era demostrar velocidad de construcción y capacidad de resolver una fricción concreta.
14. Estado del experimento
El MVP quedó funcional y preparado para la demostración. La siguiente pregunta ya no es técnica: es si una persona que realmente tenga este problema considera que la herramienta le ahorra trabajo.
También funciona como demostración de una habilidad: observar un problema, investigar, diseñar una solución, programarla y terminar con algo que funciona.
15. Relación con el TikTok
Título: “¿Qué hacer cuando te sientes desmotivado y sabes programación?”
Problema encontrado en Reddit.
Investigación rápida.
Código.
Interfaz.
Importación de movimientos.
Clasificación automática.
Resolución de un desconocido.
Resultado final.
El video no necesita voz. La historia puede contarse visualmente. La idea no es afirmar que se creó una gran empresa ni que el producto ya tiene usuarios: es mostrar qué puede ocurrir cuando alguien que sabe programar deja de esperar una idea perfecta y empieza a buscar un problema concreto.
16. Resultado
El experimento empezó sin una idea clara de qué programar. Hubo comunidades descartadas, búsquedas que no produjeron nada útil y varias ideas que no pasaron el filtro.
Finalmente apareció una señal concreta, se convirtió en una solución pequeña y terminó en un MVP funcional.
La lección: cuando falta motivación para programar, quizá no haga falta buscar otra tecnología. Puede ser suficiente buscar una fricción real y darse permiso para construir una solución pequeña.
Nota de trazabilidad
La publicación de Reddit funcionó como señal inicial del problema; no demuestra por sí sola que exista una necesidad general en todos los creadores. El MVP actual sí implementa importación CSV, clasificación por patrones, ingresos/gastos/neto, atención de desconocidos, desglose por fuente y exportación.
