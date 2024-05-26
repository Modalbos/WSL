# Instalación de Windows Subsystem for Linux (WSL)

## Paso 1: Instalar WSL a través de la terminal

Para instalar WSL, abre una terminal de PowerShell como administrador y ejecuta el siguiente comando:

```powershell
wsl --install
```
![image](https://github.com/Modalbos/WSL/assets/148746995/ee684103-6724-4899-9925-d41dac0b1108)

de base te instala ubuntu

Paso 2: Reiniciar el sistema
Para que los cambios surtan efecto, es necesario reiniciar el sistema. Una vez reiniciado, inicia Ubuntu.
![image](https://github.com/Modalbos/WSL/assets/148746995/a998018d-d6ea-46d1-9d71-d2b1fe4da6d9)

![image](https://github.com/Modalbos/WSL/assets/148746995/4decfec2-8c0a-42f6-8128-17c97dfe889f)



Paso 3: Actualizar Ubuntu
Una vez que Ubuntu esté iniciado, puedes actualizar y mejorar los paquetes ejecutando los siguientes comandos:

```powershell
sudo apt update
sudo apt upgrade
```

![image](https://github.com/Modalbos/WSL/assets/148746995/9f762162-6c9f-4cce-b53f-0a6fbdfbe66e)

## Instalación de una distribución específica como Debian
Si deseas instalar una distribución específica como Debian, primero debes buscarla. Luego, instala Debian ejecutando el siguiente comando en PowerShell:

Paso 1: buscamos la distribucion
```powershell
wsl --list --online
```

![image](https://github.com/Modalbos/WSL/assets/148746995/129a8b42-1a9b-4d3d-9706-ce826346a413)

Paso 2: instalar la distribucion deseada
```powershell
wsl --install -d Debian
```


![image](https://github.com/Modalbos/WSL/assets/148746995/9f3b675e-5053-4e9b-b83e-de6ccf72fd5c)

Paso 3: comprobamos que va


![image](https://github.com/Modalbos/WSL/assets/148746995/a604f701-88bf-43f0-b880-8b9106acb7d0)


## Importante
En ambos casos una vez instalado nos pedira el nombre de usuario y contraseña asi que ponemos la que queramos
