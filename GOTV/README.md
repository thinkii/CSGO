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

Agregad todo esto a una config nueva llamada `GOTV.cfg` para que la podáis ejecutar cada vez que vayáis a castear/ver una demo.

```
// GOTV config by thinkii 27/04/2020

// Unos cuantos comandos requieren de sv_cheats 1
sv_cheats "1"

// Misc
engine_no_focus_sleep 		"0" 	// Evita que el juego baje a 30fps cuando los que hacen stream en pantalla completa sin bordes tabulan

// Sonido
snd_mixahead 			"0.015"
snd_musicvolume         	"0"  	// Volumen maestro de la música
snd_deathcamera_volume  	"0"     // Música de muerte
snd_mapobjective_volume 	"0"     // Música que suena cuando plantan
snd_menumusic_volume    	"0"     // Música del menú principal
snd_music_selection 		"0"
snd_mute_losefocus      "0"         // Reproduce el sonido en segundo plano cuando el CS:GO está minimizado
snd_roundend_volume     	"0"     // Música cuando la ronda acaba
snd_roundstart_volume   	"0"     // Música cuando la ronda comienza
snd_tensecondwarning_volume 	"0"	// Música de los últimos 10 segundos de bomba

// Comunicaciones
lobby_voice_chat_enabled 	"0"	// Desactiva el chat de voz del lobby
voice_enable        		"1"	// Chat de voz activado
voice_scale 			"0"	// Dejamos el voice_enable a 1 porque si no aparece abajo a la izquierda las letras en rojo
cl_chatfilters 			"0"	// Desactiva el cuadrado del chat
tv_nochat 			"1"	// Desactiva el chat de GOTV

// Comandos de cámara
cl_disablefreezecam 			"1" 
cl_freezecampanel_position_dynamic 	"0" 
cl_obs_interp_enable			"0"	// Desactiva el suavizado al cambiar de cámara
sv_spec_post_death_additional_time 	"2"	// Añade 2 segundos de espera antes de cambiar de cámara cuando alguien muere. Default: 5
sv_spec_use_tournament_content_standards "1"	// Cuando esté disponible, utilizará los nicks forzados que el torneo ha configurado e ignorará los name tags de las armas.

// Radar
cl_radar_icon_scale_min 		"1"	// Hace los iconos del radar más grandes para que la gente pueda ver el número de dentro.
cl_hud_radar_scale 			"1.3"	// Hace el radar más grande en general. 

// HUD 
hud_scaling 			"0.85"
cl_spec_show_bindings 		"0" 	// Oculta los binds de debajo de las stats de los jugadores
cl_spec_stats 			"0" 	// Elimina las stats de KDA de debajo de los jugadores, ya que a veces son incorrectas
cl_hud_color 			"1"	// Pone todos los elementos en color blanco, al ser el más neutro también es el mejor imo.

// Viewmodel mejorado para GOTV
viewmodel_presetpos "0"
viewmodel_offset_y "2"
viewmodel_offset_z "-2"
viewmodel_recoil "0"

// Movimiento del arma reducido al mínimo
cl_bob_lower_amt "5"
cl_bobamt_lat "0.1"
cl_bobamt_vert "0.1"
cl_bobcycle "0.980000"

// Desactiva postprocesado
mat_postprocess_enable "0"
mat_disable_bloom "1"

// Desactiva la niebla
fog_override "1"
fog_enable "0"

// Cambia el cielo por otro mucho mejor
sv_skyname vertigoblue_hdr

// Rayos X en defusekits
spec_xray_dropped_unoccluded "1"
spec_xray_dropped_defusekits "1"

// Mirilla
cl_crosshair_drawoutline "1"
cl_crosshair_dynamic_maxdist_splitratio "0.35"
cl_crosshair_dynamic_splitalpha_innermod "1"
cl_crosshair_dynamic_splitalpha_outermod "0.5"
cl_crosshair_dynamic_splitdist "7"
cl_crosshair_outlinethickness "1"
cl_crosshair_sniper_show_normal_inaccuracy "0"
cl_crosshair_sniper_width "1"
cl_crosshairalpha "200.000000"
cl_crosshaircolor "5"
cl_crosshaircolor_b "0"
cl_crosshaircolor_g "255"
cl_crosshaircolor_r "0"
cl_crosshairdot "0"
cl_crosshairgap "0.500000"
cl_crosshairgap_useweaponvalue "0"
cl_crosshairscale "0"
cl_crosshairsize "4.000000"
cl_crosshairstyle "4"
cl_crosshairthickness "1.000000"
cl_crosshairusealpha "1"
cl_fixedcrosshairgap "-2"
cl_show_observer_crosshair "0" // Cambiar para volver a activar las mirillas de la gente
```
   
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
