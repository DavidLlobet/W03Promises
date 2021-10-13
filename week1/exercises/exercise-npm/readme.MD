## Ejercicio - npm

En este proyecto en blanco dispones de un archivo `package.json` con las dependencias iniciales de tu proyecto. Revisa el archivo para ver qué dependencias son.

Hay que entregar una captura de pantalla para cada punto, más los comandos que habéis utilizado.

1. Instala todas las dependencias.
2. Comprueba mediante algún comando de npm si te ha instalado localmente los paquetes que había en package.json.
3. Comprueba los tres paquetes lanzando sus ejecutables:

- Paquete superb-cli: genera palabras soberbias aleatorias. Ejecutable:
`superb`

- Paquete quote-cli: genera citas aleatorias. Ejecutable:
`quote`
- Paquete figlet-cli: genera un texto con ASCII a partir de una frase. Ejecutable:
`figlet -f Standard "(pon aquí la frase que tú quieras)"`
`figlet -f Ghost "(pon aquí la frase que tú quieras)"`

4. Ahora instala los siguientes paquetes:

- Paquete `ascii-cats`: genera gatetes en la consola. Instálalo como dependencia de desarrollo.
Para comprobar que funciona, el ejecutable es `asciiCats`

- Paquete `bot`: chat con un bot. Instálalo como dependencia de producción.
Para comprobar que funciona, el ejecutable es `bot`    

- Paquete `yodasay`: personajes de Star Wars en ASCII. Instálalo como dependencia de desarrollo.
Para comprobar que funciona, el ejecutable es `yodasay -r "(pon aquí la frase que quieras)"`

5. Mira el archivo package.json y comprueba que todo se ha registrado como esperabas.
6. Crea un proyecto en blanco fuera de éste (es decir, crea una carpeta en otro lugar, que no sea una subcarpeta de ésta). Copia el package.json de este proyecto al nuevo.
7. En el nuevo proyecto en blanco, instala las dependencias de producción.
8. Comprueba mediante un comando de npm que se han instalado los cuatro paquetes.