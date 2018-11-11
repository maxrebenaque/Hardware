
QUE ES IONCIE?


  -Basicamente , ionice es un programa que nos permite hacer un control de la prioridad que tienen acceso algunos recursos
    de lectura y escritura, asi el usuario puede decidir como los quiere poner.
  
  
  
  Podemos definir que cierto proceso pertenezca a tres clases:
  
  Idle: El proceso solo podra acceder a disco cuando el resto de programas no lo hayan pedido, ( solo como root )
  Best effort: Permite el uso de un parámetro como prioridad: 0 como la mayor prioridad y 7 como la prioridad más pequeña.
  Real time: Tan pronto como pide el acceso se le concede. Igual que en el caso de Best effort, permite el uso de prioridades del 0 al 7.

  
