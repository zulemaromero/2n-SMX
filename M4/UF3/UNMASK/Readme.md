## Activitat 2 – umask
  1. Crea un usuari anomenat "proves2" i mostra la seva màscara per defecte.
![image](https://github.com/user-attachments/assets/a17800f9-f2c1-4686-be69-551949ef0e51)

  2. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-r--r-- i els
directoris amb rwxr-xr-x.
![image](https://github.com/user-attachments/assets/a8990a8e-1aaf-405d-b517-b4cd1f88c61b)
![image](https://github.com/user-attachments/assets/d373c115-13ae-4d16-a439-007bb37da0cc)

  3. Comprova que la màscara anterior funciona.
  4. ![image](https://github.com/user-attachments/assets/a8990a8e-1aaf-405d-b517-b4cd1f88c61b)
![image](https://github.com/user-attachments/assets/4dc74ed6-6957-48a2-9355-f8cba17c55fd)

  5. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-rw-rw- i
els directoris amb rwxrwxrwx.
![image](https://github.com/user-attachments/assets/296f1cfc-2d61-4521-9ffc-9090957dd52a)

  6. Comprova que la màscara anterior funciona.
![image](https://github.com/user-attachments/assets/6894c457-cf0b-4348-b014-1a2404abaca5)

  7. Modifica la màscara de proves2 perquè els fitxers els crei amb r--r--r-- i els
directoris amb r-xr-xr-x.

  8. Comprova que la màscara anterior funciona.

  9. Modifica la màscara de proves2 perquè els fitxers els crei amb rw--w--w- i
els directoris amb rwx--x--x.

  10. Comprova que la màscara anterior funciona.

  10.Modifica la màscara per crear un fitxer anomenat "511.txt" amb permisos r--------

  11.Utilitza chmod perquè els permisos de "511.txt" siguin r-x--x--x.

  12.Utilitza chmod perquè el fitxer anterior tingui permisos rwxrwxr-x.

  13.Utilitza chown perquè el fitxer anterior sigui propietat de l'usuari root i del
grup proves.

  14. Intenta eliminar el fitxer amb l'usuari proves2. (sense sudo)

  15. Afegeix l'usuari proves2 al grup proves i elimina el fitxer anterior.
