# ArduinoOpta

Ce dépôt regroupe des projets d’automatisation pour **Arduino Opta**, combinant :

- des projets PLC (`.plcprj`, `.wkpx`, `.imgx`),
- une logique Arduino (`LLSketch/LLSketch.ino`),
- des configurations réseau/terrain (ex. `ModbusTCP.conf`),
- des dossiers de build et d’export générés automatiquement.

## Structure principale

- **R2D1/**, **R2D3/**, **R2D4/**, **R2D5/** : variantes du projet (versions/équipements différents).
- **Build/** : artefacts de compilation PLC.
- **LLSketch/** : code embarqué Arduino associé au projet PLC.
- **LLSketch_build/** : fichiers de build Arduino générés.
- **PreviousVersions/** : historiques/anciennes versions.

## Objectif

Fournir une base de développement et de déploiement pour des applications industrielles sur Arduino Opta, avec communication Modbus TCP et logique mixte PLC + sketch Arduino.
