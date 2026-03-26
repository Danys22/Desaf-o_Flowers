Problematica:
La actualidad del servidor de archivos de la compañía es que los discos duros sufren fallos regularmente, y no hay ningún tipo de redundancia, 
esto significa que, si se falla un disco, la información que almacena se pierde de forma definitiva. Dicha situación es un problema crítico 
para la continuidad del negocio, ya que los datos almacenados pueden llegar a ser información importante como documentaciones empresariales, 
bases de datos, archivos de clientes, etc. 

La pérdida de los datos podría causar interrupciones operativas, pérdida de dinero y afectación para la reputación de la compañía. Sin 
considerar, además, que la carencia de redundancia impediría la recuperación rápida del sistema y podría alargar el tiempo de inactividad 
(downtime) en caso de fallo.

Mi propuesta de solucion:
Se propone la implementación de un sistema RAID 1 (Redundant Array of Independent Disks), el cual consiste en duplicar 
la información en dos discos duros de manera simultánea. RAID 1 es una solución adecuada para esta empresa debido a su simplicidad y 
efectividad en la protección de datos. Aunque no mejora significativamente el rendimiento, garantiza la integridad de la información, 
lo cual es prioritario para la empresa.

En este tipo de configuración, ambos discos contienen exactamente los mismos datos. Si uno de los discos falla, el sistema puede seguir
funcionando utilizando el disco restante sin pérdida de información.
