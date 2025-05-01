# FCSC 2024 SOC Simulator 3/5 - Exfiltration

During the summer of 2022, an operator of vital importance (OIV) alerts the ANSSI because it believes it is the victim of a major cyber attack. The OIV’s security operation center (SOC) sends an export of its system collection over the last few days. Your job is to understand the attacker’s actions.

**Note:** The 5 parts are numbered in the chronological order of the attack, but it is not necessary to solve them in order.

----------------

Following on from what we have seen above, the attacker has collected a large amount of business data. Find the command used to collect this data.

**Flag format:** *FCSC{sha256(<UTF8 command without line feed>)}*

For example if the malicious command was *7z a "Stolen files.zip" C:\Windows\System32*, the flag would be *FCSC{91c79bc2fcb72bdc8ebf68a1f4d53d37e7b3933762b80278bdf6db14319c9948}*



Fichiers :
- [soc_events.zip](https://hackropole.fr/filer/fcsc2024-forensics-soc-simulator/public_filer/soc_events.zip)


Auteur : ribt

Origine : [SOC Simulator 3/5 - Exfiltration](https://hackropole.fr/en/challenges/forensics/fcsc2024-forensics-soc-simulator-3/)


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-forensics-soc-simulator.git

> cd fcsc2024-forensics-soc-simulator


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/en/challenges/forensics/fcsc2024-forensics-soc-simulator-3/