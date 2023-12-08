 # MODELO DE CAJA
- Caracteristicas de la caja (width, height, etc)
- Calculo del espacio ocupado por la caja
    - Box-sizing
        - Content-box - espacio ocupado
            = widht + border + padding + (margin)
        - Border-box - espacio ocupado = width + (margin)
- Comportamiento de la caja (Tipo de elemento)
    - Display
        - block
        - inline
        - inline-block
 ## LAS PROPIEDADES DEL MODELO DE CAJA NO SON HEREDABLES

 ### SELECTOR UNIVERSAL (*)
 - Permite aplixar propiedades al momento de la creacion del elemento
 - Todos los elementos de html reciben las propiedades aplicadas con este selector
 - Su valor de especificidad es 0000
 - Se utiliza mucho para resetear box-sizing, margin y padding
     - Sacar todos los espacios no aplicados por nosotros



# PROPIEDADES DE TEXTO 
- Propiedades de texto
    - Font-family
        - Modificar la fuente
            - Fuentes seguras > Son fuentes que se encuentran en el SO del usuario:
                - 1ro tipografia deseada
                - 2do tipografia de respaldo
                - 3ro familia
            - fuentes traidas de bancos de fuentes (google fonts)
                - Font-family:'Cormorant SC', serif;
                  - 1ro tipografia deseada
                  - 2do familia
            - Fuente propia del proyecto
                - @Font-face
                  - Permite la configuracion de una tipografia
                    - src - La ruta del archivo que contiene la tipografia 
                    - font-family - nombre otorgado a la tipografia
            - Font-weight
                - Permite modificar el grosor
                - el navegador va aplicar el grosor que conozca
            - Font-style
                - Permite modificar el estilo de la tipografia
                    - regular
                    - italic
                    - cursive
            - text-align
                - Alinea el texto dentro del contenedor, en horizontal
            - text-transform
                - permite modificar como se escribe el texto en pantalla
            - text-decoration
                - permite agregar subrayados/


# BACKGROUND
