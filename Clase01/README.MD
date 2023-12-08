# CSS - CASCADING STYLE SHEETS (Hoja de estilo en cascada)


### SELECTORES  
- Elementos que nos permite indicar que queremos modificar.
 1. **Basico**  
     -  id: Se utiliza para modificar el elemento con el atributo id correspondiente
     - class: Se utiliza para modificar el/los elemento/s con el atributo class correspondiente
     - :root: permite aplicar estilos al documento
     - * : permite aplicar estilos al momento de la creacion del elemento
     - Etiqueta / Elemento: Se utiliza 

 2. **Compuestos** - Se generan combinando selectores basicos y/o compuestos.
    - **Grupal:** Permite agrupar varios selectores para aplicar el mismo estilo.
    - **Descendente:** Permite modificar un elemento por que se encuentra dentro de otro
      - Hijo de (dentro de) - div p
      - Hijo directo de (directamente dentro de) div > p
    - **Adyacente:** Permite modificar un elemento por que es hermano de otro.
       - Hermano directo de: En el documento se encuentra en la linea posterior

### FLUJO DE TRABAJO 👜
Indica como se resuelve la vista cuando hay mas de un selector aplicando las mismas propiedades de estilo con distinto valor sobre un elemento.

- **Herencia:** 
  - Los elementos hijos recibiran los estilos aplicados al padre.


- **Importancia:** 
  - Los elementos hijos recibiran los estilos aplicados a su padre mas cercanos.



- **Especificidad:** 
  - ![especificidad](/Img/Especificidad.PNG)
  - Cuanto mas especifico el selector utilizado, mas relevante el estilo aplicado.
Valor de especificidad del selector 
   - Cualquier selector supera a las reglas de herencia e importancia


* Calculo de valor de especificidad de selector descendente.
  
  - div p = 0001 + 0001 = 0002
  - .unaClase p = 0010 + 0001 = 0011