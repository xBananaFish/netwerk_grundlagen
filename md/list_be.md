<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

<style>
    
html {
    scroll-behavior: smooth;
}
h1 {
    margin-left: 72px
}
  .link-wrapper {
    text-align: center;
    margin-bottom: 10px; /* Abstand zwischen Links und der Überschrift */
    background: #21252b;
    padding: 8px;
    border-radius: 6px
  }

  .link-wrapper a {
    margin: 0 10px; /* Abstand zwischen den Links */
    font-size: 16px;
    color: #a0a4af;
  }
#back-main {
    position:absolute;
    top:60px;
    left: 32px;
    width:60px;
    height: 60px;
    border-radius: 30px;
    border: 0px;
}
#back-main .material-icons {
      color: white;
      font-size: 26px;
    }
</style>

<button id="back-main" >   
<a class="material-icons" href='../netzwerk_grundlagen.md'>home</a> 
</button>
<a id="top"> </a>

# Begriffe und deren Beschreibung 

| Namen                   | Beschreibung                                                                                                             |
|:-------------------------|:------------------------------------------------------------------------------------------------------------------------|
| **Host**                 | Ein System im Netzwerk.                                                                                                 |
| **Route**                | Ein Weg zwischen Netzwerken.                                                                                            |
| **Dienst**               | Eine im Hintergrund laufende Anwendung für Systemaufgaben.                                                              |
| **PDC**                  | Primary Domain Controller – Der primäre Domänencontroller in einem Netzwerk.                                             |
| **BDC**                  | Backup Domain Controller – Der Backup-Controller in einem Netzwerk.                                                      |
| **Freigabe**             | Möglichkeit, Dateien und Verzeichnisse über das Netzwerk zu teilen.                                                      |
| **Domain**               | Ein Verbund von Systemen in einem Netzwerk, ansprechbar über einen Namen, z.B. google.de, cmb.local.                    |
| **Subdomain**            | Ein untergeordneter Bestandteil einer Domain, z.B. images.google.de (IMAGES ist die Subdomain).                          |
| **FQDN**                 | Fully Qualified Domain Name – Der vollständige Domainname, z.B. images.google.de.                                        |
| **Top-Level-Domain**      | Die höchste Ebene einer Domain, z.B. DE in google.de.                                                                    |
| **TTL**                  | Time To Live – Die maximale Anzahl an Hops bei einer Routenverfolgung.                                                   |
| **RTT**                  | Round Trip Time – Die benötigte Zeit für eine Nachricht zum Ziel und zurück.                                             |
| **HOP**                  | Ein Knotenpunkt (z.B. Router oder System), der beim Routing verwendet wird.                                              |
| **ARP**                  | Address Resolution Protocol – Dient zur Auflösung von IP-Adressen in MAC-Adressen.                                       |
| **MAC**                  | Media Access Control – Eindeutige Identifizierung einer Netzwerk-Schnittstelle.                                          |
| **IP**                   | Internet Protocol – Adressierungsprotokoll zur Vermittlung von Daten im Netzwerk.                                        |
| **Hub**                  | Ein Gerät zur Erweiterung von Netzwerken; verteilt Informationen ohne Rücksicht auf den Empfänger (Schicht 1).            |
| **Switch**               | Ein Gerät zur Erweiterung von Netzwerken; entscheidet anhand der MAC-Adressen, an welchen Host Daten gesendet werden (Schicht 2). |
| **Router**               | Ein Gerät zur Erweiterung von Netzwerken; trifft Routing-Entscheidungen basierend auf IP-Adressen (Schicht 3).           |
| **RFC**                  | Request for comments                                                                                                     |
| **TCP**                  | Transmission Control Protocol                                                                                                    |
| **UDP**                  | User Datagram Protocol                |
| **Port**                  | Eine Durchwahl/Erweiterung zu einer IP-Adresse. Wird in der Regel durch einen Doppelpunkt hinter der IP Adresse angegeben 192.168.0.1:80 |
| **MSB**                  | Most Significant Bit/Byte First. Beispielwerte: `A0 B0 C0 D0 E0 F0` ->  `A0 B0 C0 D0 E0 F0`  |
| **LSB**                  | Last Significant Bit/Byte First. Beispielwerte: `A0 B0 C0 D0 E0 F0` -> `0F 0E 0D 0C 0B 0A`   |
| **Endianess**            | Angabe in welcher Dimension Datenströme / Dateninformationen aufhören- Aufgeteilt in Big - und little Endian.|
| **Big-Endianess**        | Die höchstwertige Information steht an letzter Stelle. Beispiel in Dezimalzahlen: 723726 -> 627327               |
| **Little-Endianess**     | Die niedrigstwertige Information steht an letzter Stelle. Beispiel in Dezimalzahlen: 723726 -> 723726               |

