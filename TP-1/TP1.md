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

**☀️ Table de routage**

    C:\Users\eloua>arp -a
    Interface : 10.33.73.71 --- 0x3

**☀️ Hosts ?**

    C:\Windows\System32\drivers\etc\
    1.1.1.1    b2.hello.vous
    C:\Users\eloua>ping b2.hello.vous

    Envoi d’une requête 'ping' sur b2.hello.vous [1.1.1.1] avec 32 octets de données :
    Réponse de 1.1.1.1 : octets=32 temps=19 ms TTL=55
    Réponse de 1.1.1.1 : octets=32 temps=43 ms TTL=55
    Réponse de 1.1.1.1 : octets=32 temps=403 ms TTL=55
    Réponse de 1.1.1.1 : octets=32 temps=243 ms TTL=55

    Statistiques Ping pour 1.1.1.1:
        Paquets : envoyés = 4, reçus = 4, perdus = 0 (perte 0%),
    Durée approximative des boucles en millisecondes :
        Minimum = 19ms, Maximum = 403ms, Moyenne = 177ms
    
**☀️ Go mater une vidéo youtube et déterminer, pendant qu'elle tourne...**

    Adresse IP : 10.33.73.71
    Port : 443
    Port local : 65153

**☀️ Requêtes DNS**

    C:\Users\eloua>ping www.thinkerview.com
    Envoi d’une requête 'ping' sur www.thinkerview.com [188.114.97.7] avec 32 octets de données :
    Réponse de 188.114.97.7 : octets=32 temps=15 ms TTL=55

    C:\Users\eloua>nslookup 143.90.88.12
    Serveur :   dns.google
    Address:  8.8.8.8

    Nom :    EAOcf-140p12.ppp15.odn.ne.jp
    Address:  143.90.88.12

**☀️ Hop hop hop**

    C:\Users\eloua>tracert ynov.Com

    Détermination de l’itinéraire vers ynov.Com [104.26.10.233]
    avec un maximum de 30 sauts :

    1     2 ms     1 ms     1 ms  10.33.79.254
    2     6 ms     2 ms     2 ms  145.117.7.195.rev.sfr.net [195.7.117.145]
    3     3 ms    11 ms     3 ms  237.195.79.86.rev.sfr.net [86.79.195.237]
    4     6 ms     3 ms     4 ms  196.224.65.86.rev.sfr.net [86.65.224.196]
    5    13 ms    12 ms    10 ms  164.147.6.194.rev.sfr.net [194.6.147.164]
    6   154 ms    53 ms     *     162.158.20.24
    7    17 ms    15 ms    15 ms  162.158.20.240
    8   175 ms   307 ms   342 ms  104.26.10.233

    Itinéraire déterminé.

**☀️ IP publique**

    C:\Users\eloua>curl ipconfig.me
    Moved Permanently. Redirecting to https://ifconfig.me/
    IP Address	195.7.117.146