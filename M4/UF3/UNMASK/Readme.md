## Activitat 2 – umask
  1. Crea un usuari anomenat "proves2" i mostra la seva màscara per defecte.

  2. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-r--r-- i els
directoris amb rwxr-xr-x.

  3. Comprova que la màscara anterior funciona.

  4. Modifica la màscara de proves2 perquè els fitxers els crei amb rw-rw-rw- i
els directoris amb rwxrwxrwx.

  5. Comprova que la màscara anterior funciona.

  6. Modifica la màscara de proves2 perquè els fitxers els crei amb r--r--r-- i els
directoris amb r-xr-xr-x.

  7. Comprova que la màscara anterior funciona.

  8. Modifica la màscara de proves2 perquè els fitxers els crei amb rw--w--w- i
els directoris amb rwx--x--x.

  9. Comprova que la màscara anterior funciona.

  10.Modifica la màscara per crear un fitxer anomenat "511.txt" amb permisos r-
-------

  11.Utilitza chmod perquè els permisos de "511.txt" siguin r-x--x--x.

  12.Utilitza chmod perquè el fitxer anterior tingui permisos rwxrwxr-x.

  13.Utilitza chown perquè el fitxer anterior sigui propietat de l'usuari root i del
grup proves.

  14. Intenta eliminar el fitxer amb l'usuari proves2. (sense sudo)

  15. Afegeix l'usuari proves2 al grup proves i elimina el fitxer anterior.
