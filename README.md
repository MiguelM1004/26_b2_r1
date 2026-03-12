## 1. Título actividad: Actividad 1 - Configuración y Pruebas de Proyecto Spring Boot
Estudiante: Miguel Ángel Muñoz López

## 2. Instancia de base de datos

La instancia de Prisma.io no es pública.
Se adjunta evidencia mediante captura de pantalla.

![Base de datos creada](imagenes/instancia_BD.png)

## 3. Conexión en prisma
![Configuración Prisma](imagenes/credenciales.png)

## 4. Log consola Spring Boot y ejecución del proyecto

La aplicación inicia correctamente. Establece una conexión exitosa con la base de datos PostgreSQL en prisma.
![Conexion y ejecución](imagenes/punto_4.png)

## 5. Evidencias CRUD

## POST
Creación de 3 estudiantes:
![post](imagenes/estudiante1.png)
![post](imagenes/estudiante2.png)
![post](imagenes/estudiante3.png)

## GET ALL
Se muestran los estudiantes registrados
![GET](imagenes/get_all.png)

## GET ID
Muestra estudiante por su respectivo ID
![GET](imagenes/get_id.png)

## GET EMAIL
Muestra estudiante por su respectivo correo
![GET](imagenes/get_email.png)

# PUT
Actualiza la información de cada estudiante
![PUT](imagenes/put.png)

## DELETE
Se eliminó a un estudiante de los creados
![DELETE](imagenes/delete.png)

## 6. Captura de pantalla resultado pruebas internas
Se ejecuta comando './mvnw test', donde se verifica que las pruebas unitarias y de integración se realizan de manera exitosa y pasan.
![Resultado pruebas internas](imagenes/pruebas_internas.png)