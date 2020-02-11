---
layout: page
chapter: 2.02
title: kleineAnfragen
website: https://kleineanfragen.de/
permalink: /open-government/kleineanfragen/
visual:
    img: /assets/images/opengovernment/kleineanfragen.png
    alt: Eine Beschreibung des Textes
problem:
- text: Anfragen und Antworten aus den Parlamenten sind nicht zugänglich.
causes:
- title: Mangelnde Transparenz,
- title: unbenutzbare Werkzeuge und
  text: Suchfunktionalitäten der Parlamentsdokumentationssysteme erfassen nicht den vollständigen Text und teilweise ist keine Verlinkung auf Anfragen in diesen Systemen möglich
- title: wenig Berichterstattung
  text: Anfragen werden von sich aus von Journalist\*innen nicht gefunden, manchmal werden sie vorab von Abgeordneten direkt an befreundete Journalist\*innen weitergegeben oder darauf hingewiesen
- title: führen dazu, dass
  claim: sich interessante und wertvolle Informationen in den Antworten finden, diese jedoch von wenigen Menschen außerhalb des Parlaments gelesen werden.


solution:
- title: neue und einfache Tools
  text: Mithilfe von einfach verständlichen Werkzeugen können alle einfacher auf die Anfragen und Antworten zugreifen.
- title: Verknüpfung mit bestehenden Tools
  text: Durch den Verweis auf Tabula und die Implementation eines offenen Standards (OParl) können die Daten in den Antworten, aber auch die Metadaten zu allen Antworten weiterverwendet werden.
- title: Best Practice
  text: Durch ein Best-Practice-Beispiel werden Verwaltungen und Politik von den Vorteilen offener Werkzeuge überzeugt.
effect:
- title: auf Verwaltung & Abgeordnete
  text: >
    Anfragen und Antworten tauchen bei normaler Suchmaschinenrecherche auf.


    Der Regierungsprozess wird transparenter und politische Beteiligung wird vereinfacht.
- title: auf interessierte Menschen
  text: >
    Die Praxis der Informationsfreiheit wird gestärkt, weil Verwaltungen online anhand von Fällen viel über Informationsfreiheit lernen können.


    NGOs, Bürgerinitativen und andere Interessens&shy;vereinigungen erfahren schneller, wenn ihre Themen im Parlament angefragt werden.
- title: auf Journalist\*innen / Medien
  text: >
    Der Einstieg in das Thema aus journalistischer Sicht wird vereinfacht


    Die parlamentarische Anfrage als journalistisches Werkzeug rückt stärker in den Fokus der Medien.
  text: Mehr Artikel und Nachforschungen werden erstellt, die sich auf Anfragen stützen.
- title: gesellschaftliche Wirkung
  claim: Regierungshandeln wird transparenter und Parlamentsarbeit wirksamer und besser nachvollziehbar, da mehr Menschen die Möglichkeit haben, sich zu informieren.
resources:
  timespan:
      img: /assets/images/opengovernment/laufzeit/kleineanfragen.svg
      alt: Das beschreibt die Projektlaufzeit in Worten
  funding:
      img: /assets/images/opengovernment/finanzierung/kleineanfragen.svg
      alt: Das beschreibt die Finanzierungssituation in Worten

resources: >
  <br>**Laufzeit** <br>

  ganzjährige Projektlaufzeit <br><br>
  ![ganzjährige Laufzeit](/assets/images/laufzeit/kleineanfragen.svg "Laufzeit kleineAnfragen")
  <br><br><br>

  **Finanzierung** <br>

  Das Projekt wird ehrenamtlich von Maximilian Richt realisiert. Es fallen ausschließlich Kosten für Server und Speicherplatz an. <br><br>

  ![0% Finanzierung, 100h ehrenamtliche Arbeit](/assets/images/finanzierung/kleineanfragen.svg "Laufzeit kleineAnfragen")<br><br>

  **Personal**
  Entwickler (ehrenamtlich): Maximilian Richt

achievements: >
    * stabile, menschenlesbare URLs für Anfragen und Antworten, sodass diese auch per Mail oder in Sozialen Medien geteilt werden können

    * Anfragen und Antworten im Volltext durchsuchbar

    * Benachrichtigung per E-Mail oder Feed bei neuen Antworten zu einer Suche

    * Metadaten der Anfragen über API und als täglicher Datenbankdump für Entwickler*innen bereitgestellt

outputs: >
    * 101.000 Anfragen und Antworten zugänglich und leicht durchsuchbar

    * 701 aktive E-Mail-Abonnements

    * Monatlich ~30.000 unique Besucher, ~147.000 Seitenaufrufe

outcome: >
    * Verwaltungsmitarbeitende der Parlamente nutzen kleineAnfragen.de öfter als ihre eigenen Tools

    * politische Parteien und Verwaltungen interessieren sich für die Plattform und wollen eigene Arbeit verbessern

impact: >
    * Regierungshandeln wird transparenter und Parlamentsarbeit besser nachvollziehbar, da mehr Menschen die Möglichkeit haben, sich zu informieren. Das ermöglicht mehr Partizipation.


evaluation:  >
    * Die ursprüngliche Zielgruppe (Journalist\*innen) hat sich mehr in Richtung interessierte Bürger\*innen und interessanterweise Verwaltungsmitarbeiter\*innen bewegt.

    * Parlamente updaten/tauschen Dokumentationssoftware, sodass Import von Anfragen und Antworten ohne Anpassung nicht mehr möglich ist – zeitliche Ressourcen hierfür nicht ausreichend, sodass längere Zeit keine neuen Dokumente mehr erscheinen

    * technischer Aufbau nicht stabil, Nichtverfügbarkeit einzelner Komponenten (Suche, Scraper, Dokumentenbereitstellung) sorgt für Ausfall der ganzen Plattform



outlook: >
    * Risiken: Parlamente updaten oder tauschen die Dokumentationssoftware, sodass der Import von Anfragen und Antworten von diesem Parlament erstmal nicht mehr funktionieren bis eine neue Anbindung geschrieben wurde.

    * Die Finanzierung des Projekts ist nicht gesichert. Daher ist eine langfristige Planung nicht möglich.


---


# Datenbank der Kleinen Anfragen und Antworten aus den Parlamenten

In den Landtagen und im Bundestag haben Abgeordnete ein parlamentarisches Fragerecht. Die Antworten darauf sind aber wenig bekannt, obwohl sie viele interessante Details enthalten. Die Dokumentenmanagementsysteme der Parlamente (hier: Parlamentsdokumentationssysteme) sind nicht nutzer\*innenfreundlich, sodass selbst Verwaltungsmitarbeitende diese ungern benutzen. Bei manchen Parlamenten lassen sich Dokumente nicht verlinken, ein Teilen in Sozialen Netzwerken ist also nicht möglich. Man muss jedes Parlamentssystem einzeln durchsuchen; eine Suche über alle Parlamente funktioniert nur auf Stichwortbasis.

Durch den besseren Zugang zu den Anfragen und Antworten mit Volltextsuche aus allen Parlamenten auf einer Seite sowie eine Benachrichtungsfunktion bei neuen Anfragen oder Antworten, die auf einen Suchbegriff zutreffen, nutzen Verwaltungsmitarbeitende der Parlamente kleineAnfragen.de öfter als ihre eigenen Tools. Journalist\*innen und interessierte Bürger\*innen finden interessante Anfragen und Antworten, Anfragen tauchen in Suchmaschinen öfter auf und Parlamentsdokumentationssysteme und Metadaten in den Dokumenten werden verbessert.

Regierungshandeln wird dadurch transparenter und Parlamentsarbeit besser nachvollziehbar, da mehr Menschen die Möglichkeit haben, sich darüber zu informieren. Das führt zu besseren Möglichkeiten für Partizipation.
