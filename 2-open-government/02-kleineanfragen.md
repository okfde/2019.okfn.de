---
layout: page
chapter: 2.2
title: kleineAnfragen (†)
website: https://kleineanfragen.de/
permalink: /open-government/kleineanfragen/
visual:
    img: /assets/images/opengovernment/kleineanfragen.png
    alt: Illustration – Anfragedokument
problem:
- text: Anfragen und Antworten aus den Parlamenten sind nicht zugänglich.
causes:
- title: Mangelnde Transparenz,
- title: unbenutzbare Werkzeuge und
  text: Suchfunktionen der Parlamentsdokumentationssysteme erfassen nicht den vollständigen Text und teilweise ist keine Verlinkung auf Anfragen in diesen Systemen möglich.
- title: wenig Berichterstattung
  text: Anfragen werden von Journalist\*innen nicht gefunden, manchmal werden sie vorab von Abgeordneten direkt an befreundete Journalist\*innen weitergegeben oder darauf hingewiesen.
- title: führen dazu, dass
  claim: sich interessante und wertvolle Informationen in den Antworten finden, diese jedoch von wenigen Menschen außerhalb des Parlaments gelesen werden.


solution:
- title: neue und einfache Tools
  text: Mit Hilfe von einfach verständlichen Werkzeugen können alle leichter auf die Anfragen und Antworten zugreifen.
- title: Verknüpfung mit bestehenden Tools
  text: Durch den Verweis auf Tabula und die Implementation eines offenen Standards (OParl) können die Daten in den Antworten, aber auch die Metadaten zu allen Antworten weiterverwendet werden.
- title: Best Practice
  text: Durch ein Best-Practice-Beispiel sollten Verwaltungen und Politik von den Vorteilen offener Werkzeuge überzeugt werden.
effect:
- title: auf Verwaltung & Abgeordnete
  text: >
    Anfragen und Antworten tauchen bei normaler Suchmaschinenrecherche auf.


    Der Regierungsprozess wird transparenter und politische Beteiligung wird vereinfacht.
- title: auf interessierte Menschen
  text: >
    Die Praxis der Informationsfreiheit wird gestärkt, weil Verwaltungen anhand der Einzelfälle viel über Informationsfreiheit lernen können.


    NGOs, Bürgerinitativen und andere Interessens&shy;vereinigungen erfahren schneller, wenn ihre Themen im Parlament angefragt werden.
- title: auf Journalist*innen / Medien
  text: >
    Der Einstieg in das Thema aus journalistischer Sicht wird vereinfacht


    Die parlamentarische Anfrage als journalistisches Werkzeug rückt stärker in den Fokus der Medien.


    Mehr Artikel und Nachforschungen werden erstellt, die sich auf Anfragen stützen.
- title: gesellschaftliche Wirkung
  claim: Regierungshandeln wird transparenter und Parlamentsarbeit wirksamer und besser nachvollziehbar, da mehr Menschen die Möglichkeit haben, sich zu informieren.

resources: >
  <br>**Laufzeit** <br>

  ganzjährige Projektlaufzeit <br><br>

  **Finanzierung** <br>

  Das Projekt wurde ehrenamtlich von Maximilian Richt realisiert. Es fallen ausschließlich Kosten für Server und Speicherplatz an. <br><br>

  **Personal** <br>
  1 Entwickler: Maximilian Richt

total_achievements: >
    * stabile, menschenlesbare URLs für Anfragen und Antworten, sodass diese auch per Mail oder in Sozialen Medien geteilt werden können

    * Anfragen und Antworten im Volltext durchsuchbar

    * Benachrichtigung per E-Mail oder Feed bei neuen Antworten zu einer Suche

    * Metadaten der Anfragen über API und als täglicher Datenbankdump für Entwickler*innen bereitgestellt

outputs: >
    * 116.000 Anfragen und Antworten zugänglich und leicht durchsuchbar

    * 760 aktive E-Mail-Abonnements

    * monatlich ~25.000 unique Besucher\*innen, ~119.000 Seitenaufrufe

outcome: >
    * Verwaltungsmitarbeitende der Parlamente nutzten kleineAnfragen.de öfter als ihre eigenen Tools

impact: >
    * Regierungshandeln wird transparenter und Parlamentsarbeit besser nachvollziehbar, da mehr Menschen die Möglichkeit haben, sich zu informieren. Das ermöglicht mehr Partizipation.

evaluation:  >
    * Die ursprüngliche Zielgruppe (Journalist\*innen) hat sich mehr hin zu interessierten Bürger\*innen und interessanterweise Verwaltungsmitarbeiter\*innen bewegt.

    * Parlamente updaten oder tauschen oft die Dokumentations&shy;software, sodass der Import von Anfragen und Antworten von diesem Parlament ohne Anpassung nicht mehr funktionierte bis eine neue Anbindung geschrieben wurde. Die zeitlichen Ressourcen waren hierfür nicht ausreichend, sodass längere Zeit keine neuen Dokumente mehr erscheinen.

    * Der technische Aufbau ist nicht stabil; die Nichtverfügbarkeit einzelner Komponenten (Suche, Scraper, Dokumentenbereitstellung) sorgte für den Ausfall der ganzen Plattform.

    * Die Parlamente nahmen kleineAnfragen nicht zum Anlass, den eigenen Parlamentsspiegel zu überarbeiten und selbst offene Daten bereitzustellen.


outlook: >
    * kleineAnfragen wird darum zum 31.12.2020 abgeschaltet. Etwa auftretende Fehler beim Import von Anfragen und Antworten werden nicht mehr korrigiert. Es werden auch keine E-Mail-Benachrichtigungen mehr verschickt und ab diesem Zeitpunkt wird auch keine Volltextsuche mehr möglich sein.


---


# Datenbank der Kleinen Anfragen und Antworten aus den Parlamenten

Das Fragerecht ist ein wichtiges Recht der Abgeordneten – und ein häufig genutztes parlamentarisches Kontrollinstrument. Allein im Bundestag werden pro Wahlperiode tausende **Kleine Anfragen** gestellt, die von der Regierung schriftlich beantwortet werden müssen. Nimmt man die Anfragen in den Länderparlamenten hinzu, ist dies ein riesiger Fundus nützlicher Informationen, der wichtige Einblicke in demokratische Prozesse enthält. 

Von Seiten der Parlamente werden diese Dokumente zwar veröffentlicht, dies geschieht aber auf verschiedenen Onlinearchiven verstreut und mit mangelhafter Qualität. Unter anderem sind die Dokumente nicht im Volltext durchsuchbar, wodurch sie anhand der großen Menge von Anfragen in großen Teilen faktisch unzugänglich sind. 

Um die in den Dokumenten enthaltenen Informationen zugänglich zu machen, wurden sie auf kleineAnfragen.de fünf Jahre lang ehrenamtlich in einer Datenbank gesammelt, aufbereitet und – als Beitrag zu Transparenz und Partizipation – kostenfrei für die Öffentlichkeit zugänglich gemacht. Dadurch sollte demonstriert werden, **welche Chancen eine sinnvolle Digitalisierung Kleiner Anfragen** bietet, um die [Parlamente dazu zu bewegen](https://kleineanfragen.de/info), die gegenwärtig mangelhafte Bereitstellung zu überdenken und sich aktuellen technischen Standards anzupassen.

Dabei wurden auf technischer Ebene die folgenden Features implementiert: 

* eine Volltextsuche (nicht nur von redaktionell vergebenen Stichwörtern)

* Saubere, stabile und verlinkbare Links zu den Dokumenten (URLs)

* maschinenlesbare [Metadaten](https://de.wikipedia.org/wiki/Metadaten)

* E-Mail-Abonnement für neue Antworten

* Erkennung von Tabellen und eingestuften Dokumenten

* Feeds, um selbst auf den neuesten Stand bleiben zu können und z. B. daraus automatisiert Twitter-Bots zu betreiben

## kleineAnfragen stillgelegt

Die Plattform erfreute sich großer Beliebtheit, insbesondere bei Abgeordneten und bei den Mitarbeiter*innen in den Parlamentsverwaltungen selbst (zu erkennen durch die IP-Adressen). Was jedoch nicht geschah, war eine bessere Bereitstellung der Dokumente durch die Parlamente. Im Gegenteil haben Umstellungen der einzelnen Parlamente dazu geführt, dass für jedes einzelne der 17 Parlamente immer wieder umfangreiche Änderungen an der Software von kleineAnfragen notwendig waren, um die veröffentlichten Anfragen importieren zu können. Würden die Parlamente ihre Dokumentensammlung auch maschinenlesbar als **[offene Daten](https://okfn.de/themen/open_data/)** veröffentlichen, wäre dies nicht notwendig.

Es muss eine moderne, stabile und offene Möglichkeit geschaffen werden, Anfragen und Antworten, aber auch alle anderen parlamentarische Dokumente besser für Menschen zugänglich und maschinenlesbar zu machen. kleineAnfragen.de konnte diese Bereitstellung als ehrenamtliches Projekt nur exemplarisch leisten. **Nun ist es wieder die Aufgabe der Parlamente und insbesondere die des [Parlamentsspiegels](https://www.parlamentsspiegel.de/), der die Dokumente aller Parlamente aggregieren soll, die Situation zu verbessern.**
