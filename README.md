# Instrucciones

Instalación de los programas necesarios para aprender y codificar html con herramientas gratuitas y de uso actual.

## Paso-1: Notepad++ (es opcional pero te lo recomiendo)
  https://notepad-plus-plus.org/downloads/
  
  Notepad++ es un editor de texto (este documento lo eh escrito en Notepad++)
	Es gratuito, sirve para varias cosas, es bastante optente; pero no es una GUI (interfaz grafica del usuario) para ejecutar programas
	sino que lo que hace es poder verlos, modificarlos...
	Para que te hagas una idea, notepad++ es como la herramienta de bloc de notas, pero infinidad de veces mejor
	
- Paso-1.1. Instalación de Notepad++ en tu ordenador
  (puedes seguir el video: https://www.youtube.com/watch?v=hNMbfWZ2pGc)
  te recomeindo instalar la versión 8.4.8.
  dejalo todo por defecto, pero te recomeindo instalar el acceso directo al escritorio
	
- Paso-1.1.1. Instalación de plugin Compare en Notepad++
  (puedes seguir el video: https://www.youtube.com/watch?v=XJrnqrczLZQ)
  Una vez habras notepad++ te recomeindo en el menu de arriba que pone (Archivo,Editar,Buscar...) seleccionar 
  Plugins>Administrar Plugins>Y buscas uno que se llama ```Compare``` (ComparePlus no, solo Compare) lo seleccionas y arriba a la derecha en instalar.
  El plugin "compare" te permite comparar 2 docuemntos que tengas abiertos en notepad++ de forma inmediata tal como haría git o github.
		
## Paso-2: Instalar Visual Studio Code como GUI para codificar en html (es obligatorio)
  https://code.visualstudio.com/
  
  Visual Studio Code 	es una nueva interfaz grafica y editor de codigo que es uno de los mas potentes actualemnte por su versatilidad
  y por eso está cogiendo tanta reputación. Sirve para muchos lenguajes de programación pero sobretodo para html va genial
	
- Paso-2.1: Instalar Visual Studio Code en tu ordenador
  (recomiendo seguir el video: https://www.youtube.com/watch?v=X_Z7d04x9-E)
  Descargate la version Stable y te recomiendo añadir un acceso directo al escritorio
	
  Sobre los plugins:
    - el del español te da igual, lo que quieras. Yo lo tengo en ingles.
    - el del material icon theme puedes hacerlo, aunque el ya por defecto ya te lo pone, lo que prefieras (yo no lo tengo pero está muy bien ese plugin)
	
- Paso-2.2: Instalar el plugin Live Server
  (recomiendo seguir el video: https://www.youtube.com/watch?v=x1Xl5J5QkCs minutos 0:36 y 1:27)
  
  Accede a la pestaña de extensiones, y busca el plugin ```Live Server``` y le das a instalar. 


## Paso-3: Git + Github (es opcional pero para trabajar conjunto a otras personas se vuelve obligatorio)
  https://git-scm.com/downloads
  
  Git 	es la herramienta que permite llevar un control de las versiones de codigo.
	
  https://github.com/
  
  Github 	es la pltaforma donde puedes subir tu codigo en la nube y así no perderlo nunca ademas 
			de poder compartirlo o rabajar conjuntamente con otros programadores
			
  - Paso-3.1: Instalar Git en tu ordenador. 
    (puedes seguir el video: https://www.youtube.com/watch?v=cYLapo1FFmA)
      (recomeindo instalar lo que venga marcado, el opcional que está como NEW que marca el en el video no hace falta)
      (en la parte del editor que viene por defecto el Vim, puedes usar Vim o sino el Notepadd++)
      
    URL de descargas de git: https://git-scm.com/downloads
    (Recomendado los Standalone Installer y la versión mantenida (2.39.0) 64-bit). Verificar que tu ordenador sea x64 o x32.
    Para verificar si es x32 o x64 puedes hacerlo llendo a Las carpetas,  este equipo, la unidad C -> la ruta de directorio ```C:\```
    Si allí te aparecen 2 carpetas de "Archivos de programa" y la otra de "Archivos de programa (x86)" entonces tu pc es de x64 (actualmente la mayoria lo son)

    Para verificar si se ha instalado correctamente, 
    si abres el cmd / terminal (la aplicación simbolo de sistema) y escribes ```git --version``` debería aparecer la versión instalada
		
		
  - Paso-3.2: Crearse una cuenta de Github en la web.
		(puedes seguir el video: https://www.youtube.com/watch?v=jwFSIEi_d7E)
	
  - Paso-3.2.1: Crear un nuevo repositorio demo y subirlo a Github para inicializar comunicacion github-git
		(puedes seguir el video: https://www.youtube.com/watch?v=qba3H93HAtk)
		en lugar de los fihceros .html y .css que tiene el, tu puedes usar o bien el que creaste en el Paso-2.1 siguiendo el video o sino pon un fichero .txt creado tuyo y ya.

## Paso-4: Creación de tu primer codigo html
	
  - Paso-4.1: Creación de tu primer html
		Para la realización de este paso es indispensable el Paso-2.
		(sigue el vudeo https://www.youtube.com/watch?v=b_cUDH5HuzY)
    
      - En el minuto 0:46 que el va a copiar la platilla del index.html tu vas a hacer lo siguiente:
      vas a abrir el index.html en el visual studio code, y vas a escribir ```!``` (si te fijas aparecera tanto ```!``` como ```!!!```)
      despues de escribir ```!``` le das a la tecla enter del teclado o a la tecla de tabulación (cualquiera de las dos) y ya lo tienes.
      (si no te funciona, borra el simbolo ```!```. Es importante que la tecla de enter o la de tabulación le debes dar despues de escribir el ```!```
      mientras está el submenu donde te aparecen las opciones de ```!``` y ```!!!``` porque lo que va a hacer es autocompeltar. En caso de que escribas un 
      ```!``` clicas en otra tecla (como un espacio) y despues le des al enter o al tab (tabulación) no va a funcionar y deberas borrar el simbolo ```!``` 
      y escribirlo de  nuevo.

        - (recuerda que en el index.html te crea la plantilla, pero te falta añadir lo de dentro del ```<body>``` y el ```link al css``` que justo lo explico a continuación)
		
      - Para añadir la parte del ```<body>```, pon el cursor dentro de ambas etiquetas (```<body>``` y ```</body>```) y escribe ```h1``` y le das a enter o al tab (igual que con el ```!```)
      Despues debes escribir el texto que quieras (```Mi pagina```) recuerda que va sin comillas (""), direactemente el texto y ya.
		
        - HTML funciona por etiquetas, primero se abre una etiqueta y despues se tiene que cerrar. 
        Eso lo que hace es delimitar la zona donde se define y existe dicha etiqueta. las etiquetas son lo que va entre ```<>``` (ejemplo ```<body>```)
        y siempre que abres una etiqueta ```<body>``` debes cerrarla ```</body>``` de esta forma, delimitas el espacio que va a ocupar.
        Algunas etiquetas necesitan abrirse y cerrarse (```<body>...</body>```, ```<html>...</html>``` por ejemplo) y otras no necesitan cerrarse
        pues solo se definen en la propia apertura y se cierran por dentro (```<meta ...params... >``` , ```<link ...params... >```)
		
      - En el minuto 2:24 que hace el link entre el .thml y el .css tu vas a hacer lo siguiente:
      en el index.html vas a escribir: ```link:css``` y le vas a dar a enter o al tab (igual que antes con el ```!```)
		
      - En el minuto 2:42 que va a abrir directaemnte el fichero, en lugar de eso vamos a poner en práctica el Paso-2.2.
      Para ello, abajo de todo a la derecha, en una barrita azul que hay, a la derecha del todo hay una opción que pone ```Go Live``` clicas allí y listo.
      Importante, para que actualice los cambios, debes guardarlos (si modificas un fichero te aparecerá una bolita blanca el lado de su nombre, eso
      siginifca que lo modificaste y hay cambios no guardados; para guardarlos clicas en las teclas ```"CTRL"+"S"``` y ya (la tecla control y la tecla S).
      Guardando los cambios, el server los actualiará automaticamente en el navegador.
      
        - Una vez llegues aquí, te recomiendo hacer el Paso-3.2.1 para subirlo al Github (te recomiendo crearte otro repositorio)
