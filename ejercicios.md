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
    
 ### código de promedios por grupos-CONDICIONALES (sin switch)
 

    Algoritmo promedios
        definir nombre Como Caracter
        definir espaniol Como Real
        definir mate Como Real
        definir ciencias Como Real
        definir musica Como Real
        definir ingles Como Real
        definir promedio Como Real
        definir grupo Como entero
        escribir "Ingresa tu nombre"
        leer nombre
        escribir "¿A qué grupo perteneces?"
        leer grupo
        //condicionales dependiendo el grupo del alumno
        si grupo=1 Entonces
            escribir "¿Cuál fue tu calificación en español?"
            leer espaniol
            si espaniol<=10 y espaniol>0 entonces
                escribir "¿Cuál fue tu calificación en matemáticas?"
                leer mate
                si mate<=10 y mate>0 entonces
                    escribir "¿Cuál fue tu calificación en ciencias?"
                    leer ciencias
                    si ciencias<=10 y ciencias>0 Entonces
                        promedio=(espaniol+mate+ciencias)/3
                        si promedio>=6 entonces
                            escribir nombre, " fue aprobado con ", promedio
                        sino escribir nombre, " fue reprobado, ya que obtuvo ", promedio
                        FinSi
                    FinSi
                finsi
            FinSi
        finsi
        si grupo=2 Entonces
            escribir "¿Cuál fue tu calificación en español?"
            leer espaniol
            si espaniol<=10 y espaniol>0 entonces
                escribir "¿Cuál fue tu calificación en matemáticas?"
                leer mate
                si mate<=10 y mate>0 entonces
                    escribir "¿Cuál fue tu calificación en ciencias?"
                    leer ciencias
                    si ciencias<=10 y ciencias>0 Entonces
                        escribir "¿Cuál fue tu calificación en inglés?"
                        leer ingles
                        promedio=(espaniol+mate+ciencias+ingles)/4
                        si promedio>=6 entonces
                            escribir nombre, " fue aprobado con ", promedio
                        sino escribir nombre, " fue reprobado, ya que obtuvo ", promedio
                        FinSi
                    FinSi
                finsi
            FinSi
        finsi
        si grupo=3 Entonces
            escribir "¿Cuál fue tu calificación en español?"
            leer espaniol
            si espaniol<=10 y espaniol>0 entonces
                escribir "¿Cuál fue tu calificación en matemáticas?"
                leer mate
                si mate<=10 y mate>0 entonces
                    escribir "¿Cuál fue tu calificación en ciencias?"
                    leer ciencias
                    si ciencias<=10 y ciencias>0 Entonces
                        escribir "¿Cuál fue tu calificación en inglés?"
                        leer ingles
                        si ingles<=10 y ingles>0 Entonces
                            escribir "¿Cuál fue tu calificación en música?"
                            leer musica
                            si musica<=10 y musica>0 Entonces
                                promedio=(espaniol+mate+ciencias+ingles+musica)/5
                                si promedio>=6 entonces
                                    escribir nombre, " fue aprobado con ", promedio
                                sino escribir nombre, " fue reprobado, ya que obtuvo ", promedio
                                finsi
                            finsi
                        FinSi
                    FinSi
                finsi
            FinSi
        FinSi

FinAlgoritmo



###Ciclo FOR
#Pormedio de varios alumnos, FOR ANIDADO
    Algoritmo sin_titulo
        definir nombre Como Caracter
        definir veces, num Como Entero
        definir cal, prom, sum Como Real
        escribir "¿Cuántos alumnos serán?"
        leer num
        Para j<-1  Hasta num Con Paso 1 Hacer
            escribir "Ingresa nombre del alumno ", num
            leer nombre
            escribir "¿Cuántas calificaciones tiene ", nombre, "?"
            leer veces
            Para i<-1 Hasta veces Con Paso 1 Hacer
                escribir "¿Cuál fue su calificación ", i, "?"
                leer cal 
                sum=sum+cal
            Fin Para
            prom<- suma/veces
            escribir "El promedio de ", nombre, " es ", prom
        Fin Para


    FinAlgoritmo

