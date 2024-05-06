# Documento con la sintaxis de GitHub
## Este documento será para mostrar la sintaxis que ofrece GitHub en su editor de texto
### Estos son los ecabezados de nivel 1, 2 y 3 respectivamente4

#### Primero veremos los estilos de texto

Hay varios estilos de texto como el **negrita**, _itálico_, ~~tachado~~. Se pueden combinar como el **negrita y _cursiva_ anidada** o que sea todo ***negro y cursiva***. También se pueden poner <sub>subíndices</sub> y <sup>superíndices</sup>

#### Citado de texto

Puedes citar textpo facilmente con ">"
> Este es un texto citado

También puedes citar código con las comillas invertidas, puedes usarlas facilmente con `ctrl + e` o en macOS `command + e`
Puedes citar código en bloque por ejemplo:
```
git init
git status
git commit
```

#### Modelos de color

Puedes resaltar colores dentro de una oración usando comillas invertidas. Soporta HEX, RGB y HSL.
Este es color `#000000` negro.

#### Links

Puedes crear un link con el nombre en los corchetes [] y el link en paréntesis (). [GitHub](https://github.com/).
También puedes definir enlaces relativos, por ejemplo [Este README](README.md)

#### Imágenes

Puedes agregar imágenes con ! y añadiendo un texto breve entre corchetes [] añadiendo el link de la imagen entre paréntesis ().
![Logo de GitHub](https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png)

#### Listas

Puedes hacer listas con -, *, +. Por ejemplo:
- Java
* Python
+ C++

Puedes ordenar la lista puedes empezar cada linea con un número.

1. Java
2. Python
3. C++

Existen también las listas anidadas.

1. Primer objeto de la lista
  - Primero objeto anidado
    - Segundo objeto anidado

#### Listas de Tareas

Con un guión, un espacio seguido y unos corchetes [ ] creas una lista de tareas.

- [x] Tarea 1
- [ ] Tarea 2
- [ ] Tarea 3

#### Mencionar personas y equipos

Para mencionar a una persona o equipo debes usar el @ mas el nombre del usuario o equipo y esto le enviará una notificación al usuario que menciones
@github/support esto es una mención.

#### Emojis

Cuando pones : sale una lista de emojis que puedes usar. El emoji se ecribirá entre dos puntos :atom:

#### Notas a pie de página

Para escibir una nota a pie de página debes poner ^1 entre corchetes.
Esta es una nota [^1].

Una nota también puede tener varias lineas [^2].

[^1]: Nota1

[^2]: Nota2

#### Alertas

> [!NOTE]
> Esto es una nota

> [!TIP]
> Esto es una ayuda que debes saber

> [!IMPORTANT]
> Esto es informacion importante

> [!WARNING]
> Esto es un aviso

> [!CAUTION]
> Esto es una advertencia

<!-- Puedes hacer comentarios con la misma sintaxis que en html -->

#### Tablas

Con barras verticales | y guiones - puedes crear tablas.

| Primera columna | Segunda columna |
| ------------- | ------------- |
| celda 1  | celda 2  |
| celda 3  | celda 4  |

#### Secciones colapsadas

<details>

<summary>Esto es una seccion colapsada</summary>

Para hacer una sección colapsada debes escribir <details> <sumary> y posteriormente cerrar estos.

</details>
