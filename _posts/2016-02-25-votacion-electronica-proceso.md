---
layout: post
title:  "Votación Electrónica y Proceso Eleccionario"
description: Relación entre la Votación Electrónica y los Procesos Eleccionarios tradicionales, enfocado en el caso chileno.
img: jekyll-poster.png
date:   2016-02-25 14:50:00 +0200
categories: general
---
En el primer post de este blog me gustaría enfocarlo en esclarecer tres conceptos que me parecen imprescindibles a la hora de hablar de Sistemas de Votación Electrónica y temas relacionados. El primero será definir en términos exactos de qué trata una Votación Electrónica, es decir, que requisitos se deben cumplir para que digamos que una elección utiliza votación electrónica; el segundo y el tercero son más bien de caracter general sobre los Procesos Eleccionarios, específicamente los pasos que se siguen al momento de la votación y los requisitos de seguridad (derechos de los votantes) que una elección debe cumplir para que sea válida.

## VOTACIÓN ELECTRÓNICA

Vamos a restringir decir que un proceso eleccionario posee votación electrónica si es que éste utiliza cualquier medio tecnológico a la hora de que los votantes marquen su selección, emitan el voto o en el proceso de conteo de éstos (no es necesario que se utilice tecnología en todos ellos, con que se utilice en alguno, ya se considerará como votación electrónica). Con esto se excluyen procesos eleccionarios que utilicen tecnología en, por ejemplo, a la hora de publicar los resultados (como el proceso en Chile) o que utilicen tecnología a la hora de inscribir y confirmar la identidad de los votantes (para más detalles dirigirse a Partes de una Elección).

## PROCESO ELECCIONARIO

### Partes de una Elección

* Inscripción de Votantes: es necesario que exista un proceso en que los votantes se inscriban para votar, ya sea que deban cumplir algún requisito específico o sean inscritos automáticamente, es necesario preparar el padrón electoral para el día de la elección.

* Confirmación de Identidad: típicamente este paso se produce en el día mismo de la votación, previo a que el votante marque su selección (hay casos en que puede realizarse en otro momento, pero ello se abarcará cuando se hable de algún sistema que realice ese cambio). La confirmación de identidad se realiza para verificar que la persona que quiere emitir su voto se encuentre calificada para realizarlo (esté inscrita en el padrón electoral), además de no sufrir de suplantación de identidad presentando alguna identificación o por un sistema biométrico.

* Marcar la selección: paso en el cual el votante deja registro de su intención de voto en un medio en el cual posteriormente se pueda contabilizar. En una elección clásica, este paso corresponde a la marca que pone el votante en un papeleta de votación, frente al nombre del candidato de su preferencia.

* Emitir el voto: una vez que el votante marcó su preferencia, debe entregar el medio en el cual dejó registrada su preferencia, para que a posteriori (al final de la elección) pueda ser contabilizado y sumado con el resto de los votos. Este paso correspondería al hecho de depositar la papeleta en la urna dispuesta en la mesa de votación.

* Contabilizar los votos: al final de la elección, una vez cerradas las mesas, es necesario que se contabilicen y se sumen los votos individuales para obtener el resultado final de la elección. Esto puede ser realizado \”a mano\” contando uno por uno (como en una elección clásica) o de manera automatizada por algún mecanismo tecnológico.

* Publicación de Resultados: el último paso es la publicación de los resultados, donde tanto los votantes como los candidatos conocen el resultado final de la elección y se decretan los ganadores resultantes del proceso.

*NOTA*: existen procesos eleccionarios que pueden incorporar más pasos que los descritos anteriormente (dependiendo de los medios que se utilicen para realizar la votación) o que se junten dos o más pasos en uno. Pero en esencia es necesario que existan al menos los pasos descritos en la lista anterior.

## REQUISITOS DE SEGURIDAD

Una votación, ya sea electrónica o no, debe siempre contar con algunos requisitos de seguridad (visto desde el lado computacional) o dicho de otra manera, se deben asegurar algunos derechos hacia los votantes vitales para que la elección tenga la validez necesaria. Estos requisitos son los siguientes:

* Integridad: el resultado final de la elección coincide con la intención de todos los votantes. El voto es emitido tal como la intención del votante, y los votos son contabilizados tal como fueron emitidos.

* Privacidad del Voto: (1) nadie puede saber como votó un votante, (2) incluso si el votante intenta demostrar como votó. La parte (2) es más fuerte que (1), y es recomendable que los procesos eleccionarios implementen la versión fuerte de este requisito.

* Autentificación del Votante: solo votantes autorizados pueden emitir votos, y éstos deben hacerlo solamente las veces que se tiene permitido (en la mayoría de los casos pueden votar solamente una vez, aunque existen excepciones).

* Derecho a Voto: todas las personas autorizadas para votar tienen la oportunidad de realizarlo. Este requisito tiene relación con la accesibilidad para personas con discapacidad o acercar las mesas de votación a lugares de dificil acceso físico.

* Disponibilidad: el sistema es capaz de aceptar todos los votos emitidos durante el tiempo de votación, además de producir resultados después de un tiempo razonable.

Agradecimientos a [Alejandro Hevia](http://dcc.uchile.cl/~ahevia/) por la lista de requisitos de seguridad en los procesos de votación.