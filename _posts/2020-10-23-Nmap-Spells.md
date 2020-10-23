---
title: Nmap Spells
date: 2020-10-23 12:55:00
categories: 
tags:      # TAG names should always be lowercase
---

**No Ping**

`nmap -Pn 192.168.0.1` 

**TCP SYN Scan (half-open scan)**

`nmap -sS 192.168.0.1`

**TCP FULL Scan**

`nmap -sT 192.168.0.1`

**UDP Scan**

`nmap -sU 192.168.0.1`

**XMAS Scan**

`nmap -sX 192.168.0.1`

**IDLE Scan**

`nmap -sI aqui.la.ip.zombie 192.168.0.1`

**Version Detection**

`nmap -sV 192.168.0.1`

**OS Detection**

`nmap -O 192.168.0.1`

**Para indicar un puerto**

`nmap -p 80 192.168.0.1`

**Para indicar rango de puertos**

`nmap -p 1-50 192.168.0.1`

**Modo verbose**

`nmap -v 192.168.0.1`

**Scripts**

`nmap --script=nombre-del-script 192.168.0.1`

`nmap --script=http-enum 192.168.1.0`

**Timing (de 0 a 5, de mas lento a mas agresivo)**

Paranoid:

`nmap -T0 192.168.0.1` 

Sneaky:

`nmap -T1 192.168.0.1`

Polite:

`nmap -T2 192.168.0.1`

Normal:

`nmap -T3 192.168.0.1`

Agressive:

`nmap -T4 192.168.0.1`

Insane:

`nmap -T5 192.168.0.1`

**Output**

Normal output:

`nmap -oN nombrearchivo 192.168.0.1`

XML output:

`nmap -oX nombrearchivo 192.168.0.1`

**Para mas info:**

https://nmap.org/
