# 4.1 Cambio Contraseña

## 4.1.1 Description and Priority
Feature que verifique la identidad del usuario y proceda a actualizar su contraseña en la base de datos. 
- Priority: High

## 4.1.2 Stimulus / Response Sequences
- Usuario inicia sesión.
- Usuario da click en botón de cambiar contraseña. 
- Pedir usuario y contraseña vieja.
- Enviar notificación a correo institucional para verificar que sea el usurio el que está solicitando el cambio de contraseña.
- Solicitar nueva contraseña.
- Verificar que la contraseña escrita cumpla con los parámetros de seguridad necesarios. 
- Requerir que el usuario la escriba una vez más la nueva contraseña para verificar que la escribió de manera correcta. 
 
## 4.1.3 Functional Requirements
- REQ-1: Verificar la identidad del usuario.  
- REQ-2: Asegurarse de que la nueva contraseña no sea similar a la contraseña anterior. 
- REQ-3: Verificar que la contraseña escrita cumpla con los parámetros de seguridad necesarios. 
- REQ-4: Hacer el hashing necesario para proteger la contraseña.  
- REQ-5: Guardar la contraseña en la base de datos. 
