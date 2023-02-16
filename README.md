# Projet ISIMA ZZ2 F1
> Projet ISIMA de ZZ2 F1 sur la récupération et le traitement d'un signal sonore afin de piloter différents types de sorties. 

## Informations générales

- `Étudiants` : Jamila KAMAL, Thomas QUENTEL
- `Tuteur` : Jean-Thierry BODIN (jeanthierrybodin@gmail.com 06 79 69 59 98) développeur embarqué diplômé de l'ISIMA
- `École` : ESACM (École Supérieure d'Art de Clermont Métropole)
- `Mots clés` : Traitement du signal, Temps réel, Pilotage d'appareil
- `Durée` : 60h par étudiant

## Objectifs et description du travail à réaliser  
Dans le cadre de la réalisation du projet de diplôme de Lauriane Charière--Fiedler (DNSEP), elle recherche quelqu’un pour l’accompagner dans la programmation d’un logiciel embarqué.  
Elle souhaite réaliser des installations immersives qui nécessitent le traitement de données sonores captées en direct afin de contrôler différentes sorties en fonction de la composition  du son (fréquence, puissance, etc.).  
Dans un premier temps la sortie pilotée serait un générateur relié à un système électrolyse.  
L'installation a pour but de capter des ressources sonores en in situ afin de créer une variation électrique dans le contrôle des électrolyses pour effectuer des gravures sur cuivre. 
Le logiciel sera installé sur ordinateur et tous les équipements utilisés seront choisis après échanges avec les étudiants du projet. 

## Matériels/Langages
- C
- Labview

## Structure du programme:
- main.vi
  - recuperation_microphones.vi
  - acquisition_son.vi
  - traitement_son.vi
    - moyennage.vi
  - variable_stop_globale.vi
