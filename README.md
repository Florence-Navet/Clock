# Clock
projet de groupe à quatre
# Clock with Alarm

## Description

Ce projet implémente une horloge numérique interactive avec une fonctionnalité d'alarme. L'utilisateur peut choisir le format de l'heure (12h ou 24h), définir une heure de départ et, éventuellement, configurer une alarme. L'application affiche en continu l'heure et déclenche un message lorsque l'alarme est activée.

---

## Fonctionnalités

- **Affichage de l'heure :**
  - Format 12 heures (AM/PM) ou 24 heures.
  - Incrémentation des secondes, minutes et heures.

- **Alarme :**
  - Possibilité de définir une alarme pour une heure précise.
  - Affichage d'un message "Ring ring! Ring ring!" lorsque l'alarme se déclenche.
  - L'alarme reste active pendant 10 secondes.

- **Interactions utilisateur :**
  - Saisie de l'heure de départ et de l'heure de l'alarme.
  - Choix entre format 12 heures ou 24 heures.

---

## Structure des fichiers

- **`test.py`** : Contient le script principal pour exécuter l'horloge et l'alarme.
- **`timeclass.py`** : Implémente les classes principales `Time` et `Alarm`.

---

## Prérequis

- Python 3.x
- Bibliothèques Python :
  - `time`
  - `keyboard`

---

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/<nom-utilisateur>/<nom-du-depot>.git
   ```
2. Accédez au répertoire:  
   ```bash
   cd clock  
   ```
3. Installez les bibliothèques nécessaires :
   ```bash
   pip install keyboard
   ```
# Utilisation  

1. Lancez le programme :
   ```bash
   python test.py
   ```
2. Suivez les instructions à l'écran pour :
   + Choisir le format d'heure (12h/24h).
   + Définir une heure de départ.
   + Configurer une alarme (optionnel).
3. Appuyez sur la touche A pour interagir avec le programme et sur B pour quitter une action spécifique.

___

