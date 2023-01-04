# Control-de-flujos-con-pandas
## Evaluación 1 del Módulo Fundamentos de Data Science


### Habilidades a evaluar

● Generar arrays ficticios con numpy
● Ejecutar un loop que devuelva los resultados requeridos.

### Descripción

¡Has logrado pasar la primera ronda de la selección de la Empresa TI en la cual postulaste en el Desafío anterior! A los reclutadores les interesó tu currículum una vez revisado, pero siguen existiendo al menos 10 competidores para el puesto, por lo tanto, te solicitan una vez más una serie de requerimientos para poder filtrar técnicamente a los postulantes. Pero esta vez, serán un poco más complejos. Revisémoslos.

### Requerimientos:

1.	Generar un par de arrays ficticios con numpy. Tip: Utilice la función linspace para generar un array entre 1 y 50, y un array entre 50 y 150. (1 punto)
2.	Ejecuta un loop que devuelva si el número en el primer array es par o impar. Tip: Utilice la función módulo para encontrar si el número es divisible por 2. (1 punto)
3.	Genere un loop con el segundo array que cuente las siguientes condiciones: ● Si el número es divisible por 2 o 3. ● Si el número es divisible por 2 y 3. ● Si el número es divisible por 3 pero no por 2. ● si el número no es divisible por 2 ni 3. (1 punto)
4.	Corrección de errores: Revisa el siguiente código y encuentra los errores a corregir. for i in range(100): print(I**2) (1 punto)
5.	Utilizando la misma base flights.csv debes hacer un loop y clasificar los meses con una cantidad de pasajeros menor a la media. Para ello: ● Genera un nuevo objeto que represente la media de passengers. ● Genera una columna en la base de datos que se llame underperforming y asígnele 0. ● Ejecuta un loop que recorra cada observación de passengers, donde si la observación es menor a la media de passengers se le asigne a underperforming un 1. ● Asignar unos en la columna underperforming ya creada, para ello utilice la función at de pandas. (3 puntos)
6.	Por último, haz un loop que clasifique los meses donde la cantidad de pasajeros se escapa de la tendencia. Para ello: ● Genera dos objetos que guarden la media general y la desviación estándar general de passengers. ● Genera una nueva columna en la tabla de datos que se llame outlier y asígnale 0. ● Ejecuta un loop que recorra cada observación de passengers, donde si la observación se escapa de la tendencia sea 1, de lo contrario 0. ● Para clasificar los casos que se escapen la tendencia, la observación debe satisfacer una de las siguientes condiciones: ○ La observación debe ser menor a la media menos la desviación estándar, o ○ La observación debe ser mayor a la media más la desviación estándar. ○ ¿Cuántas observaciones se pueden clasificar como casos extremos? (3 puntos)

