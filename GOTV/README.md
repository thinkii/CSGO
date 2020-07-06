# Índice

- [Config de GOTV](#Config-GOTV)
- Configuraciones del score superior
   - [Nombres de equipos](#-Nombres-de-equipos)
   - [Banderas](#Banderas)
   - [Logos](#Logos)
   - [Estadísticas](#Estadísticas)
- [Config de stream](#Config-de-stream)
   
## Config GOTV

Esta config de GOTV está hecha por mí, los comandos los he ido buscando por ahí y su objetivo es mejorar la calidad del stream en Twitch lo máximo posible.

- Reducido el movimiento del Viewmodel el máximo posible que permite el juego (y que visualmente queda bien).

- Niebla eliminada junto a postprocesado y cambio de cielo por otro más estético.

- Rayos X activados en Kits de desactivación.

- Radar más grande para una mejor visualización en stream.

- Mirilla grande y bastante visible.

- Ajustes varios de sonido.

- Ajustes de HUD.

- Ajustes de cambio de cámara.

[LINK DE DESCARGA](https://drive.google.com/file/d/1rHhkyDnGG28mdzl127FWvbO_AclaRY-m/view?usp=sharing)
   
## Nombres de equipos

Para añadir los nombres a los equipos usaremos estos comandos:

```
mp_teamname_1 (CT)
mp_teamname_2 (T)
```

Ejemplo:
```
mp_teamname_1 HellRaisers
mp_teamname_2 TSM
```

![alt text](https://steamuserimages-a.akamaihd.net/ugc/222193264455381333/3EDD3437FF3EB6346082EA02CEDB26C0257E4775/ "CS")

## Banderas

Para añadir los nombres a los equipos usaremos estos comandos:
```
mp_teamflag_1 (CT)
mp_teamflag_2 (T)
```

Ejemplo:
```
mp_teamflag_1 eu
mp_teamflag_2 ca
```

![alt text](https://steamuserimages-a.akamaihd.net/ugc/222193264455572323/7F4123F86C755C41FB9775A7F89E1F4376FF3DA6/ "CS")

Las banderas usan código ISO, aquí tenéis todas https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2

## Logos

Para añadir los nombres a los equipos usaremos estos comandos:

```
mp_teamlogo_1 (CT)
mp_teamlogo_2 (T)
```

Ejemplo:

```
mp_teamlogo_1 hlr
mp_teamlogo_2 tsm
```

![alt text](https://steamuserimages-a.akamaihd.net/ugc/222193264455678340/EE31706B8162AD90553CC50E3DE93144F1CEC80C/ "CS")

Lista completa de logos [aquí](https://steamcommunity.com/sharedfiles/filedetails/?id=1109861355)

## Estadísticas

Para añadir estadísticas usaremos estos comandos:

```
mp_teammatch_stat_txt (Texto)
mp_teammatchstat_1 (CT)
mp_teammatchstat_2 (T)
```

Ejemplo:

```
mp_teammatch_stat_txt BO3
mp_teammatchstat_1 Champion
mp_Teammatchstat_2 Challenger
```

![alt text](https://steamuserimages-a.akamaihd.net/ugc/222193264457345839/105BFD1CD1C0A2806737297BA58E1F4AFB15E2A3/ "CS")

Guía que he usado como referencia [How to setup team logos, names etc.](https://steamcommunity.com/sharedfiles/filedetails/?id=788257116)

## Config de stream

Si vais a usar la cfg de GOTV os recomiendo añadirle un filtro de color a la fuente que tengáis de CS:GO.

Eso se hace dando botón derecho sobre la fuente de CS:GO y seleccionando `Filtros`, añadir filtro (botón derecho o el icono de + de abajo a la izquierda) y elegís la opción `Correción de color`.

Mi preferencia personal es poner la `Saturación` a `1,00`, se verá bastante más colorido pero sin llegar a ser agresivo para el viewer.
