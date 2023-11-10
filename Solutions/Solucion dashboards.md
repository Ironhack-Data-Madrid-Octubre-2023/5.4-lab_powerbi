# ENTREGA DASHBOARDS

Aquí dejo mi 'public.tableau' con el lab de Power Bi. 

No he sido capaz de descargar Power BI, a pesar de haber probado tanto con Parallels como con UTM. 

Lo elaboro en Tableau. 

#### URL es la siguiente:

https://public.tableau.com/app/profile/sara.pazo/viz/AnlisisCARS/DashClassiccars?publish=yes


## Dashboard 1. Orders Offices

En el primer dashboard se muestran las 3 primeras hojas. 

- **Estas se encuentran filtradas por país**: 
    
     - El mapa basado en Longitud y Latitud.  El color muestra suma de orderNumber (orders).  Se muestran detalles para Country (Offices).
     
     - Recuento de orders para cada Country (Offices) desglosado por Order Date año.  El color muestra detalles acerca de Country (Offices).  Las marcas se etiquetan por suma de Quantity Ordered. Los datos se filtran en Acción (Country (Offices)), lo que conserva 5 miembros.

     - Recuento de orders para cada Product Line desglosado por Country (Offices).  El color muestra detalles acerca de productLine (products). Los datos se filtran en Acción (Country (Offices)), lo que conserva 5 miembros. La vista se filtra en productLine (products), lo que conserva 7 de 7 miembros.


## Dashboard 2. Classic Cars

- Product Name y suma de Quantity In Stock.  El color muestra promedio de Quantity In Stock.  El tamaño muestra promedio de Quantity In Stock.  Las marcas se etiquetan por Product Name y suma de Quantity In Stock. Los datos se filtran en Product Line y Acción. El filtro Product Line conserva Classic Cars. La vista se filtra en suma de Quantity In Stock, lo que va de 68 a 9.772.

- Mapa basado en Longitud y Latitud.  El color muestra suma de Quantity Ordered.  Se muestran detalles para Country y Order Date año. Los datos se filtran en productLine (products), lo que conserva Classic Cars. La vista se filtra en Order Date año. 
Se da la posibilidad de cambiar en el Dashboard el año que queremos revisar. 


**Además, podemos seleccionar un país, y se filtrará el promedio de cantidad en Stock, para el país seleccionado**
