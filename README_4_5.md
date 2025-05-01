# FCSC 2024 SOC Simulator 4/5 - Latéralisation

During the summer of 2022, an operator of vital importance (OIV) alerts the ANSSI because it believes it is the victim of a major cyber attack. The OIV’s security operation center (SOC) sends an export of its system collection over the last few days. Your job is to understand the attacker’s actions.

**Note:** The 5 parts are numbered in the chronological order of the attack, but it is not necessary to solve them in order.

----------------

Over a short period of time, the attacker tried to connect to numerous machines, as if trying to reuse the secrets stolen in part 2. This enabled him to connect to the *Workstation2* machine. Find the source IP, the account used and the UTC time of this connection.

**Flag format (case insensitive):** *FCSC{192.168.42.27|MYCORP\Technician|2021-11-27T17:38:54}*


Fichiers :
- [soc_events.zip](https://hackropole.fr/filer/fcsc2024-forensics-soc-simulator/public_filer/soc_events.zip)


Auteur : ribt

Origine : [SOC Simulator 4/5 - Latéralisation](https://hackropole.fr/en/challenges/forensics/fcsc2024-forensics-soc-simulator-4/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-forensics-soc-simulator.git

> cd fcsc2024-forensics-soc-simulator


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/en/challenges/forensics/fcsc2024-forensics-soc-simulator-4/