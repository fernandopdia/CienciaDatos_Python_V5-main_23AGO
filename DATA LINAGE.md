###Linaje de los datos (data lineage)

<p>El linaje (Jenifa, 2023) de datos es el proceso de rastrear el flujo de datos a lo largo del tiempo, facilitando la comprensión de dónde se han originado los datos, cómo han cambiado y su destino final dentro de la canalización de datos. Las herramientas de linaje de datos proporcionan un registro de los datos a lo largo de su ciclo de vida, incluida la información de origen y todas las transformaciones de datos que se hayan aplicado durante cualquier proceso de ETL o ELT. Este tipo de documentación permite a los usuarios observar y rastrear diferentes puntos de contacto a lo largo del trayecto de los datos, con lo cual las organizaciones pueden validar su precisión y coherencia. Se trata de una prestación esencial para asegurar la calidad de los datos en una organización. Normalmente se utiliza para ganar contexto sobre procesos históricos, así como para rastrear errores hasta la causa raíz.</p>

##What is data Linage?

<p>The data Linage is a process of found source and data moving through life cycle. Include information about data source, where have been and their direction, so any change to do it on the way.</p>

<p>El linaje de datos es un aspecto crítico de la gestión de datos y es importante por varias razones.</p>

<p>
•	Comprender la historia de los datos, incluida la forma en que se han transformado y utilizado a lo largo del tiempo.
•	Para mantener la calidad de los datos y garantizar el cumplimiento de los requisitos reglamentarios.
•	
•	Permitir el análisis de impacto de los cambios en los datos y procesos.
•	Ayuda en Auditoría y Gobernanza para tomar decisiones informadas a nivel empresarial basadas en los datos.
•	Mejora la eficiencia y eficacia general de los procesos de gestión de datos.</p>
   
<p>
Ejemplo
Se tienen los datos originados por una institución Solar Influences Data Analysis Center (Belgica) (Belgium, 2023).
<img src="https://miscclasesfpd.000webhostapp.com/a/sunspot_number.png">

<img src="https://miscclasesfpd.000webhostapp.com/a/datos_origen.png">
    
<img src="https://miscclasesfpd.000webhostapp.com/a/datos_filtrados.png">    

    
    
<p>Después se le da un tratamiento por medio de Jupyter Notebook -Python. Los valores (-1) sin registro de manchas se eliminan (usando pandas), para ofrecer un valor significativo que pueda ser susceptible de graficar (matplotlib).  </p>    


<p>Bibliografía
Belgium, R. O. (10 de septiembre de 2023). Sunspot Number. Obtenido de https://sidc.be/SILSO/datafiles</p>

<p>Jenifa, A. (25 de junio de 2023). Geekflare. Obtenido de ¿Qué es el linaje de datos? Ejemplo, técnicas y casos de uso: https://geekflare.com/es/data-lineage/<p>

