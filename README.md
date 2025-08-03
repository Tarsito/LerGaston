# LerGaston

Aplicación cuyo objetivo será hacer gestión de economía doméstica. El nombre viene de la unión de "Lercas" mas "Gastón". Dicho proyecto se llevará a cabo a modo de Jam con objetivos que se marquen en distintos momentos del tiempo con tiempo limitado, motivo por el cual, este proyecto tendrá una evolución errática cara el futuro, con posibilidad de cambios que condicionen la versión final del mismo.

La Jam se sustentará en diferentes sesiones con sus reglas, tiempos y objetivos.

## Idea final

Aplicación Web para gestión de gastos dinámico, individualista, abierto, con opción de que el usuario gestione su información sin depender del servidor, aplicable su ejecución tanto en HTTP como en FILE. Los datos que se han de gestionar son:

* **Fecha de inicio**: Fecha en la que se produce la orden.
* **Fecha de realización**: Fecha en la que se lleva a cabo la orden.
* **Tipo de movimiento**: Ésta puede ser pago, cobro, cancelación.
* **Importe**
* **Moneda**
* **Concepto**
* **Grupos**: Grupos de movimientos, por ejemplo, alimentación, coche, casa, etc.
    * **Nombre**: Nombre del grupo.
    * **Porcentaje**: Porcentaje de consumo. Si no se define siempre serán porciones iguales.
* **Entidad**: Entidad con la que se efectúa el movimiento.
    * **Grupos por defecto**: Para entidades que tengan patrón siempre, se le establecen dichos grupos por defecto.

> Para futuro. Cuando un movimiento tenga más de un grupo, éste pueda desglosarse en cómputos totales para cada grupo.

Los datos han de partir de Drivers de lectura de datos vía CSV, 43, XML, JSON, etc. Dependiendo de la entidad y como lo retorne.

## Objetivos finales

El proyecto será una Aplicación Web OnePage OneFile, todo unificado y ha de intentar, en la medida de lo posible, no importar recursos externos, lo que no impide dicha acción pero penalizará. Una vez gestionados los datos, poder consultarlos, visualizarlos y descargar informes de éstos, ya sea en CSV, JSON, XML y/o PDF.

El archivo único ha de ser totalmente legible, flexible, mantenible y escalable.

Los puntos por Jam se valorarán de 0 a 10 y se hará media por los jueces, quienes pueden ser los propios participantes, una IA, personas externas o varios de éstos.

## Sesiones

### Sesión 1

Esta sesión constará de 2 horas, y sus objetivos son los siguientes:

* Estructurar el proyecto. 9 Tarsi  6 KyMaN
* Estructurar la base funcional. 9 Tarsi  8 KyMaN
* Estructurar los datos. 4 Tarsi  6,5 KyMaN

3/8/2025 17:40 - 19:40

### Sesión 2

Esta sesión constará de 2 horas, y sus objetivos son los siguientes:

* Parte estática para divirlo en bloques mas pequeños.
* Logo.
* GUI estrucuturar y elementos.
* Drivers.

* Carga información.
* Generación informes.
* Almacenado de datos.

4/8/2025 17:45 - 19:45