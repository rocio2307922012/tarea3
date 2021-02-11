# tarea3
Codigo
Alumnos=[
{
    "alumno":" " ,
    "nua":" ",
    "Carrera":" ",
    "Inscripcion":" "
},
{
   "alumno":" " ,
    "nua":" ",
    "carrera":" ",
    "inscripcion":" "  
},
{
    "alumno":" " ,
    "nua":" ",
    "carrera":" ",
    "inscripcion":" "
}]

alumno_1=input("Introduce el nombre del alumno: ")
nua_1=int(input("Introduce el número de control: "))
carrera_1=input("Introduce la carrera del alumno: ")
inscripcion_1=float(input("Introduce el precio de la inscripción: "))

alumno_2=input("Introduce el nombre del alumno: ")
nua_2=int(input("Introduce el número de control: "))
carrera_2=input("Introduce la carrera del alumno: ")
inscripcion_2=float(input("Introduce el precio de la inscripción: "))

alumno_3=input("Introduce el nombre del alumno: ")
nua_3=int(input("Introduce el número de control: "))
carrera_3=input("Introduce la carrera del alumno: ")
inscripcion_3=float(input("Introduce el precio de la inscripción: "))




Alumnos[0].update({'alumno':alumno_1})
Alumnos[0].update({'nua':nua_1})
Alumnos[0].update({'carrera':carrera_1})
Alumnos[0].update({'inscripcion':inscripcion_1})

Alumnos[1].update({'alumno':alumno_2})
Alumnos[1].update({'nua':nua_2})
Alumnos[1].update({'carrera':carrera_2})
Alumnos[1].update({'inscripcion':inscripcion_2})

Alumnos[2].update({'alumno':alumno_3})
Alumnos[2].update({'nua':nua_3})
Alumnos[2].update({'carrera':carrera_3})
Alumnos[2].update({'inscripcion':inscripcion_3})

print(Alumnos[0])
print(Alumnos[1])
print(Alumnos[2])
