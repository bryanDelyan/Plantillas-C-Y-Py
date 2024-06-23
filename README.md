## Plantillas-C-Y-Py

Estas plantillas están diseñadas para usar con acceleo en el eclipse modeling tools

## Introducción 
El proyecto se centra en desarrollar una herramienta de generación de código automático que transforma modelos UML ("En este caso diagramas de clases") en código funcional en los lenguajes C# y Python. Utilizando la herramienta de acceleo en eclipse.

![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/fa20cd1f-c49a-4fa8-8fed-def35c565787)

## Instalación 
Para poder usar estas plantillas primero debemos instalar el eclipse modeling tools
link de descarga : https://www.eclipse.org/downloads/packages/release/2024-06/r/eclipse-modeling-tools

Una vez descargado, procedemos a la instalación de acceleo, para ellos nos vamos a help --> Eclipse Marktplace

![aaa](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/ce053965-a6dc-41f9-af8c-2d73e807d40e)

Y procedemos a instalarlo.
Después Procedemos a crear un proyecto en eclipse Usando acceleo :
![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/30466b7e-6e3c-4515-a1ce-5509c89f28d6)
![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/e0484572-feb0-414a-9701-5c3fcaeea395)

Luego le damos en el simbolo de agregar, y buscamos uml2/5.0.0/uml

![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/a8b5b6f0-0caf-44f6-96c9-096b50f4f206)

Y luego le damos a las casillas de Generate File, Main plate
Y finish

![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/826a8b50-a1f9-4a61-81a8-8afd36714a6e)


Nos dirigimos a el main y luego a generate.mtl y borramos el código que tenga adentro
Ahí es donde copiamos la plantilla de C# o Py y la pegamos en el genrate.mtl:

![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/a4bdbb99-e4e5-4c7f-be31-655cdec8b95f)

Para probarlo con un uml se puede hace de varias formas pero la mas sencilla es : 

1 Crear el modelo utilizando Herramientas como Papyrus: "Aquí un video de Youtube del canal de 'Alejandra Navarro Díaz 
' donde explica como hacerlo ": https://www.youtube.com/watch?v=nSIV5qYvats&ab_channel=AlejandraNavarroD%C3%ADaz
1.1 Tutorial básico de Papyrus "Video del canal de 'Mony ruiz'"  https://www.youtube.com/watch?v=XyhQcdxZWMc&ab_channel=MonyRuiz

Lo importante es tener el .uml para poder utilizarlo con la plantilla 

Luego de haber creado el diagrama de clases , ejemplo : 

![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/ebbb5dcc-c6a7-4ef6-aa52-3be8dd81a988)



Lo que nos importa es el .uml para utilizarlo 

![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/cf44a416-2655-49da-8e86-0555ca7a7a68)


Luego le damos click derecho sobre el generate.mtl 

![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/220adceb-a0b4-4a6b-9d79-e252c4bb8384)

![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/b6b45aa5-33a6-44a0-b794-64e582a89804)


Entonces dejamos Project y main class por default
Luego en Model elejimos el Uml que queremos y en Target creamos una carpeta para poder visualizar los resultados
le damos aplicar y run y se genererá los diagramas de clases 


![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/a84a2a0e-cd9c-4682-8a37-3367dc496e44)

Como observamos se generaron las clases que teníamos en el diagrama de clases 
![image](https://github.com/bryanDelyan/Plantillas-C-Y-Py/assets/84107668/c84f4764-4349-447c-933d-1ebca71c5409)

Y así de simple 





