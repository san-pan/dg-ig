<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

Eine Hausarztpraxis erfasst Arzneimittelallergien ihrer Patientinnen und Patienten strukturiert und mit Codes aus der Schweizer Allergieliste. Eine Notfallstation soll diese Angaben zuverlässig auswerten können, insbesondere wie gefährlich eine Allergie ist und welche Reaktionen bekannt sind.

### Scope

Dieses IG deckt Allergien gegen Arzneimittel ab, die von einer Ärztin oder einem Arzt erfasst werden. Nicht abgedeckt sind Nahrungsmittel-, Umwelt- und biologische Allergien sowie Unverträglichkeiten, die von Patientinnen oder Angehörigen selbst gemeldet werden.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Profil auf Basis von CH Core AllergyIntolerance mit den Regeln für die Erfassung von Arzneimittelallergien.
* [Bestätigte Penicillin-Allergie von Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Beispiel einer bestätigten, hochkritischen Penicillin-Allergie mit dokumentierter Reaktion.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin

Sandra Pannarakunnel

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>