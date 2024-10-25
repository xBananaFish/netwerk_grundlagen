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

# Aufgaben

### Erstellen einer Wertetabelle

- A und B oder C
- A oder B xor C
- (A und B) oder (C und D)
- nicht A und nicht B
- nicht A und nicht (A oder B)

|a	  |     b	|c	|d	|a∧b∨ca∧b∨c | 	a∨(b⊕c)a∨(b⊕c)  |	(a∧b)∨(c∧d)(a∧b)∨(c∧d)	 |  ¬a∧¬b¬a∧¬b  |	¬a∧¬(a∨b)¬a∧¬(a∨b)|
|:----|:--------|:-|:----|:----------|:---------------------|:--------------------------|:-------------------|:--------------|
|0	  |     0	|0	|0	|0	         | 0	                |  0	                     |  1	            |1|
|0	  |     0	|0	|1	|0	         | 0	                |  0	                     |  1	            |1|
|0	  |     0	|1	|0	|1	         | 1	                |  0	                     |  1	            |1|
|0	  |     0	|1	|1	|1	         | 1	                |  0	                     |  1	            |1|
|0	  |     1	|0	|0	|0	         | 1	                |  0	                     |  1	            |1|
|0	  |     1	|0	|1	|0	         | 1	                |  0	                     |  1	            |1|
|0	  |     1	|1	|0	|1	         | 1	                |  0	                     |  1	            |1|
|0	  |     1	|1	|1	|1	         | 1	                |  0	                     |  1	            |1|
|1	  |     0	|0	|0	|1	         | 1	                |  0	                     |  0	            |0|
|1	  |     0	|0	|1	|1	         | 1	                |  0	                     |  0	            |0|
|1	  |     0	|1	|0	|1	         | 1	                |  0	                     |  0	            |0|
|1	  |     0	|1	|1	|1	         | 1	                |  0	                     |  0	            |0|
|1	  |     1	|0	|0	|1	         | 1	                |  1	                     |  0	            |0|
|1	  |     1	|0	|1	|1	         | 1	                |  1	                     |  0	            |0|
|1	  |     1	|1	|0	|1	         | 1	                |  1	                     |  0	            |0|
|1	  |     1	|1	|1	|1	         | 1	                |  1	                     |  0	            |0|

---

##### Verwendet speedtest.net um die aktuelle Geschwindigkeit des Internetzugangs zu ermitteln.

- 925.88 Mbps

---

##### Berechne anhand des ergebnisses von speedtest.net und einer Zahl von 180 Arbeitsplätzen, wieviel Bandbreite jeder Teilnehmer zur Verfügung hat

    Anzahl der Arbeitsplätze, die die Adobe Cloud nutzen: 40
    Synchronisation pro Arbeitsplatz: 10 GiBit

Zuerst müssen wir die 10 GiBit in Megabit umrechnen, da die Internetgeschwindigkeit in Megabit angegeben ist.

1 GiBit = 1024 Megabit, also:
10 GiBit=10×1024 Megabit=10240 Megabit
10 GiBit=10×1024 Megabit=10240 Megabit

Gesamtbandbreite für 40 Arbeitsplätze:
Gesamtbandbreite fu¨r Adobe Cloud Arbeitspla¨tze=40×10240 Megabit=409600 Megabit
Gesamtbandbreite fu¨r Adobe Cloud Arbeitspla¨tze=40×10240 Megabit=409600 Megabit

---

##### 40 der 180 Arbeitsplätz nutzen die Adobe Cloud unstarten um 8:30 mit der Synchr. Die 40 Arbeitsplätze synchronisieren jeweils 10 GiBit. Berechne, wieviel Bandbreite die restlichen Arbeitsplätze zur Verfügung haben.

Restliche Arbeitsplätze:
Anzahl der restlichen Arbeitspla¨tze=180−40=140
Anzahl der restlichen Arbeitspla¨tze=180−40=140

Verfügbare Bandbreite für die restlichen Arbeitsplätze:
Verfu¨gbare Bandbreite=Gesamte Internetgeschwindigkeit−Gesamtbandbreite fu¨r Adobe Cloud Arbeitspla¨tze
Verfu¨gbare Bandbreite=Gesamte Internetgeschwindigkeit−Gesamtbandbreite fu¨r Adobe Cloud Arbeitspla¨tze
Verfu¨gbare Bandbreite=925.88 Mbps−409600 Mbps
Verfu¨gbare Bandbreite=925.88 Mbps−409600 Mbps

Da die Bandbreite für die Adobe Cloud Arbeitsplätze (409600 Mbps) die gesamte Bandbreite (925.88 Mbps) übersteigt, ist die restliche Bandbreite in diesem Fall negativ. Das bedeutet, dass die Adobe Cloud Arbeitsplätze die gesamte verfügbare Bandbreite überlasten, was zu einer unzureichenden Internetverbindung für die anderen 140 Arbeitsplätze führt.

Um zu sehen, wie viel Bandbreite pro Arbeitsplatz für die restlichen 140 Arbeitsplätze zur Verfügung steht, müssen wir die Rechnung anpassen. Da die Adobe Cloud Arbeitsplätze mehr Bandbreite benötigen, als die gesamte verfügbare Bandbreite bietet, haben die restlichen Arbeitsplätze keine Bandbreite.

Bandbreite pro Arbeitsplatz (vor Nutzung der Adobe Cloud):
Bandbreite pro Arbeitsplatz≈5.15 Mbps
Bandbreite pro Arbeitsplatz≈5.15 Mbps

Verfügbare Bandbreite für die restlichen 140 Arbeitsplätze:
Verfu¨gbare Bandbreite=0 Mbps (da die Adobe Cloud Arbeitspla¨tze die gesamte Bandbreite beanspruchen)
Verfu¨gbare Bandbreite=0 Mbps (da die Adobe Cloud Arbeitspla¨tze die gesamte Bandbreite beanspruchen








