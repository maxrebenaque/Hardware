
QUE ES EL COMANDO FDISK?

  -Es un comando con muchas opciones que nos permite administrar , gestionar i ver todo lo relacionado con nuestro disco.
  
   -Con este comando podemos hacer todo tipo de ajustes a las particiones que tengamos en nuestro disco.
    
 
 
ALGUNOS COMANDOS UTILES:

  -Para ver todas las particiones existentes en nuestro sistema usamos el comando “-l”, que hará que se listen ordenadas por el nombre del dispositivo. 
  
  -Para ver todas las opciones que nos ofrece el comando fdisk usaremos el fdisk y a continuación la "m"
  
  -Para ver toda la tabla de particiones , usamos el comando fdisk y después la letra "p"
  
  -Para ver un disco específico usamos fdisk -l /dev/sdb " y el nombre del disco "
  
  -Para borrar una partición escojemos el disco que queramos y pulsamos la D 
  
  -Para crear nuevas particiones primero de todo debemos pulsar la "n" , ahora nos pedirá de que tipo la queremos, primaria letra "p", swap  "t" o extendida "e".
   
  -Para ver tamaño de partición lo hacemos con el comando fdisk -s
  
  -Para guardar cambios pulsamos w
