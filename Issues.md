Usar los Issues de GitHub permite gestionar y documentar problemas en un repositorio, desde errores simples en la redacción hasta defectos complejos en la funcionalidad. Con una interfaz intuitiva, permite que cualquier usuario señale y describa aspectos mejorables, y con plantillas de Issues, mejora la claridad y colaboración en el proceso.
¿Qué es un Issue en GitHub?

Un Issue es una forma de señalar problemas o sugerencias dentro de un repositorio. Puede ser usado para:

    Notificar errores en la documentación, como faltas de ortografía.
    Reportar problemas en el funcionamiento esperado del código.
    Informar mejoras o cambios necesarios.

Los Issues permiten una comunicación bidireccional entre los colaboradores y el creador del repositorio, lo que facilita la resolución de problemas.
¿Cómo crear un nuevo Issue?

    En el repositorio de GitHub, selecciona la pestaña Issues.
    Haz clic en New Issue y describe el problema en dos campos principales:
        Título: Una breve descripción.
        Descripción: Detalles del problema, pasos para reproducirlo, etc.

Es posible agregar elementos adicionales, como asignar el Issue a otra persona o etiquetarlo.
¿Cómo crear una plantilla de Issues?

Para facilitar el proceso a otros colaboradores, es útil crear plantillas de Issues. Para hacerlo:

    Desde el repositorio, abre Visual Studio Code con el comando code ..
    Crea una carpeta llamada .github y dentro otra carpeta llamada ISSUE_TEMPLATE.
    Dentro de ISSUE_TEMPLATE, crea un archivo Markdown (por ejemplo, bug_report.md).
    Copia la estructura de la plantilla, que usualmente incluye secciones como descripción, pasos para reproducir el error y detalles adicionales.

Con esta plantilla, los colaboradores tendrán un formato estándar para reportar problemas, lo que ayuda a una mejor gestión y resolución.
¿Cómo sincronizar los cambios en GitHub?

    Una vez creada la plantilla, verifica que los archivos cambiados estén marcados en verde en Visual Studio Code.
    Realiza un commit (por ejemplo, “Bug Report agregado”).
    Sincroniza con el repositorio de GitHub mediante el botón de flecha hacia arriba (push).
    En GitHub, verifica que la plantilla esté disponible en la sección de Issues.

¿Qué ventajas tiene una plantilla de Issues?

Las plantillas simplifican el proceso de documentación de problemas y mejoran la comunicación al estandarizar la información que se solicita a los colaboradores. Esto ayuda a identificar los problemas de forma precisa y rápida.
¿Cómo personalizar las plantillas de Issues para casos específicos?

Además de la plantilla básica para bugs, puedes crear plantillas personalizadas como:

    Document Report: Para señalar errores en la documentación.
    Mejores prácticas: Para sugerir mejoras en la estructura del código.

Estas plantillas permiten a los colaboradores elegir el tipo de Issue que mejor se adapta al problema y agilizan la gestión del repositorio.
