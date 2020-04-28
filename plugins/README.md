## Imprescindibles

- [Practicemode](https://github.com/splewis/csgo-practice-mode)

- [!pause, .coach, no hay bots y daño en chat a final de ronda](https://ci.splewis.net/job/sm-misc/lastSuccessfulBuild/artifact/builds/release/sm-misc-19.zip)
`csgo_coachcommand.smx, csgo_damageprint.smx, csgo_pause.smx y nobots_enforcer.smx`

- `servercleanup.smx` Este plugin lo que hace es "limpiar" el servidor cada cambio de mapa, elimina logs, demos y demás mierda del servidor para que vaya finito.

Todos están en esta ruta: `addons\sourcemod\plugins`

## Inútiles:

- Todos los demás

## Opcionales

- `rr.smx`

## Limpieza de plugins

Si queréis eliminar plugins que vienen por defecto totalmente inútiles que no van a afectar en NADA a lo que vais a utilizar seguid esta lista. Esto mejora ligeramente el rendimiento

Estos son los únicos que tenéis que mantener (de los que trae por defecto sourcemod, luego añadís los que queráis, como por ejemplo `csgo_damageprint.smx`

```
admin-flatfile
adminhelp
adminmenu
basebans
basecommands
clientprefs
```

Si elimináis alguno de esos es posible que no os funcionen ciertos plugins, como por ejemplo el practicemode.
