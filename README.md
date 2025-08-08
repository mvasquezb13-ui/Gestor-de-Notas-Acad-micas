Gestor de Notas Académicas

Descripción del problema y requisitos

Tener un control de las notas es muy importante para los estudiantes, y tener un metodo mas practico para ingresar notas es muy funcional para los docentes.
El proyecto de sistema de Gestor de Notas Académicas tiene como objetivo facilitar a las personas que desean registrar, consultar y ingresar las notas de los estudiantes en distintos cursos. El sistema esta diseñado para todos los estudiantes, docentes o las personas que desean tener un control organizado de sus notas academicas, sin utilizar plataformas con dificultad.  

El sistema de gestor de notas cubre la nesecidad básica, como agregar nuevas notas, ver el rendimiento académico de los estudiantes, actualizar registros ya existentes y poder borrar información que ya no se necesita. El sistema ofrece una experiencia facil y directa, para personas que desean tener un analisis de las calificaciones en distintos cursos. 

Funcionalidades 
1. Registrar un nuevo curso y su nota.
2. Mostrar todas las notas registradas.
3. Eliminar un curso y su nota.
4. Calcular el promedio general de las notas.
5. Salir del sistema.

   
Diseño del menú principal en pseudocódigo


INICIO
IMPRIMIR "Seleccione una opción:"
  
MIENTRAS opción > "5" HACER
    IMPRIMIR "Gestor de Notas Académicas"
    IMPRIMIR "1. Registrar nuevo curso y nota"
    IMPRIMIR "2. Mostrar todas las notas"
    IMPRIMIR "3. Eliminar curso y nota"
    IMPRIMIR "4. Calcular promedio general"
    IMPRIMIR "5. Salir"
Leer opción   
    SI opción = "1" ENTONCES
        (registrar curso y nota)
    SINO SI opción = "2" ENTONCES
        (mostrar todas las notas)
    SINO SI opción = "3" ENTONCES
        (Eliminar curso y nota)
    SINO SI opción = "4" ENTONCES
        (Calcular promedio)
    SINO SI opción = "5" ENTONCES
        IMPRIMIR "Saliendo del gestor de notas."
    SINO
        IMPRIMIR "Opción no valida. Intente de nuevo."
    FIN_SI

FIN_MIENTRAS

FIN




