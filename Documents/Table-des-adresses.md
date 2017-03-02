# Table des adresses

Ce document rescence l'ensemble des adresses, interfaces, masques et noms des appliance réseau.

### Routeurs

|Appliance     |Interface|Vlan|Adresse      |Masque         |Direction   |
|--------------|---------|----|-------------|---------------|------------|
|MainRouterBack|S0/0     |-   |public       |public         |Internet    |
|              |G0/0     |    |             |               |PublicSwitch|
|              |G0/0.130 |130 |192.168.3.2  |255.255.255.128|            |
|||||||
|MainRouterBack|S0/0     |-   |public       |public         |Internet    |
|              |G0/0     |    |             |               |PublicSwitch|
|              |G0/0.130 |130 |192.168.3.3  |255.255.255.128|            |
|||||||
|MainRouterPool|Vlan10   |10  |192.168.3.241|255.255.255.240|            |
|              |Vlan20   |20  |192.168.3.145|255.255.255.248|            |
|              |Vlan130  |130 |192.168.3.1  |255.255.255.128|            |
|||||||
