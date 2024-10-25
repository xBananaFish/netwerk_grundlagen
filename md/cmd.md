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


# Kommandozeile (cmd): Befehle und Beschreibungen 

|Befehl|Beschreibung|
|:-------------------------|:-------------------------|
| **ping**                 | Tool zum Testen der Erreichbarkeit von Hosts im Netzwerk.                                                                |
| **tracert**              | Tool zur Routenverfolgung, zeigt den Pfad zu einem Host über mehrere Hops.                                               |
| **net**                  | Befehl zur Verwaltung von Netzwerkaufgaben und -informationen.                                                           |
| **net user**             | Zeigt eine Liste der Benutzer im System an.                                                                              |
| **net share**            | Zeigt eine Liste der vorhandenen Freigaben im System an.                                                                 |
| **net group**            | Zeigt eine Liste der Gruppen im System an.                                                                               |
| **net start**            | Zeigt die aktiven Systemdienste an.                                                                                      |
| **net start [DIENST]**   | Startet einen bestimmten Dienst.                                                                                         |
| **net stop [DIENST]**    | Stoppt einen bestimmten Dienst.                                                                                          |
| **net … /DOMAIN**        | Führt ein Netzwerkkommando auf dem Primary Domain Controller (PDC) durch.                                                |

