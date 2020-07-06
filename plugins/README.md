## Imprescindibles

- [Practicemode](https://github.com/splewis/csgo-practice-mode)

- [!pause, .coach, no hay bots, daño en chat a final de ronda y .stop en chat para hacer backup de ronda](https://drive.google.com/file/d/1s1UY3hfG9AOG0i8Gw36Q_-VvTWjA7fSB/view?usp=sharing)
`csgo_coachcommand.smx, csgo_damageprint.smx, csgo_pause.smx, nobots_enforcer.smx y [PugSetup] RestoreRound.smx`

`El plugin de .stop es nuevo, cuando haya acabado el freezetime y la ronda esté live funciona cuando ambos equipos escriben .stop, automáticamente carga el backup y pausa la partida, esperando la confirmación de los equipos para quitar el pause con !unpause`

Todos están en esta ruta: `addons\sourcemod\plugins`

## Inútiles:

- Todos los demás

## Opcionales

- `rr.smx`, este plugin lo que hace es un restart de 3 segundos de duración si ponemos en el chat !rr

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
