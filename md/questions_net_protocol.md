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


###### {#top}

# Aufgabe(n) (Netzwerk-Protokolle):


- [Welche Bezeichnung hat der Stecker bei Ethernet-Netzwerkkabeln ( CAT )](#1)
- [Benenne das Protokoll, welches in einem Ethernet-Netzwerk die Umwandlung von einer logischen IP-Adresse in eine pysische MAC Adresse durchführt.](#2)
- [Wozu wird das IP-Protokoll genutzt?](#3)
- [Auf welcher OSI-Schicht befindet sich das IP-Protokoll](#4)
- [Was bedeutet DNS?](#5)
- [Beschreibe den Ablauf einer DNS-Abfrage](#6)
- [Recherchiere gängige Ethernet Übertragungsmedien (z.B. 1000-Base-T 10-Base-T) inkl. deren Geschwindigkeiten](#7)
- [Recherchiere das Protokoll IEEE802](#8)
- [Recherchiere Network-Byte-Order (hatten wir am Mittwoch kurz besprochen)](#9)
- [Wofür steht IEEE und OSI?](#10)

---

##### Welche Bezeichnung hat der Stecker bei Ethernet-Netzwerkkabeln ( CAT ) {#1}

> `Der Stecker, der bei Ethernet-Netzwerkkabeln (z. B. Cat5, Cat5e, Cat6) verwendet wird, heißt RJ-45. Der RJ-45-Stecker hat acht Pins und wird für die Verbindung von Twisted-Pair-Kabeln in Ethernet-Netzwerken eingesetzt.`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#2">nächster</a>
  <a href="#top">nach oben</a>
</div>

---
##### Benenne das Protokoll, welches in einem Ethernet-Netzwerk die Umwandlung von einer logischen IP-Adresse in eine physische MAC-Adresse durchführt. {#2}

> `Das Protokoll, das in einem Ethernet-Netzwerk die Umwandlung von einer logischen IP-Adresse in eine physische MAC-Adresse durchführt, ist das Address Resolution Protocol (ARP). ARP ermöglicht es einem Gerät, die MAC-Adresse eines anderen Geräts im selben Netzwerk zu ermitteln, um eine direkte Kommunikation über Ethernet zu ermöglichen.`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#1">vorheriger</a>
  <a href="#3">nächster</a>
  <a href="#top">nach oben</a>
</div>

---
##### Wozu wird das IP-Protokoll genutzt? {#3}

> - `Datenpakete zu adressieren: Es ermöglicht die Identifikation und Adressierung von Geräten in einem Netzwerk durch IP-Adressen (z. B. IPv4 oder IPv6).`
> - `Datenverkehr zu routen: IP sorgt dafür, dass Datenpakete von der Quelle zum Ziel über verschiedene Netzwerke weitergeleitet werden.`
> - `Verbindung von Netzwerken: Es ermöglicht die Kommunikation zwischen verschiedenen Netzwerken und stellt sicher, dass Daten über das Internet oder andere Netzwerke ausgetauscht werden können.`
> - `Fehlerbehandlung: IP enthält Mechanismen zur Fragmentierung und Wiederzusammensetzung von Datenpaketen, um die Übertragung über unterschiedliche Netzwerke zu optimieren.`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#2">vorheriger</a>
  <a href="#4">nächster</a>
  <a href="#top">nach oben</a>
</div>


---

##### Auf welcher OSI-Schicht befindet sich das IP-Protokoll? {#4}

> `Das IP-Protokoll (Internet Protocol) befindet sich auf der dritten Schicht des OSI-Modells, der Netzwerkschicht. Diese Schicht ist verantwortlich für die Weiterleitung von Datenpaketen über verschiedene Netzwerke hinweg und für die Adressierung der Geräte im Netzwerk.`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#3">vorheriger</a>
  <a href="#5">nächster</a>
  <a href="#top">nach oben</a>
</div>

---
##### Was bedeutet DNS? {#5}

> `DNS steht für Domain Name System. Es ist ein hierarchisches System, das dafür verantwortlich ist, Domainnamen (wie www.example.com) in IP-Adressen (wie 192.0.2.1) umzuwandeln. DNS ermöglicht es Benutzern, Websites über leicht merkbare Namen anstelle von numerischen IP-Adressen zu erreichen. Es spielt eine entscheidende Rolle im Internet, indem es die Benutzerfreundlichkeit erhöht und die Kommunikation zwischen Geräten erleichtert.`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#4">vorheriger</a>
  <a href="#6">nächster</a>
  <a href="#top">nach oben</a>
</div>


---
##### Beschreibe den Ablauf einer DNS-Abfrage. {#6}

> - `Anwendungsebene: Eine Anwendung (z. B. ein Webbrowser) benötigt die IP-Adresse einer Domain. Der Benutzer gibt eine URL ein (z. B. www.example.com).`
> - `Überprüfung im Cache: Der Browser überprüft zuerst seinen eigenen Cache, um zu sehen, ob die IP-Adresse bereits gespeichert ist.`
> - `Anfrage an den DNS-Resolver: Wenn der Cache leer ist, sendet der Browser eine DNS-Anfrage an einen DNS-Resolver (in der Regel der DNS-Server des Internetdienstanbieters).`
> - `Anfrage an die Root-Server: Der DNS-Resolver fragt einen der Root-DNS-Server, der Informationen über die Top-Level-Domains (TLD) hat (z. B. .com, .org).`
> - `TLD-Server: Der Root-Server verweist den Resolver an den zuständigen TLD-DNS-Server (z. B. für .com).`
> - `Authoritative DNS-Server: Der TLD-Server gibt die Adresse des authoritativen DNS-Servers für die spezifische Domain zurück (z. B. den DNS-Server von example.com).`
> - `Abruf der IP-Adresse: Der DNS-Resolver fragt nun den authoritativen DNS-Server, der die IP-Adresse für die angeforderte Domain bereitstellt.`
> - `Antwort zurück an den Resolver: Der authoritative DNS-Server sendet die IP-Adresse zurück an den DNS-Resolver.`
> - `Cache speichern: Der DNS-Resolver speichert die IP-Adresse im Cache für zukünftige Anfragen.`
> - `Antwort an den Browser: Schließlich sendet der DNS-Resolver die IP-Adresse zurück an den Browser, der die Verbindung zur gewünschten Website herstellt.`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#5">vorheriger</a>
  <a href="#7">nächster</a>
  <a href="#top">nach oben</a>
</div>


---
##### Recherchiere gängige Ethernet Übertragungsmedien (z.B. 1000-Base-T, 10-Base-T) inkl. deren Geschwindigkeiten. {#7}

> - `10-Base-T: Überträgt Daten mit 10 Mbit/s über Kupfer-Twisted-Pair-Kabel (Cat3).`
> - `100-Base-TX (Fast Ethernet): Überträgt mit 100 Mbit/s über Twisted-Pair-Kabel (Cat5).`
> - `1000-Base-T (Gigabit Ethernet): Überträgt mit 1 Gbit/s über Kupfer-Twisted-Pair-Kabel (Cat5e, Cat6).`
> - `10G-Base-T: Überträgt mit 10 Gbit/s über Kupfer-Twisted-Pair-Kabel (Cat6a oder besser).`
> - `1000-Base-LX: Überträgt 1 Gbit/s über Glasfaserkabel (bis zu 5 km Reichweite).`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#6">vorheriger</a>
  <a href="#8">nächster</a>
  <a href="#top">nach oben</a>
</div>


---

##### Recherchiere das Protokoll IEEE802. {#8}

>    `IEEE 802 ist eine Protokollfamilie für Netzwerke, die Standards für kabelgebundene (Ethernet, 802.3) und drahtlose (WLAN, 802.11) Kommunikation definiert. Sie regelt die physische und die Sicherungsschicht im OSI-Modell und sorgt für Kompatibilität in Netzwerken.`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#7">vorheriger</a>
  <a href="#9">nächster</a>
  <a href="#top">nach oben</a>
</div>


---

##### Recherchiere Network-Byte-Order (hatten wir am Mittwoch kurz besprochen). {#9}
>   `Network Byte Order ist die Big Endian-Reihenfolge, bei der das höchstwertige Byte zuerst übertragen wird. Es ist der Standard für Datenübertragung im Netzwerk, um Kompatibilität zwischen verschiedenen Computersystemen zu gewährleisten.`

<div class="link-wrapper">
<a href="#bottom">nach unten</a>
  <a href="#8">vorheriger</a>
  <a href="#10">nächster</a>
  <a href="#top">nach oben</a>
</div>


---

##### Wofür steht IEEE und OSI? {#10}

###### IEEE
>   `IEEE steht für Institute of Electrical and Electronics Engineers, eine Organisation, die technische Standards für Elektronik und Kommunikation entwickelt, einschließlich Netzwerktechnologien wie IEEE 802.`
###### OSI
>   `OSI steht für Open Systems Interconnection. Es ist ein Referenzmodell, das Netzwerke in 7 Schichten unterteilt, um die Kommunikation zwischen verschiedenen Systemen standardisiert zu beschreiben.`

<div class="link-wrapper">
  <a href="#9">vorheriger</a>
  <a href="#top">nach oben</a>
</div>

# {#bottom}

