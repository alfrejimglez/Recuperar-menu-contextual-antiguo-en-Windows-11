<h1>Recuperar menu contextual antiguo  de Windows 10 en Windows 11</h1>

![image](https://user-images.githubusercontent.com/17550010/157343765-ade4f95c-446c-4321-80ee-2d7460246f66.png)






<h2>Pasos</h2>

1. Presione el método abreviado de teclado de Windows 11 “Windows + R” para abrir una ventana Ejecutar. Aquí, escriba regedit y presione Enter.
![image](https://user-images.githubusercontent.com/17550010/157343517-0a71b572-5619-4857-9318-4a0a3519727b.png)


2. A continuación, continúe y pegue la siguiente dirección en el Editor del registro. Lo llevará a la entrada CLSID.

**HKCU\Software\Classes\CLSID**


![image](https://user-images.githubusercontent.com/17550010/157343608-f3e63a88-cbcf-406b-a2cc-2e2c13082025.png)

3. En la carpeta CLSID, haga clic con el botón derecho en el espacio vacío del panel derecho y seleccione Nuevo -> Clave.


![image](https://user-images.githubusercontent.com/17550010/157343630-7952cb2b-5c1d-4607-bc4d-3eb75b820ff1.png)


4. Después de eso, copie la siguiente cadena y cambiar el nombre de la nueva clave.

{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}


![image](https://user-images.githubusercontent.com/17550010/157343646-db836556-cf10-47f1-b064-d1322302733f.png)


5. A continuación, haga clic con el botón derecho en el nueva entrada en el panel izquierdo y elija Nuevo -> Clave.


![image](https://user-images.githubusercontent.com/17550010/157343679-48ee277b-967f-47c8-bf7c-d90dc639a1e6.png)



6. Cambie el nombre a **InprocServer32** y presione Enter.

![image](https://user-images.githubusercontent.com/17550010/157343725-4c6981ea-eaaf-42ed-84e9-44c83e54877c.png)


7. Ahora, vaya a la carpeta “InprocServer32” y haga doble clic en “Defecto”En el panel derecho. Después de eso, haga clic en “Aceptar” sin cambiar ningún valor.

![image](https://user-images.githubusercontent.com/17550010/157343736-590fd075-ec30-4efa-ad89-c90d4acba676.png)


8. Ahora, cierre el Editor del registro y reinicie el Explorador de Windows desde el Administrador de tareas. O simplemente puede reinicia tu PC. Finalmente, verá que el antiguo menú contextual está de vuelta en Windows 11. ¡Disfrute!




