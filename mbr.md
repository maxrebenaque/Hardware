EL MBR

  De que esta formado el mbr? 
     El mbr (master boot record) esta formado por 3 cosas, tabla de particiones , gestor de arranque y la signature.
     
   
   
  TABLA DE PARTICIONES  ( 64 bytes ) 
  
    Está alojada en el MBR, en la tabla hay toda la información básica sobre las particiones , 
    si es arrancable , si no lo es, el formato , tamaño y el sector de inicio.
    
    
   GESTOR DE ARRANQUE ( 446 Bytes )
   
     El gestor de arranque, tambien llamado como cargador, es un   programa que carga el sistema operativo.
     
     Cuando el ordenador se apaga , la BIOS realiza algunas pruevas y transfiere el control al MBR.
      
    
   SIGNATURE ( 2 bytes )
   
     Los dos ultimos bytes del secotr de arranque contienen 2 caracteres ( 55h , AAh ) 
     que son denominados firma del sector de carga.
