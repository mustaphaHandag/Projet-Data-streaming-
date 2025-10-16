# 🌤️ Weather IoT – Real-Time Data Streaming Simulation

## 🧩 Description

**Weather IoT** (Internet of Things) est un projet de simulation de streaming de données météorologiques.  
L’objectif est de reproduire le comportement d’un réseau de capteurs IoT mesurant la **température**, l’**humidité** et la **luminosité**, puis d’envoyer ces données dans un flux de streaming en temps réel.

Le projet se compose de deux notebooks principaux :

- **`V3Projet_streaming_Producer.ipynb`** : simule un capteur IoT qui génère et envoie des données météorologiques.
- **`V3Projet_streaming_Consumer.ipynb`** : récupère et traite ces données pour analyse ou visualisation.

---

## ⚙️ Architecture du projet

```text
+----------------+       +----------------+
|  IoT Producer  | --->  |  IoT Consumer  |
|  (Simulation)  |       |  (Processing)  |
+----------------+       +----------------+
        |                        |
        |                        |
        +------->  Kafka / Stream  <--------+
# Projet-Data-streaming-
Simulez les données des capteurs IoT (température, humidité, etc.) dans Kafka, traitez-les avec Spark Structured Streaming et déclenchez des alertes ou des notifications pour des seuils
