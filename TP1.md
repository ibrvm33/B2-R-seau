# TP1 : Maîtrise réseau du votre poste

## Basics

**☀️ Carte réseau WiFi**

    C:\Users\eloua>ipconfig /all
    Adresse physique . . . . . . . . . . . : 40-1A-58-3B-37-EC
    Adresse IPv4. . . . . . . . . . . . . .: 10.33.73.71
    Masque de sous-réseau. . . . . . . . . : 255.255.240.0 /20

**☀️ Déso pas déso**

    L'adresse réseau (LAN) est 10.33.64.0.
    L'adresse de broadcast est 10.33.64.255
    La plage d'adresse IP est 10.33.64.1 à 10.33.79.254

**☀️ Hostname** 

    C:\Users\eloua>hostname
    Ibrahim

**☀️ Passerelle du réseau**

    C:\Users\eloua>ipconfig
    Passerelle par défaut. . . . . . . . . : 10.33.79.254
    C:\Users\eloua>arp -a
    10.33.79.254          7c-5a-1c-d3-d8-76     dynamique