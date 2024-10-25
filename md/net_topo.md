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

# Netzwerk-Topologien

![The Markdown logo](../NetzwerkTopologien.png)


<a id='5-1'></a>

#### Ring-Topologie
In einer Ring-Topologie sind die Geräte in einem geschlossenen Kreis miteinander verbunden. Daten werden in eine Richtung von einem Gerät zum nächsten weitergeleitet. Ein Ausfall eines Geräts kann das gesamte Netzwerk stören.

<a id='5-2'></a>

#### Vermaschte Topologie
In einer vermaschten Topologie sind alle Geräte miteinander verbunden, sodass mehrere Verbindungen zwischen ihnen bestehen. Dies erhöht die Redundanz und Ausfallsicherheit, da die Daten mehrere Wege nehmen können.

<a id='5-3'></a>

#### Stern-Topologie
In einer Stern-Topologie sind alle Geräte an ein zentrales Gerät (z.B. einen Switch oder Hub) angeschlossen. Die Kommunikation erfolgt über dieses zentrale Gerät. Ein Ausfall des zentralen Geräts kann das gesamte Netzwerk lahmlegen, während die einzelnen Geräte unabhängig voneinander funktionieren können.


<a id='5-4'></a>

#### Vollvermaschte Topologie
Eine Vollvermaschte Topologie ist eine spezielle Form der vermaschten Topologie, bei der jedes Gerät direkt mit jedem anderen Gerät verbunden ist. Dies bietet maximale Redundanz und Ausfallsicherheit, ist jedoch teuer und aufwendig in der Implementierung.

<a id='5-5'></a>

#### Linien-Topologie
In einer Linien-Topologie sind die Geräte in einer linearen Anordnung miteinander verbunden. Daten werden in eine Richtung über die Verbindung gesendet. Ein Ausfall eines Geräts oder der Verbindung kann die Kommunikation zwischen den Geräten unterbrechen.

<a id='5-6'></a>

#### Baum-Topologie
Eine Baum-Topologie ist eine hierarchische Struktur, die aus mehreren Stern-Topologien besteht, die miteinander verbunden sind. Ein zentraler Knoten dient als Wurzel, von dem mehrere Ebenen von Knoten abzweigen. Dies ermöglicht eine einfache Erweiterung des Netzwerks, kann aber bei einem Ausfall des zentralen Knotens Probleme verursachen.


<a id='5-7'></a>

#### Bus-Topologie
In einer Bus-Topologie sind alle Geräte an ein einzelnes Übertragungsmedium (Bus) angeschlossen. Daten werden an alle Geräte gesendet, aber nur das Zielgerät verarbeitet die Informationen. Ein Ausfall des Busses kann das gesamte Netzwerk stören.


