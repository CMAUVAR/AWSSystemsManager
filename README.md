# AWSSystemsManager
pasos a seguir para configurar Systems Manager
Implementación de aws Systems Manager Session
Crear un rol en IAM 
Vamos al IAM 
  Vamos a roles y agregamos un nuevo rol 
  Seleccionamos ec2 y damos click en siguiente 
  Buscamos la política “core” y selecciónanos la opcion que dice “amazon ssmmanagedinstancecore” y damos en siguiente 
  Opcional 
  Ponemos nombre a la clave y sino la dejamos en blanco, damos click en siguiente 
  Damos un nombre al rol y damos click en crear rol 
 
debemos Tener una instancia creada y asociar el usuario a la instancia para ello seleccionamos la instancia y damos click en seguridad y después en modificar rol de Iam
Después de esto iniciamos la instancia 
buscamos aws systems manager 
Buscamos la característica sesión Manager 
Damos click en iniciar sesión 
aparece la sesión que tenemos activa 
