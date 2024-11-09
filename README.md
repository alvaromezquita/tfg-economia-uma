# PLANTILLA_TFG_UMA

## Plantilla de TFG en LaTeX

**Autor:** Álvaro Mezquita Martínez  
**Contacto:**  
- **E-mail:** alvaromezquitam@gmail.com  
- **LinkedIn:** [Álvaro Mezquita Martínez](https://www.linkedin.com/in/%C3%A1lvaro-mezquita-mart%C3%ADnez-35956919a?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BdBE%2FVfG9S72HFS7%2BJsttxA%3D%3D)  
- **GitHub:** [alvaromezquita](https://github.com/alvaromezquita)

---

## LEEME.txt

### Índice

1. [Introducción](#introducción)  
2. [Instalación](#instalación-local)  
3. [Instrucciones de uso](#instrucciones-de-uso)  
4. [Licencia](#licencia)  
5. [Contribuciones](#contribuciones)  
6. [Agradecimientos](#agradecimientos)
---

### Introducción

La mayoría de los trabajos de fin de grado (TFG) de economía no requieren una alta carga matemática o informática, por lo que muchos estudiantes usan procesadores de texto “What You See Is What You Get” como Microsoft Word o LibreOffice Writer. 

Sin embargo, en casos donde el TFG incluye matemáticas complejas o programación, LaTeX se convierte en una mejor opción. Este entorno permite centrarse en el contenido sin preocuparse por problemas de formato y automatiza tareas como la gestión de referencias y el diseño.

La Facultad de Ciencias Económicas y Empresariales de la Universidad de Málaga exige un formato específico para estos trabajos. Esta plantilla LaTeX está diseñada para cumplir con esas normas y facilitar al estudiante el enfoque en su investigación.

Si eres nuevo en LaTeX, se recomienda buscar tutoriales para familiarizarte con el entorno. Incluso si tienes experiencia, sigue las instrucciones que se describen a continuación.

---

### Instalación Local

> **Nota:** Puedes ignorar esta sección si vas a usar Overleaf.

Para trabajar localmente con LaTeX, sigue estos pasos:

1. **Instala una distribución de LaTeX** (ej. TeX Live o MiKTeX). Asegúrate de que incluya los paquetes necesarios o que los instale automáticamente.
2. **Instala un editor de TeX** como TeXworks o TeXmaker.
3. **Instala un lector de PDFs**. Se recomienda SumatraPDF por ser ligero, pero también puedes usar Adobe Acrobat.

Después de configurar tu entorno local, descarga la carpeta "Proyecto Platilla UMA" del repositorio de [GitHub](https://github.com/alvaromezquita/tfg-economia-uma) (para ello le das al boton verde code y descargas el .zip y lo descomprimes). Corretamente instalado el entorno LaTeX, `main.tex` debería compilar correctamente el PDF.

---

### Instrucciones de Uso

Dentro del archivo `main.tex` encontrarás comentarios que te guiarán en el proceso. Aquí se resumen algunas recomendaciones:

- **No elimines paquetes ni ajustes predefinidos.** Puedes añadir nuevos si es necesario.  
- **No elimines archivos `.TTF`.**  
- **Escribe solo donde se indique.**  
- **Evita eliminar comandos que no entiendas.**

Si tienes experiencia, puedes modificar la plantilla a tu gusto, pero siguiendo estas pautas evitarás problemas de compilación.

#### Puntos clave:
- **Espaciado:** Usa `\vspace{12pt}` para generar un espacio de 12 puntos entre párrafos, como lo exige el formato.  
- **Comandos `\makebox[]{\dotfill}`:** Puedes eliminarlos y reemplazarlos con el texto requerido.  
- **Imágenes:** Sube la imagen al proyecto (en Overleaf o en tu carpeta local) y utiliza el código proporcionado para insertar figuras o gráficos.  
- **Referencias:** Usa el archivo `bib_tfg.bib` para incluir tus referencias en formato BibTeX. Solo aparecerán al final las citas utilizadas en el documento.

---

### Licencia

Esta plantilla está bajo la **LaTeX Project Public License (LPPL) versión 1.3c o posterior**.

#### Permisos:
- Uso y modificación para fines personales o profesionales.
- Distribución de copias, originales o modificadas, cumpliendo con la licencia.

#### Condiciones clave:
- Las versiones modificadas deben ser renombradas para evitar confusiones.
- Se debe incluir un aviso indicando que es una derivación de la plantilla original.

El texto completo de la licencia está en el archivo `LICENSE.txt` o en [LaTeX Project Public License](https://www.latex-project.org/lppl/).

---

### Contribuciones

Si deseas contribuir, abre un "issue" o crea un "pull request" en el repositorio de GitHub:  
[https://github.com/alvaromezquita/tfg-economia-uma](https://github.com/alvaromezquita/tfg-economia-uma)

--- 

### Agradecimientos 

Especial agradecimiento al profesor Gonzalo Fernández de Córdoba Martos. Fue mi tutor de TFG y quien me motivo a realizar este proyecto.
