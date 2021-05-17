Guerkin es un  bussines-readable, domain-specific y lenguaje que describire el comportamiento de un software pero no como ese comportamiento esta siendo implementado.
Sirve para automatizar test y como documentacion de la app

Provee una estructura para documentacion de ejemplos.
Aunque es un lenguaje de programacion es mas enfocado para ser facilmente leido por humanos.
![[Gherkin sintax.png]]

Feature: 
Es una keyword, es neutral
Contiene el nombre de una funcion y una brebe descripcion

Scenario:
Es un ejemplo concreto de como e sistema deberia comportarse.
Se escribe como pass/fail examples
Cada funcion generalmente tiene entre 5-20 escenarios

Given:
Describe el contexto del escenario

When:
Identifica el evento o action de un actor en el sistema

Then:
Es el resultado o salida.