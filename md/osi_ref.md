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

# Das OSI – Referenzmodell 

| Schicht             | Beschreibung                                                                 |
|:--------------------|:---------------------------------------------------------------------------- |
| 7. Anwendungsschicht | Stellt Dienste für Anwendungen bereit, wie z.B. HTTP, FTP, SMTP. Sie ist die Schnittstelle zwischen Anwendungssoftware und Netzwerk. |
| 6. Darstellungsschicht | Verarbeitet Datenformate, Verschlüsselung und Kompression. Sie sorgt dafür, dass Daten für die Anwendungsschicht richtig interpretiert werden. |
| 5. Sitzungsschicht   | Verantwortlich für die Verwaltung von Sitzungen zwischen zwei Kommunikationsendpunkten (z.B. Aufbau, Verwaltung und Beendigung einer Sitzung). |
| 4. Transportschicht  | Gewährleistet eine zuverlässige Übertragung der Daten zwischen den Endgeräten. Protokolle wie TCP (zuverlässig) oder UDP (nicht zuverlässig) arbeiten auf dieser Schicht. |
| 3. Vermittlungsschicht | Regelt die logische Adressierung und Weiterleitung von Datenpaketen über das Netzwerk. Das Internetprotokoll (IP) ist auf dieser Schicht angesiedelt. |
| 2. Sicherungsschicht | Sorgt für eine fehlerfreie Übertragung der Daten auf der physikalischen Ebene. Sie kümmert sich um MAC-Adressen und den Zugang zum Übertragungsmedium. |
| 1. Bitübertragungsschicht | Überträgt die Rohdaten als Bits über das physikalische Medium (z.B. Kabel, Funk). Sie umfasst elektrische und physikalische Spezifikationen der Verbindung. |

