# proyecto-conversor-monedas-alura
Proyecto de conversión de monedas y temperaturas correspondiente al Challenge de Alura Latam Oracle-One Next Education que forma parte de su curso Backend


  # Estructura del proyecto
  ![Estructura del proyecto](https://raw.githubusercontent.com/Liriko/proyecto-conversor-monedas-alura/master/src/main/resources/ev25.png)
  
  En la estructura encontramos el proyecto divido en capas. 
  Los packages que representan esta jerarquía son los siguientes:
  
  - constantes (en su interior, la clase abstracta Constantes de la cual se referencian los distintos mensajes de la aplicación).
  - images (las imagenes del proyecto).
  - src.main.interfaces (en su interior la interfaz Front, destinada a la implementación de la parte visual de la aplicación).
  - src.main.model
    - divisas
      - Divisa (clase abstracta)
      - Dólar
      - Euro
      - LibraEsterlina
      - PesoChileno
      - WonSurcoreano
      - YenJapones
    - temperaturas
      - Temperatura (clase abstracta)
      - Celsius
      - Fahrenheit
      - Kelvin
  - src.main.business
    - logica
      - GestorDivisa
      - GestorTemperatura
    - pantalla
      - Bienvenida
      - ConversorDivisas
      - ConversorTemperatura
      - Licencia
  
  # Clases
  ![Detalle clases](https://raw.githubusercontent.com/Liriko/proyecto-conversor-monedas-alura/master/src/main/resources/ev26.png)
  
  Todas las clases, src.main.interfaces, y componentes se encuentran cuidadosamente comentados para el mejor entendimiento de su análisis.
  
  # Diseño
  En cuanto al diseño de esta aplicación; la solución implementada hace uso de la Programación orientada a objetos y sus paradigmas, Abstracción, Encapsulamiento, Herencia y Polimorfismo y adelanta el uso de la Colección HashMap como manipulador de divisas y temperaturas, para lo cuál se implementaron gestores, constantes, validaciones e src.main.interfaces, con el objetivo de desacoplar las distintas capas del proyecto, permitiendo la escalabilidad de la aplicación, asegurando la calidad y rendimiento de la misma.
  
  # Conclusión
  Este proyecto me permitió aplicar los conceptos impartidos en clases. Espero en el futuro poder modificar un poco el diseño para permitir un mantenedor de temperaturas y divisas para que el usuario pueda eliminar e incorporar sus propios elementos. En este minuto, gracias al diseño actual de la aplicación, ésto es posible solo a través de un requerimiento que, tras evaluado, puede constituir una mejora y posterior planificación de desarrollo.
  
  #¡Gracias Alura Latam!
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
