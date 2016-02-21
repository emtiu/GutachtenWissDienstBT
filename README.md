# Gutachtenliste: Wissenschaftlicher Dienst des Bundestags 2005–2015
Maschinenlesbare Liste der Gutachten des Wissenschaftlichen Dienstes des Bundestags von 2005 bis 2015
## Neu ab Februar 2016!
Der Bundestag hat nach den zahlreichen Anfragen, die aus dieser Datenbank hervorgegangen sind, mit der Veröffentlichung von Ausarbeitungen [auf einer eigenen Webseite](https://www.bundestag.de/ausarbeitungen) begonnen.

Ob die Ausarbeitungen vollständig oder nur teilweise, und welchem Schema folgend, dort veröffentlicht werden, ist momentan unklar. Informationen darüber, welche Ausarbeitungen dort veröffentlicht werden oder nicht, sind willkommen.
## Quelle
Nach einer erfolgreich durchgefochtenen IFG-Anfrage und hat Abgeordnetenwatch eine „Übersicht vorhandener Ausarbeitungen der Wissenschaftlichen Dienste des Deutschen Bundestages“ aus dem „Zeitraum 18.10.2005 bis 25.06.2015“ [erhalten und veröffentlicht](https://www.abgeordnetenwatch.de/blog/2016-01-22/wir-veroffentlichen-die-liste-mit-allen-gutachten-des-wissenschaftlichen-dienstes). Geliefert wurden zwei Listen in Papierform:
- Anlage 1 mit 208 Seiten: 3352 Gutachten von 18.10.2005 bis 22.10.2013
- Anlage 2 mit 34 Seiten: 503 Gutachten vom 23.10.2013 bis 25.06.2015

Die eingescannten Totholz-Informationen wurden innerhalb weniger Stunden von fleißigen Datenäffchen eingelesen und in Handarbeit durchgekämmt. Großer Dank gebührt [Stefan Wehrmeyer](https://twitter.com/stefanwehrmeyer) für technische Unterstützung. Trotzdem sind wahrscheinlich noch OCR-Fehler in den Daten versteckt. Pull Requests und Hinweise sind willkommen!
## Format
### ID
Die ID ist das Schlüsselfeld für diesen Datensatz. Sie wird indirekt aus dem Aktenzeichen eines Gutachtens gebildet, hat aber keine offizielle Bedeutung. Der Aufbau, am Beispiel des Gutachtens mit der ID&nbsp;08-2008-063, ist wie folgt:

Abteilung*|Jahr|laufende Nummer pro Abteilung und Jahr (aus Aktenzeichen)
---:|---:|---
08|2008|063

\* Für eine Auflistung der Abteilungen siehe unten

### Aktenzeichen
Die Aktenzeichen setzen sich zusammen aus der (historischen, siehe Tabelle) Bezeichnung der verantwortlichen Abteilung des Wissenschaftlichen Dienstes, einer laufenden Nummer für jedes Jahr und jede Abteilung und einer zweistelligen Jahresangabe. Am Beispiel des Eintrags mit der ID&nbsp;08-2008-063 lautet das Aktenzeichen **WD&nbsp;8&nbsp;-&nbsp;063/08**:

WD 8|063|08|
---|:---:|---
Abteilung 8|Gutachten 63| im Jahr 2008

**Achtung:** Die Gutachten können auch mit „langen Aktenzeichen“ bezeichnet werden, die eine zusätzliche Referenz aus dem Aktenplan des Bundestages enthalten. So wird beispielsweise aus dem „kurzen Aktenzeichen“ **WD&nbsp;3&nbsp;-&nbsp;124/11** das „lange Aktenzeichen“ **WD&nbsp;3&nbsp;-&nbsp;3000&nbsp;-&nbsp;124/11**.

Offenbar ist der Zusatz für „Infobriefe“ (siehe unten) nicht 3000, sondern 3010, denn es ist ein Bezug auf **WD&nbsp;2&nbsp;-&nbsp;118/08** als **WD&nbsp;2&nbsp;-&nbsp;3010&nbsp;-&nbsp;118/08** bekannt. Die genauen Verhältnisse um die „langen Aktenzeichen“ sind noch nicht bekannt. Lange Aktenzeichen werden in diesem Datensatz nicht verwendet.

### Abteilung

Die Bezeichnungen der Abteilungen in den Aktenzeichen richten sich nach der historischen Struktur des Wissenschaftlichen Dienstes ([Quelle: Wikipedia](https://de.wikipedia.org/wiki/Wissenschaftliche_Dienste_des_Deutschen_Bundestages#Gliederung) und [Bundestags-Dokument](StrukturBTVerw.pdf)):

<table><thead>
<tr>
<th align="right">ID</th>
<th>bis 2005</th>
<th>2006 –2013</th>
<th>seit 2013</th>
<th>Sachgebiet</th>
</tr>
</thead><tbody>
<tr>
<td>01</td>
<td align="center" colspan="3">WD&nbsp;1</td>
<td>Geschichte, Zeitgeschichte und Politik</td>
</tr>
<tr>
<td>02</td>
<td>WF&nbsp;II</td>
<td align="center" colspan="2">WD&nbsp;2</td>
<td>Auswärtiges, Völkerrecht, wirtschaftliche Zusammenarbeit und Entwicklung, Verteidigung, Menschenrechte und Humanitäre Hilfe</td>
</tr>
<tr>
<td>03</td>
<td>WF&nbsp;III</td>
<td align="center" colspan="2">WD&nbsp;3</td>
<td>Verfassung und Verwaltung</td>
</tr>
<tr>
<td>04</td>
<td>WF&nbsp;IV</td>
<td align="center" colspan="2">WD&nbsp;4</td>
<td>Haushalt und Finanzen</td>
</tr>
<tr>
<td>05</td>
<td>WF&nbsp;V</td>
<td align="center" colspan="2">WD&nbsp;5</td>
<td>Wirtschaft und Technologie, Ernährung, Landwirtschaft und Verbraucherschutz, Tourismus</td>
</tr>
<tr>
<td>06</td>
<td>WF&nbsp;VI</td>
<td align="center" colspan="2">WD&nbsp;6</td>
<td>Arbeit und Soziales</td>
</tr>
<tr>
<td>07</td>
<td>WF&nbsp;VII</td>
<td align="center" colspan="2">WD&nbsp;7</td>
<td>Zivil-, Straf- und Verfahrensrecht, Umweltschutzrecht, Verkehr, Bau und Stadtentwicklung</td>
</tr>
<tr>
<td>08</td>
<td>WF&nbsp;VIII</td>
<td align="center" colspan="2">WD&nbsp;8</td>
<td>Umwelt, Naturschutz, Reaktorsicherheit, Bildung und Forschung</td>
</tr>
<tr>
<td>09</td>
<td>WF&nbsp;IX</td>
<td align="center" colspan="2">WD&nbsp;9</td>
<td>Gesundheit, Familie, Senioren, Frauen und Jugend</td>
</tr>
<tr>
<td>10</td>
<td>WF&nbsp;X</td>
<td align="center" colspan="2">WD&nbsp;10</td>
<td>Kultur, Medien und Sport</td>
</tr>
<tr>
<td>11</td>
<td>WF&nbsp;XII</td>
<td>WD&nbsp;11</td>
<td>PE&nbsp;6</td>
<td>Europa</td>
</tr>
</tbody></table>

### Status

Die meisten Gutachten tragen das Zeichen **A**, für **Analyse**. Neben „Analysen“ gibt es auch „Fachinformationen“ und „gutachterliche Stellungnahmen“. Ob diese hier ebenfalls enthalten sind, oder ob es sich um separate Dokumente handelt, ist aktuell noch unklar.

Ein kleiner Teil ist mit **AI** ausgezeichnet und wurde als **Infobrief** veröffentlicht. Diese waren schon vor dem Februar 2016 (vollständig?) [online auffindbar](https://www.bundestag.de/analysen).

Ein einziges Gutachten (PE6-112/14: „Lösung von einem Investor-Staat-Streitbeilegungsmechanismus im Rahmen des Abkommens über eine Transatlantische Handels- und Investitionspartnerschaft (Transatlantic Trade and Investment Partnership TTIP)“) wurde von mir nachträglich mit dem Status **AG** gekennzeichnet, da bekannt ist, dass es als „NfD“ („Nur für den Dienstgebrauch“) **geheimgehalten** wird.

## Änderungen
Folgende Änderungen wurden am Inhalt gegenüber der ursprünglich vom Bundestag gelieferten und eingescannten Liste vorgenommen:
### Metadaten
- Status des Gutachtens PE6-112/14 zu „AG“ geändert (siehe oben)

### Titel
- Diverse offensichtliche Tippfehler, fehlende Klammern oder Anführungszeichen behoben
- Referenzen auf andere Gutachten in Form von „langen Aktenzeichen“ zu „kurzen Aktenzeichen“ korrigiert (siehe oben)
