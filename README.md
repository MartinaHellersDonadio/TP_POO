# Trabajo Práctico Final - Programación Orientada a Datos

**Alumno/a:** Martina Hellers Donadío

**Profesores:** Federico Moreno y Javier Duque

##  Netflix: una empresa data driven 🎬

Netflix, Inc. es una empresa de entretenimiento y una plataforma de streaming estadounidense que participa en la producción de obras audiovisuales, desde la creación o adquisición del producto hasta su difusión mundial. Actualmente, cuenta con más de 83 millones de miembros en más de 190 países que disfrutan de más de 125 millones de horas de programas de televisión y películas (incluidas series y documentales).

Desde cualquier lugar y en el momento en que los usuarios lo deseen, tienen la libertad de reproducir, pausar y reanudar la reproducción de su contenido favorito en el momento en el que lo consideren oportuno.

En el marco de la revolución digital, donde los datos son el nuevo petróleo, resulta sumamente importante y desafiante ir ajustando los modelos de negocio para poder captar con éxito cada espacio de necesidad de los clientes. 
En este sentido, Netflix es un claro ejemplo de una compañía que sin duda busca acercarle a sus usuarios una experiencia que realmente atraviese la pantalla.

### Acerca del proyecto 📊

En esta oportunidad, el análisis estará enfocado en una sola plataforma de streaming para poder realizar un análisis más de nicho y recopilar inisghts no tanto de tipo competitivo (como ser la proporción de volúmen de usuarios con respecto a otras plataformas) sino que permitan adentrarse a entender la dinámica que se está produciendo dentro de esta plataforma en particular (un análisis más bien de comportamiento) y, así, poder formular conclusiones enfocadas tanto desde el lado de los usuarios como de los productores que buscan incorporar contenidos dentro de ella.
Además, se buscará poder elaborar un **modelo que permita predecir el rating que obtendrá un contenido disponibilizado dentro de Netflix**.

Pero, por sobre todo, el objetivo no es sólo poder adentrarse a la dinámica tan interesante que se articula, día a día, en una plataforma tan interesante como Netflix dónde se toman decisiones en base a datos permanentemente, sino también, poder establecer las relaciones que se existen entre las variables y ver la influencia -que podría llegar a tener o no- cada una de ellas sobre el rating (puntuación de los usuarios) de los contenidos. Como se dijo antes, a fin de cuentas, hoy las empresas se esfuerzan permanentemente por acercarles a sus usuarios/clientes experiencias superadoras. Entonces, ¿por qué no ver si existen variables que influyan congruentemente sobre lo que tienen para decir los suscriptores de Netflix sobre los contenidos disponibles?

### Guía de instalación 💻

Para poder correr la totalidad del análisis comprendido dentro de este notebook, será necesario verificar que se cuentan con algunos requisitos importantes para evitar inconvenientes a posteriori y poder correr con tranquilidad el código:

1. Contar con una cuenta de git para poder clonar el repositorio y correrlo desde su IDE de preferencia, dónde se pueda armar un entorno de desarrollo (como Visual Studio Code, Pycharm). En lo que refiere a la estructura del proyecto: contamos con un notebook con todo el análisis (Proyecto - Hellers D.ipynb) y una carpeta (data) con todos los datasets utilizados

2. Asegurarse de contar con alguna versión de Python en sus ordenadores (y de no ser el caso, descargarlo)
    * Windows: https://www.python.org/downloads/windows/ 
    * Mac: https://www.python.org/downloads/mac/ 
    * Linux: https://www.python.org/downloads/linux/

3. Utilizar un entorno de anaconda o crear su propio entorno personalizado. 
Para crear un entorno de anaconda vamos a utilizar el comando: conda create -n <nombre_entorno> <paquete_python>

Esas son las consideraciones principales, las librerias a utilizar ya se encuentran instanciadas en la notebook que está preparado y detalladamente explicado para acompañar al usuario por todo el camino
