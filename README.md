# Données de la sonde multiparamétrique entre décembre 2024 et octobre 2025 

_Association Estuaires Loire & Vilaine_

Dans le cadre du projet de restauration des laminaires dans la Baie du Pouliguen/la Baule mené par l'Assocation ELV, une sonde (EXO3, Xylem) a été placée sur le site de restauration en décembre 2024 et depuis mesure chaque heure la température, turbidité, salinité, et pH. Une période d'absence de données est à noter entre mi-avril et mi-juin 2025 pour cause d'erreur de manipulation.

Les données brutes entre décembre 2024 et avril 2025 sont disponibles [ici](https://github.com/olegouvello/ELV_analyse_sonde_2025/blob/6ae16863dfb6172c27f1b750d2826ebdc1b09ff4/donnees_decembre-avril.csv), celles entre juin et fin septembre [ici](https://github.com/olegouvello/ELV_analyse_sonde_2025/blob/c684b16c1bbe2db620eb5ba4a3ffa0050b4ec432/donnees_juin_septembre.csv), et les données compilées pour l'ensemble de la période sont disponibles [ici](https://github.com/olegouvello/ELV_analyse_sonde_2025/blob/7b8649dde6ac546731c805a691b0075632e45233/donnees_decembre_septembre.csv). 

**Comprendre les différentes variables** : 

Paramètres environnementaux : 
- COND (µS/cm) → conductivité brute de l’eau (capacité à conduire un courant, liée aux ions dissous).
- SPCOND (µS/cm) → conductivité spécifique corrigée à 25 °C (pour comparer entre différentes températures).
- TDS (mg/L) → solides dissous totaux (masse totale de sels dissous).
- SAL (PSU) → salinité en unités pratiques (0 = eau douce, ~35 = eau de mer).
- NLF COND (µS/cm) → conductivité non corrigée de la température (valeur brute).
- TEMP (°C) → température de l’eau.
- pH → acidité ou basicité de l’eau (7 = neutre).
- pH mV → potentiel en millivolts mesuré par l’électrode pH (utilisé pour la calibration)
- TURBIDITY (FNU - Formazin Nephelometric Unit) → turbidité (mesure la clarté de l’eau, plus la valeur est élevée, plus l’eau est trouble).

Paramètres de la sonde :
- CABLE PWR V → tension d’alimentation fournie par le câble.
- BATTERY V → tension de la batterie interne (indique l’état de charge)
- WIPER POSITION VOLT → tension indiquant la position du balai nettoyeur (assure le nettoyage automatique du capteur optique).


Contact: olivia.legouvello@gmail.com
