# Changelog – piedrapapelotijera

Todos los cambios importantes de este proyecto se documentan en este archivo.
El formato se basa en [Keep a Changelog](https://keepachangelog.com/es-ES/1.1.0/) y el proyecto usa [Versionado Semántico](https://semver.org/lang/es/).

## [1.0.0] - 2026-11-04

### Agregado
- Juego de Piedra, Papel o Tijera contra la IA con menú de tres opciones.
- Estructura `Partida` y persistencia en `data/historial_partidas.txt` con `ofstream` en modo `ios::app`.
- Lectura del historial con `ifstream` delimitada por comas.
- `contarPartidasEnDisco()`: el ID de partida continúa entre sesiones.
- `limpiarEntrada()`: recuperación de `cin` ante letras u otros datos no numéricos.
- Validación de la jugada (solo 1, 2 o 3).
- Documentación: informe APA v7, manual del programador, manual del usuario, README.
- Capturas de la demostración de persistencia y del archivo en disco.

### Cambiado
- Ruta del archivo persistente de `src/` a `data/` según la estructura del repositorio.

## [0.1.0] - 2026-10-08

### Agregado
- Estructura inicial del repositorio, `.gitattributes`, `.gitignore` y `LICENSE`.
