# Control de Usuarios
## Examen Practico .Net

Se solicita realizar un sistema para dar de alta Usuarios mediante MVC .NET el cual deberá contar con los siguientes módulos: 

* **Alta usuarios:**
  * Id, campo autogenerado por el sistema y no editable. 
  * Correo electrónico, el campo deberá validar la estructura del correo.
  * Usuario, campo alfanumérico. Longitud mínima 7 caracteres. 
  * Contraseña campo alfanumérico que contenga al menos:
    * Mayuscula
    * Minuscula
    * Simbolo
    * Numero
    * longitud deberá ser de por lo menos 8 caracteres
  * Estatus (El campo booleano): 
    * Activo
    * Inactivo
  * Sexo
    * Masculino
    * Femenino
  * Fecha de Creación, campo autogenerado y no editable. 
* **Baja usuarios (Solo baja lógica)**
* **Actualización usuarios:**
  * Se podrá actualizar los siguientes campos: 
    * Usuario
    * Contraseña
    * Correo Electrónico
* **Consulta Usuarios:**
  * El estatus deberá mostrarse de la siguiente manera: 
    * Activo ( ACTIVE ) 
    * Inactivo ( INACTIVE ) 
  * Utilizar un grid para mostrar la información delos usuarios que contenga la siguiente información: 
    * Id
    * Usuario
    * Correo
    * Sexo
    * Estatus
* **Reglas:**
  * Se deberá validad que no exista otro usuario con los mismos datos. (OPCIONAL) 
  * El id deberá ser generado automáticamente por la tabla de SQL.
  * Usar Stored Procedures para CRUD en SQL
* **Entregables:**
  * Solución de proyecto 
  * Script para generar base de datos .SQL o Archivo .BAK 
  
 









