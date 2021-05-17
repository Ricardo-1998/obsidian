Explica una manera ideal de estructurar tests
Es una representacion visual de la cantidad recomendada de test coverage que deberia exister a lo largo de cada tipo de test.

Consiste en trest niveles
![[piramideTest.png]]

UI:Son los mas largos, intentan recrear la experiencia de usuario

INTEGRATION: Testea multiples servicios.
Toman un poco mas que los unit, son test que involucran la db, file systems y otras aplicaciones. API test igualmente son populares aqui.

UNIT: Se testean una funcion llamando a esa funcion. Es de los mas rapidos, y de los que deberia de haber una gran cantidad de ellos.

