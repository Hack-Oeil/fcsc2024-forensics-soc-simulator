# FCSC 2024 SOC Simulator 4/5 - Latéralisation

Durant l’été 2022, un opérateur d’importance vitale (OIV) alerte l’ANSSI car il pense être victime d’une cyberattaque d’ampleur. Le security operation center (SOC) de l’OIV envoie à l’ANSSI un export de sa collecte système des derniers jours. Vous êtes chargé de comprendre les actions réalisées par l’attaquant.

**Note :** Les 5 parties sont numérotées dans l’ordre chronologique de l’attaque mais il n’est pas nécessaire de les résoudre dans l’ordre.

----------------

Sur une courte période de temps, l’attaquant a essayé de se connecter à de nombreuses machines, comme s’il essayait de réutiliser les secrets volés dans la partie 2. Cela lui a permis de se connecter à la machine *Workstation2*. Retrouver l’IP source, le compte utilisé et l’heure UTC de cette connexion.


**Format du flag (insensible à la casse):** *FCSC{192.168.42.27|MYCORP\Technician|2021-11-27T17:38:54}*


Fichiers :
- [soc_events.zip](https://hackropole.fr/filer/fcsc2024-forensics-soc-simulator/public_filer/soc_events.zip)


Auteur : ribt

Origine : [SOC Simulator 4/5 - Latéralisation](https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-soc-simulator-4/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-forensics-soc-simulator.git

> cd fcsc2024-forensics-soc-simulator


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-soc-simulator-4/