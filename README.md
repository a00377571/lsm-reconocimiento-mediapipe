# lsm-reconocimiento-mediapipe
Desarrollar un prototipo (MVP) para el reconocimiento de un conjunto de **K señas** de Lengua de Señas Mexicana (LSM) a partir de video, utilizando **visión computacional** y extracción de **landmarks** con **MediaPipe**, con una demo funcional y evaluación acordada con el sponsor.
# Proyecto LSM (Visión + MediaPipe): Reconocimiento de señas

## Objetivo
Desarrollar un prototipo (MVP) para el reconocimiento de un conjunto de **K señas** de Lengua de Señas Mexicana (LSM) a partir de video, utilizando **visión computacional** y extracción de **landmarks** con **MediaPipe**, con una demo funcional y evaluación acordada con el sponsor.

## Integrantes
- Hugo Enrique Navarro Villeda 
- Miguel Octavio Ramírez Romero
- Marco Antonio Arellano Hernández

- Asesor/a: Dr. Raúl Valente Ramírez Velarde

## Alcance (MVP)
- Entrada: clips de video segmentados (1 clip = 1 seña) o videos pregrabados (según se defina).
- Salida: seña predicha + puntaje de confianza.
- Métricas: accuracy (definida por sponsor) y métricas complementarias (p. ej., F1 macro).

## Estructura del repositorio
- `data/`: datos (o instrucciones para acceder a ellos), estructura y diccionario de metadatos.
- `notebooks/`: análisis exploratorio, experimentos y prototipos.
- `docs/`: documentación del proyecto y entregables del curso (semanas 1, 2, 8 y 9).
- `src/`: scripts reutilizables (extracción de keypoints, features, entrenamiento, etc.).

## Cómo ejecutar (rápido)
1. Crear entorno e instalar dependencias:
   ```bash
   pip install -r requirements.txt
