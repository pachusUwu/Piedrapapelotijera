# Piedra, Papel o Tijera – Actividad 7: Persistencia de Datos con struct + fstream (LPR 2026)

Mini juego de consola en C++ contra la IA. Cada partida se guarda en una estructura `Partida` y se escribe en disco (`data/historial_partidas.txt`), por lo que el historial se conserva al cerrar y volver a abrir el programa.

**E.E.S.T. N.° 1 "Eduardo Ader" – Vicente López** · Laboratorio de Programación 5° 3° · Grupo G03 · Prof. Mansilla Muñoz York E.

## Integrantes

| Integrante | Rol |
|---|---|
| Ian Quiroga | Programación, validaciones y pruebas |
| Santino Laudati | Informe APA v7, cuestionario y manual del usuario |
| Dante Iglesias | Capturas de persistencia, manual del programador, CHANGELOG y Dual-Remote |

## Compilar y ejecutar

```powershell
g++ -std=c++11 src/main.cpp -o src/piedrapapelotijera.exe
.\src\piedrapapelotijera.exe
```

## Persistencia

```cpp
ofstream archivo("data/historial_partidas.txt", ios::app);  // escribe al final
ifstream archivo("data/historial_partidas.txt");            // lee el historial
```

## Repositorios

- GitHub: https://github.com/pachusUwu/piedrapapelotijera
- GitLab: https://gitlab.com/pachusUwu/piedrapapelotijera

## Documentación

- [Informe APA v7](docs/InformeEEST1_LPR2026_ACT07_G03_QuirogaLaudatiIglesias_Informe_v1.0.0.pdf)
- [Manual del programador](docs/manuales/manual_programador_v1.0.0.md) · [Manual del usuario](docs/manuales/manual_usuario_v1.0.0.md)
- [CHANGELOG](docs/CHANGELOG.md)
