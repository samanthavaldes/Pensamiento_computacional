# ejercicio de interés compuesto

![image](https://user-images.githubusercontent.com/126004528/220738073-1b1a3786-384d-4e29-949d-278899ed95e8.png)

## PsInt

    Algoritmo sin_titulo
      definir prestamo Como entero
      definir mensualidad Como entero
      definir total como real
      definir interes Como Real
      escribir "¿De cuánto es el préstamo que recibiste?"
      leer prestamo
      escribir "¿En cuántos meses debes pagarlo?"
      leer mensualidad
      interes<-0.08
      //operaciones
      total<-prestamo*((1+(interes))^mensualidad)
      //salida
      escribir "El pago total con interés compuesto por un préstamo de ", prestamo, " será de ", total

    FinAlgoritmo
