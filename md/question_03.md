# Aufgabe (Größen und Geschwindigkeiten)

## 1. Ablauf einer IP zu MAC Adressauflösung

Die Auflösung einer IP-Adresse in eine MAC-Adresse erfolgt typischerweise über das Address Resolution Protocol (ARP). Der Ablauf ist wie folgt:

1. **ARP-Anfrage**: Ein Gerät, das die MAC-Adresse zu einer bestimmten IP-Adresse benötigt, sendet eine ARP-Anfrage im Netzwerk. Diese Anfrage wird als Broadcast gesendet, sodass alle Geräte im lokalen Netzwerk erreicht werden.
  
2. **ARP-Antwort**: Das Gerät mit der entsprechenden IP-Adresse empfängt die ARP-Anfrage und antwortet mit seiner MAC-Adresse. Diese Antwort wird direkt an die MAC-Adresse des anfragenden Geräts gesendet.

3. **Speichern der Adressen**: Der anfragende Computer speichert die IP- und MAC-Adresse in seiner ARP-Tabelle für zukünftige Anfragen, um die Anzahl der ARP-Anfragen im Netzwerk zu minimieren.

## 2. Abkürzungen

- **ARP**: Address Resolution Protocol
- **DHCP**: Dynamic Host Configuration Protocol
- **MAC**: Media Access Control
- **IP**: Internet Protocol
- **TCP**: Transmission Control Protocol
- **UDP**: User Datagram Protocol

## 3. Was ist ein Port?

Ein Port kann auch als **Kommunikationsschnittstelle** bezeichnet werden. Es handelt sich um eine numerische Kennung, die es ermöglicht, verschiedene Netzwerkdienste zu unterscheiden und Datenströme korrekt zuzuordnen.

## 4. Was ist ein Internet-Knotenpunkt?

Ein Internet-Knotenpunkt ist eine zentrale Stelle im Internet, an der Datenströme zusammenlaufen und weitergeleitet werden. Knotenpunkte können Router, Switches oder Server sein, die dazu dienen, Netzwerkverkehr zwischen verschiedenen Netzwerken zu steuern.

## 5. Nenne 4 Internet Knotenpunkte, mit Standort und des aktuellen Datendurchsatzes

1. **Amsterdam Internet Exchange (AMS-IX)**
   - **Standort**: Amsterdam, Niederlande
   - **Aktueller Datendurchsatz**: Über 6 Terabit pro Sekunde

2. **DE-CIX**
   - **Standort**: Frankfurt, Deutschland
   - **Aktueller Datendurchsatz**: Über 7 Terabit pro Sekunde

3. **Equinix IX**
   - **Standort**: San Francisco, USA
   - **Aktueller Datendurchsatz**: Über 1 Terabit pro Sekunde

4. **LINX (London Internet Exchange)**
   - **Standort**: London, Großbritannien
   - **Aktueller Datendurchsatz**: Über 3 Terabit pro Sekunde

## 6. Gründe für den massiven Zuwachs an Traffic im Knotenpunkt Sao Paulo in den vergangenen 10 Jahren

- **Wachstum der Internetnutzung**: Steigende Anzahl von Nutzern und Geräten, die Internetzugang benötigen.
- **E-Commerce**: Zunahme von Online-Shopping und digitalen Dienstleistungen, die hohe Bandbreite erfordern.
- **Streaming-Dienste**: Beliebtheit von Video-Streaming-Diensten, die einen hohen Datendurchsatz erfordern.
- **Cloud-Dienste**: Verstärkter Einsatz von Cloud-Computing und -Speicher, die den Datenverkehr erhöhen.

## 7. Theoretische Adressen bei IPv4

Bei IPv4 gibt es theoretisch **4,3 Milliarden** (2^32) mögliche IP-Adressen.


<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

<style>
  html {
    scroll-behavior: smooth;
  }

  h1 {
    margin-left: 72px;
  }

  hr {
    height: 5px;
    background-color: red;
    border: none;
    margin: 20px 0;
  }

  .link-wrapper {
    text-align: center;
    margin-bottom: 10px;
    background: #21252b;
    padding: 8px;
    border-radius: 6px;
  }

  .link-wrapper a {
    margin: 0 10px;
    font-size: 16px;
    color: #a0a4af;
  }

  #back-main {
    position: absolute;
    top: 60px;
    left: 32px;
    width: 60px;
    height: 60px;
    border-radius: 30px;
    background-color: #21252b;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  #back-main a {
    color: white;
    font-size: 26px;
  }

</style>

<div id="back-main">
  <a class="material-icons" href='../netzwerk_grundlagen.md'>home</a> 
</div>
