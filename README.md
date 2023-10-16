# data-scrapping
Paso 1: Descargar e instalar Visual Studio Code

Visual Studio Code (VS Code) es un editor de código que te permitirá abrir y ejecutar el script. Sigue estos pasos:

Descarga Visual Studio Code desde el sitio oficial.
Ejecuta el archivo de instalación que descargaste y sigue las instrucciones en pantalla para completar la instalación.
Una vez instalado, abre Visual Studio Code.

Paso 2: Instalar Python

Para ejecutar el script, necesitarás tener Python instalado. Sigue estos pasos:

Descarga el instalador de Python desde la página oficial de Python. Elige la última versión estable para tu sistema operativo (Windows).
Ejecuta el archivo de instalación de Python y asegúrate de marcar la casilla "Add Python x.x to PATH" durante la instalación.

Paso 3: Instalar Git

Necesitarás Git para clonar el repositorio de GitHub. Sigue estos pasos:

Descarga Git desde el sitio oficial de Git.
Ejecuta el archivo de instalación de Git y sigue las instrucciones en pantalla.

Paso 4: Clonar el Repositorio de GitHub

El código se encuentra en un repositorio de GitHub. Sigue estos pasos para obtener una copia del código en tu computadora:

Abre Visual Studio Code.

Ve al menú "File" y selecciona "Open Folder" (Abrir Carpeta).

En la ventana de diálogo, crea una carpeta en tu computadora donde deseas guardar el código.

Abre una ventana de terminal en Visual Studio Code haciendo clic en "Terminal" en la parte superior y seleccionando "New Terminal".

En la terminal, ejecuta el siguiente comando para clonar el repositorio de GitHub:

shell
Copy code
git clone [https://github.com/tuusuario/turepositorio.git](https://github.com/Foxogeno/data-scrapping.git)
Asegúrate de reemplazar tuusuario/turepositorio con la URL real del repositorio que deseas clonar.

Paso 5: Instalar las Bibliotecas Python

Para ejecutar el script, necesitas instalar algunas bibliotecas Python. En la misma terminal de Visual Studio Code, ejecuta los siguientes comandos:

shell
Copy code
pip install openpyxl
pip install selenium
Estos comandos instalarán las bibliotecas openpyxl y selenium que son necesarias para el código.

Paso 6: Ejecutar el Código

Ahora que tienes todo configurado, puedes ejecutar el código:

Abre el archivo Python en Visual Studio Code haciendo clic en "File" > "Open File" y seleccionando el archivo Python que descargaste.
Haz clic en el icono de "Run Python File in Terminal" en la parte superior derecha del editor (parece un triángulo).
El código se ejecutará y verás los resultados en la terminal.
¡Eso es todo! Has descargado, configurado y ejecutado el código desde GitHub utilizando Visual Studio Code. Ten en cuenta que es importante reemplazar tuusuario/turepositorio con la URL real del repositorio de GitHub que deseas utilizar.
