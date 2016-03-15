# SCRUM AND XP FROM THE TRENCHES

## Backlog

Sean como *historias*.

### Campos

* ID: automático
* Name: descriptivo
	* Ejemplo: *“See your own transaction history”*
* Importance: Desde 0 hasta `n`
	* No usar *Prioridad*, pues todo suele ser `1`.
* Initial estimate: estimación de cuánto trabajo (`man * days`).
* How to Demo: Cómo será mostrado en el *Sprint demo*.
	* Con Test Driven Development es más fácil y escrito en psudo-código.
* Notes: Clarificaciones, referencias, etc.

> Todo lo técnico o sugerencias de cómo lograr algo que vayan en las notas.

> Separar historias si son muy largas o complejas, a modo de que quedan bien dentro de un sprint.


## Sprint Planning

El objetivo es que el equipo tenga la suficiente información para trabajar distribuidos.

En específico:

* Sprint goal.
	* Debe ser definido sí o sí.
* Lista del equipo y su nivel de disponibilidad
* Definir Backlog
	* Importante definir las historias para este sprint y su estimado.
* Definir demo date
	* Debe ser definido sí o sí.
* Definir lugar y hora del *daily scrum*.
* Tiempo de reunión: ~3 horas cada ~3 semanas.

### Tips

* Asegurarse que el backlog es *shipeable* antes de empezar la reunión.
* Dejar *gaps* entre cada *historia*.
* El product owner debe entender cada historia.

### El Product Owner debe ir a las reuniones de Sprint

La **Importancia** y el **Scope** son definidos por el Product Onwer. El **Estimado** por el equipo. Se deben hacer preguntas para refinar el estimado y definir bien el *scope*.

Es bueno preguntar a todos la estimación de las historias, de ser muy discrepantes puede que no todos hayan entendido bien.

Implícitamente está la:

* **calidad interna**: Código interno. Ojalá nunca negociar (deuda técnica).
* **calidad externa**: Lo que vé y usa el usuario.

### Planear el Sprint

* Calcular horas en página 36.
* El *ayer fue* no sirve.
* Usar tarjetas IRL. Eso mantiene despiertos y participativos.
* Definir bien el *done*.
* Hacer que todos estimen cada historia
* Confirmar con el *How to demo* si todos entendieron la historia.
* Una vez listo, asegurarse de comunicarlo con toda la compañía.

![image](https://cloud.githubusercontent.com/assets/7570744/13712896/dac03eda-e7a4-11e5-82a6-1dc18a4ebf45.png)

* En caso de tener múltiples equipos, es mejor que las fechas de los sprint coincidan.

#### Story vs Task

Las Story son enviables y mostrables al Product Owner. Las Task son no-envíables, muy técnicas o no le interesan al Product Owner (les asignará baja importancia).

### Scrum diario

![image](https://cloud.githubusercontent.com/assets/7570744/13712924/ffb04f64-e7a4-11e5-8939-18536e9feabd.png)

#### Burndown

Eje `x` tiene los días del sprint. Eje `y ` la estimación de story points del equipo restantes para cumplir el sprint, en el día `x`.

### Importancia de los demos

* El equipo se lleva crédito y se siente bien
* Otros ven en qué van.
* Feedback de los stakeholders
* Evento social :)

### Retrospectivas

* Lo bueno
* Lo que se pudo mejorar
* Cómo mejorar

## XP y Scrum

* Pair programming
* TDD
* CI
* Informative Workspace
* Coding Standard

## Release

Problema: después de un sprint y de hecho el release, durante el siguiente sprint serán reportados bugs.

Tips:

* Asegurar calidad del código.
* Seguir construyendo cosas nuevas, pero priorizar arreglar lo que está en production.

## Equipos

Estrategias:

* Equipos por componentes.
* Equipos de historias.

Elegir dependiendo del caso.

---

TODO:

* Story points
