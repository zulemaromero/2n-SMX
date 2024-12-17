## Activitat 1: Crea i explica les comandes per fer còpia de seguretat i restaurar el directori /var/www amb la comanda tar.
-c crea un nou arxiu tar.
-z comprimeix l'arxiu amb gzip.
-v mostra el progrés de la creació de l'arxiu.
-f especifica el nom de l'arxiu.
[](1.png)

-x extrau l'arxiu tar.
-z descomprimeix l'arxiu amb gzip.
-v mostra el progrés de l'extracció de l'arxiu.
-f especifica el nom de l'arxiu.
-C / especifica el directori on es vol extraure l'arxiu.
[](2.png)

## Activitat 2: Crea i explica les comandes per fer còpies de seguretat i restaurar el directori /var/www amb la comanda rsync.
-a preserva els permisos i els propietaris dels fitxers.
-v mostra el progrés de la creació de la còpia de seguretat.
-z comprimeix la transferència de dades.
[](3.png)

## Activitat 3: Utilitzant els comandaments de Dump i restore:
-0: Nivell de còpia de seguretat (0 per una còpia completa).
-u: Actualitza el registre de còpies de seguretat.
-f: Indica el fitxer de destí on es guardarà la còpia de seguretat (/tmp/Xbackup.dump).
~/Xbackup: Directori que es vol fer còpia de seguretat.
[](5.png)
[](4.png)


## Activitat 4: repeteix l’activitat anterior amb tar.
[](6.png)

## Activitat 5: Repeteix l’activitat anterior amb rsync.
## Activitat 6: Utilitza deja-dup per fer una còpia de seguretat del teu directori /home/usuari
## Activitat 7: Busca un altre programa de backups en entorn gràfic i fes una copia de seguretat de /home/usuari. Documenta el procés.
