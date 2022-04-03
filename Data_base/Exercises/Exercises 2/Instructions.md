Instrucciones

Se considera una base de datos para administrar la información de los juegos olímpicos. Se hacen varias hipótesis para simplificar el problema y considerar únicamente un subconjunto reducido de información:

Sólo se consideran los deportes individuales.
Sólo se consideran las delegaciones de países diferentes y los atletas.
La información administrada para la creación de las tablas en el modelo de datos conceptual es la siguiente:

PAIS: nombre, número de participantes, número de medallas.
DEPORTISTA: matrícula, nombre, apellidos, sexo, país.
DISCIPLINA: identificador, nombre (p. ej. 400M nado libre), disciplina (p. ej. natación).
PRUEBA: identificador, disciplina, fecha, lugar, número de deportistas inscritos, naturaleza (eliminatoria, final). Para cada disciplina hay varias pruebas eliminatorias para una sola final.
CLASIFICACION: deportista, prueba, rango (p. ej. 1, 2, ...).
RESULTADO: disciplina, matrícula del deportista con medalla de oro, matrícula del deportista con medalla de plata, matrícula del deportista con medalla de bronce.
Tomando en cuenta lo anterior, proponga un esquema conceptual (diagrama entidad-relación) que represente la información donde se identifiquen las entidades y relaciones:

Para cada entidad, especifique los atributos asociados con sus dominios.
Para cada relación, defina su nombre, cardinalidad en ambas direcciones y posibles restricciones de integridad.
Para este problema deberá llevar su modelo conceptual a la ter