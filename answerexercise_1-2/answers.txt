1.- Diferencia de CMD y ENTRYPOINT en DockerFile
El objetivo principal de un CMD es proporcionar valores predeterminados para un contenedor 
en ejecución.Un ENTRYPOINT lo ayuda a configurar un contenedor que puede ejecutar como 
ejecutable.



2.- Diferencia de COPY y ADD en DockerFile
Aunque funcionalmente similar, es preferible COPY en la mayoría de los casos. 
Esto se debe a que la directiva ADD proporciona más funcionalidades
cómo Si el parámetro "src" de ADD es un archivo en un formato de compresión reconocido, 
se descomprimirá adicional, o permite que el "src" sea una URL por eso se debe usarse 
con precaución y solo cuando sea necesario.
