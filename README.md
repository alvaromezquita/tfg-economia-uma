
# PLATILLA_TFG_UMA 
# Platilla de TFG en LaTeX 2024-2025

Autor: Álvaro Mezquita Martínez 

Contacto: 
- E-mail: alvaromezquitam@gmail.com
- Linkedin: https://www.linkedin.com/in/%C3%A1lvaro-mezquita-mart%C3%ADnez-35956919a/
- GitHub: https://github.com/alvaromezquita 

## Índice 

1. Introducción 
2. Instalación
3. Instrucciones de uso 
    3.1 Otras recomendaciones 
4. Licencia  
5. Contribuciones
6. Agradecimientos

## Introducción

La mayoría de trabajos de fin de grado de cualquier carrera de economía usualmente no tienen una alta carga matemática o informática. El poco uso de formulas o de scripts permite a la mayoría de alumnos utilizar procesadores de texto “What You See Is What You Get” como Microsoft Word o LibreOffice Writer, quienes están más familiarizados con este tipo de tecnología. 

Sin embargo, a veces estos trabajos van a contracorriente y sí exigen una alta presencia de matemáticas o de programación, y en estos casos Word no es la mejor opción para un TFG. 

El entorno LaTeX ofrece una solución eficiente a estos problemas, permitiendo al alumnado concentrarse en el contenido de su investigación más que en los problemas de formato que surgen de utilizar este tipo de procesadores. También en documentos más cargados de investigación se recomienda LaTeX porque suaviza la complejidad del documento, además de facilitar la automatización de procesos como el formato o las citaciones 

Como la Facultad de Ciencias Económicas y Empresariales de la Universidad de Málaga exige un formato muy específico para estos trabajos, esta platilla está propuesta para eliminar esas horas extra de trabajo en formatear un documento .tex y que el estudiante, de nuevo, se centre en lo importante: El contenido del trabajo. 

Si eres nuevo usando LaTeX, es altamente recomendable buscar tutoriales porque no es un entorno amigable con el usuario al principio, aunque existen muy buen material en la red que cualquier persona sin experiencia puede entender facilmente. De igual manera, aunque seas experimentado, te recomiendo que sigas las instrucciones que siguen a continuación.

## Instalación local

(Puedes ignorar esta parte si vas a utilizar Overleaf.) 

En caso de querer trabajar con el localmente (basicamente en un ordenador y no en la nube) sigue los pasos descritos a continuación: 

1. Primero necesitas instalar la distribución (TeX Live o MikTeX por ejemplo). Asegurate de que pueda tenga incluida los paquetes del archivo .tex o que los instale automaticamente. 

2. Luego deberás instalar un editor de TeX como TeXworks o Texmaker 

3. Por último, deberás tener instalado un lector de PDFs en el ordenador. Recomiendo SumatraPDF por ser ligero y no bloquear los PDFs, pero puedes usar Adobe Acrobat u otro similar si lo tienes instalado 

Después de configurar tu entorno local, descarga la carpeta "Proyecto Platilla UMA" del repositorio de GitHub (para ello le das al boton verde "code" y descargas el .zip y lo descomprimes). Corretamente instalado el entorno LaTeX, main.tex debería compilar correctamente el PDF.


## Instrucciones de uso 

En la carpeta (o el directorio de Overleaf) tendrás dos archivos .tex que tienes que prestar atención: "main.tex" y "config.tex". "main.tex" es el archivo principal donde escribirás todo tu trabajo, mientras que "config.tex" es donde aguarda toda configuracion del documento principal. 

Principalmente utilizarás "main.tex", y "config.tex" solo cuando necesites o incluir un paquete o cambiar alguna configuración por cambios en las normas de estilo. 

Si no es plenamente necesario y/o no se sabe que está haciendo, NO TOCAR "config.tex". Si sabes lo que haces, siempre puedes hacer y deshacer a tu gusto. 

Algunos puntos importantes extra a mencionar son: 

- Utilizar \vspace{12pt}. Esto permite generar un espacio entre parrafos de 12 puntos (como exigen las normas de estilo). Será como tu intro básico, asi que es recomendable copiarlo para pegarlo constantemente. 

- Existen varios comandos \makebox[]{\dotfill} en lugares que se tiene que rellenar con palabras o numero (no en el índice), por lo que puedes eliminarlo sin problema y escribir lo que se requiera

- Copia y pega el código de la imagen de ejemplo siempre que quieras poner otra imagen o figura (esto es tablas, graficas hechas con Tikz...). Escribir esto de otra manera o con otro paquete dará lugar, muy probablemente, a incumplir las normas de estilo. 

- Para utilizar imagenes tienes que subir la imagen deseada a la platilla de Overleaf (o a la misma carpeta del .tex si lo haces localmente)

- Para incluir referencias utiliza el archivo "bib_tfg.bib". En este archivo tendrás que incluir todas las referencias de tu TFG en formato BibTeX (tal y como se muestran en los ejemplos). No es necesario hacerlo a mano, la mayoría de portales académicos te permiten citar directamente en este formato, o puedes exportarlo automaticamente con un gestor de bibliografía como Zotero o Mendeley. 

- Solo saldrá al final del documento aquellas referencias que hayan sido citadas en el documento, cumpliendo así las normas de estilo. 

- A la hora de utilizar \section y \subsection, ten en cuenta que \section debe ir solo y \subsection debe ir junto con el comando \addcontentsline para incluirlo correctamente en el índice

### Paquetes recomendados

Para ciertos trabajos son altamente recomendables, si no es que necesarias, algunos paquetes que voy a listar: 

- Verbatim {Programación}: Este paquete nos sirve para dar formato a scripts de programación y que se distinga del resto del documento. La mayor pega es que no remarca los comandos del lenguaje que uses, o al menos no de forma predeterminada. 

- TikZ {Gráficas}: Este paquete sirve para hacer gráficas en el propio LaTeX. Es perfecto para cuando queremos representar una función teórica y su evolución en un plano cartesiano. También es necesario para hacer arboles de decisión como las de Teoría de Juegos. 

## Licencia 

Esta plantilla está distribuida bajo la **LaTeX Project Public License (LPPL) versión 1.3c o posterior**.

La LPPL permite:

- Usar y modificar esta plantilla libremente para uso personal o profesional.
- Distribuir copias de la plantilla original o modificada, siempre que se cumplan las condiciones de la licencia.

Condiciones clave:
- Si distribuyes una versión modificada, debes renombrar los archivos para evitar confusiones con el trabajo original.
- Debes incluir un aviso de que tu versión es una derivación de la plantilla original.

El texto completo de la licencia se puede encontrar en el archivo `LICENSE.txt` o en [LaTeX Project Public License](https://www.latex-project.org/lppl/).


## Contribuciones 

Si deseas contribuir a este proyecto, abre un "issue" (para alertar sobre algún error) o crea un "pull request" (para realizar cambios a la plantilla) en nuestro repositorio de GitHub: https://github.com/alvaromezquita/tfg-economia-uma  

## Agradecimientos 

Especial agradecimiento al profesor Gonzalo Fernández de Córdoba Martos, excelente profesor de la facultad. Fue mi tutor de TFG y quien me motivó a realizar este proyecto.
