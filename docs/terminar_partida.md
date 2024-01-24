# Terminar una partida

Para que el OCAP se guarde hace falta que salga "Misión Completada" o "Misión Fallida". Ejecutad el script en **GLOBAL EXEC**.

## Mision completada


```["END1",true,true] call BIS_fnc_endMission;```

## Misión fallida

```["LOSER",false, true] call BIS_fnc_endMission;```