## kriterien für bibliothekswahl

* *Aktivität*: arbeitet jemand aktiv oder schon länger an der bibliothek. Wie oft gibt es Releases? Existiert eine Roadmap?

* Stabilität: Beziehen sich Änderungen primär auf Features oder Bugs oder beides?
gibt es Grüche in der API zwischen den releases?

* Popularität: wie verbreitet is die Bibliothek? - wer setzt sie ein (auch kommerziell)

* Team: einzelkämpfer oder projektteam?

* Qualität: Gibt es ein "kernteam" das diverse Änderungen überwacht und Features freigibt?
Gibt es Unit Tests?
Analyse/tools?
Style Guides?


## kriterien für software
*  VISION	passt die sw zur strategie? (greenIT, Stromverbrauch, ...)
	geringer CPU verbrauch im Leerlauf, Multiprozessor-Nutzung bei Auslastung
	gibts vielleicht eine andere lösung, die auch passt (weiter gedacht)? - wie siehts in 10 jahren aus?
* SICHERHEIT	wie sieht es aus mit lizenzierung (computer/user)?
	wie sieht es aus mit authentifizierung? (O365/AD) - Account aktivieren/sperren/Eintritt/Austritt)
	wie sieht es aus mit authorisierung? (gruppen/rollenbasiert/ssh/key/autoamtismen)
  Protokollierung - Api - Job, LOG
  BCM themen (backup, rebootfähigkeit, desaster, robustness)
  monitoring, snmp
* BREITE	cross-plattformtauglich (pc/mac/mobil/iphone)?
	(Sharepoint, Teams, )?
* FINANZEN	wie sieht es aus mit anschaffungs (CAPEX) /folgekosten/wartungskosten? (OPEX)
	welche schulungsmassnahmen sind erforderlich? (CAPEX)
	wartungspläne für die nächsten jahre (updates, upgrades) (OPEX)
	ausgabenrechnung auf 10 jahre?
* API	welche schnittstellen liefert die software mit?
	automatisierung/tools
	wie läuft die integration in andere systeme? (prozesse,projekte) JDF?!
	ipv6 tauglich, Firewall-Netzwerk / Segmentierung / Internet
	reporting/statistik/bigdata?
