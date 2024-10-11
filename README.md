'# SoftwareLibreII
Laboratio2, Computo 2

****************************  PRIMERA PARTE   **********************************

1.1.1.Mostrar el estado del sistema 
(systemctl status)

1.1.2.Listar unidades en ejecución: 
(systemctl list-units --type=service --state=running)

1.1.3.Ver una lista de todas las unidades activas que systemd conoce. 
(systemctl list-units --all)

1.1.4.Listar unidades que han fallado.
(systemctl --failed)

1.1.5.Poner el sistema en suspensión
(systemctl suspend)

1.1.6.Poner el sistema en estado de reposo híbrido 
(systemctl hibernate)

1.1.7.Realiza un apagado completo, usando el comando. 
(systemctl poweroff)

1.1.8.Creará un script en gist.github.com en el cual definan
los pasos y comandos para la creación de esta parte


***************  SEGUNDA PARTE   ***********************

2.1. Crear un grupo llamado USULUTAN
(sudo groupadd USULUTAN)


2.2. Crear un grupo llamado SANMIGUEL
(sudo groupadd SANMIGUEL)


2.3. Dentro del grupo USULUTAN crear 2 usuarios, uno con el
nombre "OSCAR" y el otro usuario seria "LUIS".
(sudo useradd -m -G USULUTAN OSCAR
sudo useradd -m -G USULUTAN LUIS)


2.4. Dentro del grupo SANMIGUEL crear 2 usuarios, uno con el nombre de su código de estudiante y el otro usuario seria su nombre.
(sudo useradd -m -G SANMIGUEL USSS005022
sudo useradd -m -G SANMIGUEL IvaniaMatas)


2.5. Luego cambiar el nombre del grupo USULUTAN a UGB_USU.
2.6. Luego cambiar el nombre del grupo SANMIGUEL a UGB_SM.
2.7. Así mismo, creará un script en gist.github.com en el cual
definan los pasos y comandos para la creación de usuarios y
grupos en GNU/Linux
