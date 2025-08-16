# 📻 SherlockCo - Radio Policial

100% custom y optimizada para servidores con QBCore y pma-voice.

##  Requisitos
- [QBCore Framework]
- [pma-voice]
- qb-inventory - (solo para el cacheo).
- qb-garage - (solo para el /depot de incautar)

## 🚀Instalación
1. Colocá la carpeta `sh-radio` en tu carpeta `resources`.
2. Agregá en tu `server.cfg`:
3. Solo qb-core, no me interesa esx. mas trabajo y la mayoria de servers en esx andan mal.

## Adicionales
- Soy nuevo en esto, me dan igual las lisencias. no se como va tebex y no le podes preguntar nada a nadie.

##  Explicacion de cada apartado
- Frecuencias aquí es el sistema de frecuencias que una sola radio se que posee, en la cual por "nui" son visibles quien está en linea en tiempo real, en esta misma pueden modificar disponibilidad con el boton que parece de apagado  y encendido, muy practico para ver en tiempo real quien está libre para acudir a un operativo - Multiples formas de comunicacion, por ejemplopuedes hablar con la persona que te encuentras en la misma frecuencia, sin embargo puedes hablar a un grupo mas grande que podría ser usada como radio global  ydecirle a todos algo en concreto. - luego pueden hablar directamente a una frecuncia en particular sin moverte visualmente de la que ya estas que sería muy practico para canales como tacs o mando. y esperando a que te asignen, se activan por ejemplo yo tengo en el boton "4" del mouse que es uno del costado la radio quele habla a tu compañero de la misma frecuencia que estes tu, tambien la que seria pra hablar de manera global está por defecto que sea con 
"numpad 9 " , "numpad 7  - mando", "Numpad 6 - Tacs " , "Numpad 4 Esperando asignacion", esta radio funciona mediante frecuencias reales, no por sistema de altavoz, que es visualmente similar. 
 en estas frecuencias no le puse un pull and drag o arrastar que se usa para mover a alguien a otra frecuencia - no le puse subir bajar volumen , por defecto se oye bien.  el boton con slide es para poner y sacar de servicio.

 - Atajos rapidos, acá se hace uso de una radio interna automatica de un color celesteque su chat deberia soportar, pues por el contrario no van a mostrarse, luego la /ipol, sería la radio interna real que cada uno escribe, usada para dar mas detalle de lo acontecido,con la correspondiente frecuencia implementada. los atajos son modificables desde el codigo, o para agregar mas incluso.

 - Referencias, muy util pra marcar a los ajentes con algun icono como tal, o separar operativos con colores dsitintos, funciona en tiempo real, las imagenes son algo cutre, pues las hice una a una y al ser chiquitas pierden calidad cuando se proyectan en el "nui".

 - Interaccion, aqui hay multiples formas de interactuar con otros jugadores o sus vehiculos,  todo los eventos han sido creados por mi digamos, excepto el de cachear o incautar, que llaman a eventos ya existentes, eso lo menciono en dependencias. aqui hay un sin fin de cossa por hacer, intente hacer gas pimienta, tambien un rastreador, pero el gas pimienta me resultaba complejo y me andaba a medias, el rastreador, si bien es normalito de hacer, me parecia muy chetado, así que debia tyener muchisimas limitaciones absurdas y no lo puse y así algunas cosas mas que no implemente por complejas o muy rotas.

 - Objetos, Aquí fuí por lo practico y funcional, no ibaa poner 1000 cosas que luego no se usan, solo dejé e cono, quesirve para practica de tiro, la barrera que dice "police" y es azul, vams me gustó esa. y los pinchos tienen problemas de entidad, no se muy bien por que, funionan pero no todos los pinchos que invocas, a uno mismo si, pero con el resto hay veces que no funcionan bien. y pór ultimo el Drone, vamos es un drone con camara, tiene un rango de 150mts, se regula desde el codigo, pero ya les digo que mas es muy roto, tiene un efecto de camra para darle mas inmersion, la distancia recorrida en pantalla pra saber hasta donde pueden ir y una camra termica ademas de tener zoom estilo binoculares en todas las camaras.

 - Placas - un sistema de placas simple pero completaente funcional, permite tanto ver quien está de servicio en tiempo real, al momento de abrir dicho menu, como tambien permite crear placas persistentes para cada agente, cuando arme la tablet tengo pensado unificar algunas cosas. el mostrar placa si vien se ve algo cutre, no me arecia relevante hacerlo mucho mas complejo,  o hay objetos, pra mi es una molestia tener que integrar objetos para este tipo de cosas, y no lo hace ni mas ni menos funcional.
