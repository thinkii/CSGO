- `server.cfg` es la configuración principal del servidor. Tendrás que editar el nombre del servidor, la contraseña y la rcon. Están puestas en las primeras líneas para que sea más intuitivo, el resto ya es a gusto del consumidor.

- `esl5on5.cfg`: Config para empezar el partido, se jugarán las 30 rondas completas, es decir, un partido puede acabar 21-9, 30-0 o 15-15. También elimina todos los comandos de `sv_cheats` o de `practicemode`, como por ejemplo el `sv_showimpacts` o la munición infinita.

Para los que no estéis familiarizados con esto, lo que viene a decir es que jugaréis las 15 rondas de T y las otras 15 de CT sin importar de qué lado empecéis.

- `gamemode_competitive.cfg`: Config cuya única finalidad es que al cambiar el mapa la configuración de `warmup.cfg` esté cargada por defecto sin tener que hacer nada nosotros (es necesario que en la última línea de server.cfg esté `exec gamemode_competitive.cfg` puesto)

> Me ha costado encontrar esta mierda bastante tiempo y estoy orgulloso de ello, la verdad xD

- `simulacion.cfg`: Config para hacer simulaciones de executes saliendo de base con un poco de `mp_freezetime` (7 en concreto, ¿casualidad?)

