# FCSC 2024 SOC Simulator 3/5 - Exfiltration

Durant l’été 2022, un opérateur d’importance vitale (OIV) alerte l’ANSSI car il pense être victime d’une cyberattaque d’ampleur. Le security operation center (SOC) de l’OIV envoie à l’ANSSI un export de sa collecte système des derniers jours. Vous êtes chargé de comprendre les actions réalisées par l’attaquant.

**Note :** Les 5 parties sont numérotées dans l’ordre chronologique de l’attaque mais il n’est pas nécessaire de les résoudre dans l’ordre.

----------------

Dans la continuité de ce qui été vu précédemment, l’attaquant a collecté une quantité importante de données métier. Retrouver la commande qui a permis collecter de tous ces éléments.


**Format du flag (insensible à la casse):** *FCSC{sha256(<UTF8 command without line feed>)}*

Par exemple si la commande malveillante était *7z a "Stolen files.zip" C:\Windows\System32*, le flag serait *FCSC{91c79bc2fcb72bdc8ebf68a1f4d53d37e7b3933762b80278bdf6db14319c9948}*



Fichiers :
- [soc_events.zip](https://hackropole.fr/filer/fcsc2024-forensics-soc-simulator/public_filer/soc_events.zip)


Auteur : ribt

Origine : [SOC Simulator 3/5 - Exfiltration](https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-soc-simulator-3/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-forensics-soc-simulator.git

> cd fcsc2024-forensics-soc-simulator


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-soc-simulator-3/