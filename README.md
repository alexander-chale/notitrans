# notitrans
Script que realiza una traducción de cualquier texto seleccionado utilizando el api de google translator, el cual es consumido asignándole un atajo de teclado al script


  @descripción: Script que realiza una traducción de cualquier texto seleccionado                  
  utilizando el api de google translator.                                                          
  @parametros: $text - El mensaje a traducir.                                                      
  @requisitos: apt-get install zenity wget xsel xclip                                              
  @indicaciones:                                                                                   
  Dar permiso de ejecución a este archivo                                                          
  chmod +x ~/notitrans                                                                             
   Añadimos el script a nuestro $PATH con el siguiente comando                                     
  sudo mv ~/notitrans /usr/local/bin/                                                              
                                                                                                   
    Ya nuestro script está listo, ahora tenemos que hacer que se active cuando usamos un atajo     
    de teclado, para ello debemos crear un acceso personalizado.                                   
                                                                                                   
    Para Cinnamon, GNOME y Unity, puedes crear un atajo de teclado personalizado accediendo a      
    Configuración del Sistema > Teclado > Atajos de Teclado > Atajos Personalizados,               
    donde debemos pulsar sobre añadir atajo personalizado e ingresamos el nombre del atajo,         
    en mi caso le coloque translate y en la Orden colocamos “notitrans” o el nombre que le           
    hayamos puesto a nuestro script                                                                
                                                                                                   
  @autor: Alexander Chale.                                                                         
  @fecha: 03-03-2020.                                                                              
  @todo:  Separar los párrafos según el texto y no por punto, esto hay que hacrlo en la consulta.  
