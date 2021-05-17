[Test driven development]

El encargado de re-introducirlo fue KENT BECK el creador de XP(extreme programming)
El dijo que el desarrollador deberia de crear sus proios unit test, y deberia usar del 25-50% de su tiempo escribiendo tests.

[Proceso de TDD]
-Escribir un test que ya se sabe que fallara
-Escribir codigo para que el test pase
-Si es necesario, refactor
-Repite los pasos, hasta tener software ya trabajando.

TDD se quedo corto pues no nos daba solucion a que cosas deberiamos testear, que tanto deberiamos de testear, y tampoco los hacia entender los test fallidos.



[BEHAVIOR DRIVEN DEVELPMENT]
Introducido por DAN NORTH en 2006.
Da un argumento diferente en como acercarse a TDD, estos argumentos ayudaban al desarrollador a saber donde empezar y que cosas testear en el codigo.
Toma principios de TDD y AGILE.
Usa la palabra behavior en vez de test.

Aqui los test describiran el compartamiento del sistema que intentamos construir.

Este vino por las fallas del modelo tradicional de software development

Porque es tan convincente? Porque nos permite entender el problema, ejemplo de la compañia VANGUARD

Puntos de inicio en BDD
Los clientes ya entienden  el producto que quieren
El criterio de aceptacion debe estar definido o en su mayoria
La historias de usario ya deben estar escritas

Para hacer unas buenas historias de usuario y no tener mala idea con el criterio de aceptacion se puede usar el card mapping.
El tiempo es crucial.


BDD se trata sobre dar  [Ejemplos concretos]para que todos entiendan como implementar una solucion.
Estos ejemplos concretos tienen:
-La historias de usuarios son muy detalladas y llenas de contexto.
-Ejemplos bien definidos nos permite tener test mas robustos y enfocados
-Si los ejemplos son abstreactos, costara mas crear test  que cuenten.

Formato de escenario BDD
-Scenariio: historia de usuario
-Given: algunas condiciones iniciales
-When: cuando un evento ocurre
-THEN: la salida

