---
sidebar: auto
---

# Komponenten

Was sind eigentlich Komponenten? Komponenten sind wiederverwertbare Software Bausteine. Und das bedeutet, dass man diese Bausteine im Quellcode ähnlich einfach verschieben kann, wie HTML Blöcke in einer Webseite. Anders als ein HTML Block beinhaltet eine Komponente auch Funktionalität. 

Beispielsweise gibt es eine [Komponente](https://www.npmjs.com/package/vue-google-autocomplete), welches ein Text-Eingabefeld um die Funktionalität erweitert, die eingegebenen Zeichen an die Google Places API sendet, um dann eine Autocomplete Box dem Eingabefeld hinzuzufügen. Eine solche Komponente beinhaltet Logik in Form von Javascript. Aber auch etas Layout, um die Autocomplete Box in den Vordergund zu bringen.

Kurz: in Komponenten ist die Trennung von Logik, Daten und Logik aufgehoben.

Aus Sicht eines Smart Composers, der es ermöglichen soll etwa einen gewüschten Ort für den nächsten Job zu finden, sollte eine solche Komponente eine Vorauswahl des Landes ermöglichen. Und eventuell sollten bei der Auswahl eines Landes auch Flaggen angezeigt werden.

Im Proof of Concept gibt es eine solche Komponente, welche bei einer Suche nach einem Job oder bei der Eingabe des Wunsches zur nächsten Tätigkeit genutzt werden kann.

## Formularfelder

Komponenten können um Funktionalität, Layout und  Daten erweitert werden. Um auszuloten wie weit man bei einer Komponente in Sachen Konfigurierbarkeit gehen kann, gibt es eine Komponente für die Eingabe eines Kontakts. 

### Dienstsitz

für eine möglichst schnell passende Autovervollständigung bei der Suche nach einem
Ort ist eine Einschränkung im Vorfeld sinnvoll. 

### Gehalt

ein Gehalt benötigt 3 Werte. Einen Betrag, die Währung und einen Zeitraum. 

### Sprachkenntnisse

Der [Europass](https://europass.cedefop.europa.eu/de) kennt die Sprachlevel A1, A2, B1, B2, C1 und C2.

## Authentifikation

## Sonstiges

### Download per PDF

