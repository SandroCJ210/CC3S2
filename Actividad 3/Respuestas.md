# Actividad 3: Integración de DevOps y DevSecOps con HTTP, DNS, TLS y 12-Factor App
**Nombres y Apellidos:** Sandro Alfredo Carrillo Jordán

## Parte teórica

### 1. Introducción a DevOps: ¿Qué es y qué no es? Explica DevOps desde el código hasta la producción, diferenciándolo de waterfall. Discute "you build it, you run it" en el laboratorio, y separa mitos (ej. solo herramientas) vs realidades (CALMS, feedback, métricas, gates).

Devops es como una filosofía, una cultura y práctica de organización que busca reducir el choque entre el desarrollo y las operaciones, llevando así el código desde el repositorio hasta producción de manera rápida.

**¿Qué es?** Un flujo continuo, entonces se tiene código, integración, pruebas, despliegue y monitoreo. Un modelo cultural.
**¿Qué no es?** Un conjunto de herramientas. Un cambio de programas a usar, o de tecnología en general.

Waterfall es secuencial y lineal, ya que cada fase tiene que estar completada antes de pasar a la siguiente, el feedback es poco por lo que si hay fallos hay retrasos grandes. En cambio en DevOps los ciclos son cortos y automatizados, con continuo feedback. 

### 2. Marco CALMS en acción: Describe cada pilar y su integración en el laboratorio (ej. Automation con Makefile, Measurement con endpoints de salud). Propón extender Sharing con runbooks/postmortems en equipo.

*C*ulture: Todas las buenas prácticas de esta metodología se convierte en una cultura.
*A*utomation: Se usa makefile en esta laboratorio para la automatización
*L*ean: Simple pero robusto. 
*M*easurement: Se usan logs de Flask, métricas de red y endpoints de salud.
*S*haring: El repositorio de la actividad está relacionado a esta letra.