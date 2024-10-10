#  VISOR D'ELEMENTS WINDOWS SERVER 

## Crear una vista personalitzada.
Primer obrirem el desplegable de Herraminetas de l'administrador de Windows server i clicarem a on fica "Visor de eventos".
![ ](1.png)
A la dreta hi ha l'apartat "Acciones" i clicarem a "Crear vista personalizada".
![ ](2.png)
A la part de "Por registo" seleccionarem "Aplicación" així només sortirán els events de applicacions. Al apartat ID dicarem el ID de l'event que volem directament i li donem a "Aceptar".
![ ](3.png)
Ara en sortirá una finestra que li posarem el nom de la vista i una petita descripció.
![ ](5.png)

## Crea una tasca.
Després de guardar a la dreta li donarem a "Adjuntar tarea a esta vista".
![ ](6.png)
Ens sortirá una finestra i li donarem a Siguiente.
![ ](7.png)
Siguiente.
![ ](8.png)
I li donarem a "Iniciar un programa". Li donarem a Siguiente.
![ ](10.png)
Ara escollirem el programa que volem iniciar, en aquest cas el CMD. I li donarem a Siguiente i Finalizar.
![ ](11.png)

## Exportar vista a XML.
Ara per guardar una vista a XML haurem d'importarla. Per això a la part dreta hi ha un apartat que fica "Exportar vista personalizada".
![ ](6.png)
Seleccionarem on volem guardar l'element XML i li donem a "Guardar". L'aurem de passar d'una màquina a una altra. La pots pujar a Drive i així la pots descarregar. 

## Importar XML desde una altra MV.
Una vegada tenim l'arxiu XML descarregat obrirem el "Visor de eventos" i li donarem a "Importar vista personalizada"
![ ](12.png)
Busquem l'arxiu XML que hem descarregat i li donem a "Abrir"
![ ](13.png)
Ens sortirà una finestra amb l'informació de l'event i li donem a "Aceptar"
![ ](14.png)
Ara ja tenim el visor d'events importat amb tota l'informació d'aquest. 
![ ](14.png)
