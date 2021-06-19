#-Eliminar contraseñas temporales
wmic path Win32_UserAccount WHERE Name=’username’ set PasswordExpiries=false
#-Abrir programador de tareas a la cmd
Taskschd. msc
