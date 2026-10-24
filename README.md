# Seguimiento Temas 1-3

## 🗒️ Requisitos

Para realizar los ejercicios deberás haber realizado los ejercicios de los temas anteriores.

### Librerias

Para instalar las librerías necesarias para este tema debes ejecutar el siguiente comando en el terminal:

```bash
pip install -r requirements.txt
```

> Nota: El archivo 'requirements.txt' no está dentro de ninguna carpeta.

## 📝 Enunciados

El objetivo general del ejercicio es crear una serie de funciones que nos permitan realizar operaciones sobre un texto.
Para este ejercicio, no se debe usar la función split de Python. En vez de ello, deberás  usar las siguientes funciones auxiliares que serán de gran ayuda al resolver el ejercicio. Asimismo, se pueden elegir crear nuevas funciones adicionales. A continuación, presentaremos una descripción de estos métodos:
* is_newline(character): Es una función que detecta el final de una oración. Deberás suponer que las frases están separadas por "\n" (nueva línea). Si el carácter es este símbolo, devolverá True.
* is_space(character): Es una función que detecta si un carácter es un espacio en blanco. Si el carácter es este símbolo, devolverá True.
* remove_punctuation_marks(cad): Una función que elimina los signos de puntuación de una palabra o un texto. Este método devuelve como resultado una cadena de caracteres sin signos de puntuación.

El documento completo del ejercicio se encuentra en la plataforma de CANVAS.

Además, cada ejercicio irá acompañado de uno o varios tests para comprobar que tu solución es correcta. 

Cuando hayas propuesto una implementación para la función, ejecuta los tests para ver si tu solución es correcta. Para ello asegurate de estar ubicado en la carpeta del ejercicio correspondiente python-b1-x1-sol antes de ejecutar el comando `pytest`. Si no pasa los tests, vuelve a intentarlo revisando los errores que te comentan los tests.

Una vez termines el ejercicio, deberás enviar tus cambios para que se registren en la plataforma y que puedan ser corregidos por tu profesor. 

## 💻 Comandos
En la siguiente sección se presentan algunos comandos útiles para el desarrollo de la actividad. 

### Git

Con el fin de actualizar los repositorios locales con la última versión de código fuente, ejecute:

```bash
git pull
```

Para agregar los cambios realizados en los archivos, ejecute:

```bash
git add .
```

Para añadir un mensaje a los cambios realizados localmente, ejecute:

```bash
git commit -m "Mensaje"
```

Para sincronizar nuestras modificaciones con el repositorio remoto, ejecute:
```bash
git push
```

### Python

Para ejecutar las pruebas unitarias:
```bash
pytest 
```
En caso de tener algún problema, puedes probar ejecutar la función con la instrucción `python -m` delante, por ejemplo:

```bash
python -m pytest 
```
```bash
python -m pip install -r requirements.txt
```
Más información sobre cómo ejecutar las pruebas unitarias, consulte el ejercicio del tema 0.
