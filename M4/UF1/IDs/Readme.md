![image](https://github.com/user-attachments/assets/4781349a-78e0-44bb-b7aa-ef31ffceef06)![image](https://github.com/user-attachments/assets/b2785482-1601-404a-a409-02270011e989)
#  VISOR D'ELEMENTS WINDOWS SERVER 

## Crear una vista personalitzada.
Primer obrirem el desplegable de Herraminetas de l'administrador de Windows server i clicarem a on fica "Visor de eventos".
[ ](1.png)
A la dreta hi ha l'apartat "Acciones" i clicarem a "Crear vista personalizada".
[ ](2.png)
A la part de "Por registo" seleccionarem Aplicación així només sortirán els events de applicacions. Al apartat ID dicarem el ID de l'event que volem directament i li donem a "Aceptar".
[ ](3.png)
Ara en sortirá una finestra que li posarem el nom de la vista i una petita descripció.
[ ](4.png)

## Crea una tasca.
Després de guardar a la dreta li donarem a "Adjuntar tarea a esta vista".
[ ](5.png)
Ens sortirá una finestra i li donarem a Siguiente.
[ ](6.png)
Siguiente.
[ ](7.png)
I li donarem a "Iniciar un programa". Li donarem a Siguiente.
[ ](8.png)
Ara escollirem el programa que volem iniciar, en aquest cas el CMD. I li donarem a Siguiente i Finalizar.
[ ](9.png)

## Exportar vista a XML.
Ara per guardar una vista a XML haurem d'importarla. Per això a la part dreta hi ha un apartat que fica "Exportar vista personalizada".
[ ](10.png)
Seleccionarem on volem guardar l'element XML i li donem a "Guardar". L'aurem de passar d'una màquina a una altra. La pots pujar a Drive i així la pots descarregar. 
[ ](11.png)

## Importar XML desde una altra MV.
Una vegada tenim l'arxiu XML descarregat obrirem 
[ ](12.png)

[ ](13.png)

[ ](14.png)
