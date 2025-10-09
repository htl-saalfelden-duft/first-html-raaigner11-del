## HTML-Übung
Unser erstes Webprojekt besteht aus 2 Seiten. Die Einstiegsseite (index.html) verlinkt dabei auf vorerst eine Unterseite (uebung_html.html).

Folgende Ansicht sollte dir als Vorlage für die index.html dienen:

> # Webseite von \<Dein Name>
> Liste mit Übungen
> 1. HTML
> 2. CSS


Verwende die entsprechenden Tags.: https://www.w3schools.com/html/default.asp


Für die zweite Seite verwende folgendes Template, wieder mit den entsprechenden Tags:

> # HTML Grundlagen
> ## Was ist HTML?
> 
> HTML ist eine „Strukturierungssprache“, mit der dem Browser „gesagt“ wird, wie die Inhalte strukturiert sind: welche Bereiche (Buchstaben, Wörter, Sätze) z.B. Überschriften, was Absätze, was Aufzählungen, was Tabellen usw. sind. HTML ist keine Programmiersprache – man beschreibt, welche logische Struktur ein Inhalt hat (nicht mehr, nicht weniger). 
> In HTML also haben wir verschiedene Befehle (HTML-TAGs) für:
> - verschiedene Überschriftenebenen
> - Absätze
> - Hervorhebungen
> - verschiedene Aufzählungen
> - und weitere Befehle, um Inhalte zu strukturieren

Erweitere die uebung_html.html mit folgenden Elementen:

- Ergänze den Text noch mit Blindtext ([lorem](https://www.blindtextgenerator.de/) ipsum) so, dass er insgesamt zumindest 2 Seiten umfasst (beim Scrollen)
- Erstelle Sprungmarken am Anfang, in der Mitte und am Ende 
- Erstelle Links, die zu den Sprungmarken führen, sodass man an den Anfang, zur Mitte und ans Ende des Textes springen kann 
- Füge am Ende des Textes eine Reihe von Bildern ein (als Aufzählung ``<ul><li>...``)
  Dafür kannst du als Quelle diese hier verwenden: [https://picsum.photos/](https://picsum.photos/)) 
- Verschiebe die Sprungmarke für das Ende 
- Mach das letzte Bild „anklickbar“ und verweise auf [www.orf.at](http://www.orf.at/) 
- Füge am Ende noch einen Link zur Hauptseite hinzu (index.html)

## CSS-Übung

Diesmal erweitern wir unsere Website um eine weitere Unterseite.

Das Ergebnis sollte in etwa so aussehen:

![](./assets/Pasted%20image%2020250923095354.png)

- Dazu lege zuerst eine neue html-Datei an (uebung_css.html).
- Verlinke diese in deiner Übersichtsseite(index.html) mit dem Menüpunkt **2. CSS**, welche du in Übung 1 erstellt hast
- Erstelle die Grundstruktur der Seite (Doctype, head, body) und gib ihr den Titel „Eigene Webseite von NAME“.
- Erstelle einen ``<style>``Bereich im ``<head>``, um die einzelnen Sektionen der Webseite mit CSS zu gestalten.
- Im Header-Bereich soll der Name der aktuellen Seite stehen, in unserem Fall die HOME-Seite. Gib diesem Bereich einen Rahmen, zentriere den Inhalt und gib dem Text (Überschrift 1) eine Farbe. Die Farbwahl ist deinem Geschmack überlassen.
  Informiere dich auf folgenden Seiten für die Gestaltung: 
	- Farben generell: https://www.w3schools.com/css/css_colors.asp
	- Ränder gestalten: https://www.w3schools.com/css/css_border.asp
	- Texte gestalten: https://www.w3schools.com/css/css_text.asp o 
	- Texteffekte: https://wiki.selfhtml.org/wiki/HTML/Textstrukturierung/p#Typographie_und_CSS
- Der Main-Bereich besteht aus den Abschnitten „Bild und Text“ und dem „Motto“. Erstelle für diese beiden Abschnitte jeweils ``<div>``Elemente und gig ihnen eine passende ID.
- Schreibe die Abschnittsnamen auch als Überschrift 2 in die ``<div>``Bereiche und style sie über CSS.
- Im Main Bereich sollst du etwas über dich erzählen. Vergiss nicht, die Bereiche in Abschnitte zu gliedern (``<div>``)
	- Füge ein Bild von dir ein und vergiss nicht, die Attribute title und alt anzugeben (WARUM?) https://www.w3schools.com/html/html_images.asp 
	- Gib an, welche Interessen du hast und beschreibe dich. 
	- Gib auch einen Link zu einer Webseite an, die dich besonders interessiert und die du am öftesten öffnest. Gestalte diesen Link (:link, :hover,…) https://www.w3schools.com/html/html_links_colors.asp
- Informiere dich über das Box-Modell in CSS und besonders über die CSS Angaben „margin“ und „padding“. Gib den Außenabstand zu header und footer mit jeweils 1rem an. (Achtung: NUR oben und unten soll der Abstand sein). 
	- https://www.w3schools.com/css/css_boxmodel.asp 
		![](./assets/Pasted%20image%2020250923100506.png)
	- https://www.w3schools.com/css/css_margin.asp
- Im Bereich „Motto“ kannst du dein Lebensmotte schreiben. Dieses soll als Überschrift 4 geschrieben sein. Style den Text nach deinen Wünschen (Textgröße, Stil, Schriftart)
	- https://www.w3schools.com/css/css_font.asp 
- Der Text im Footer (siehe Abbildung) soll rechtsbündig sein und einen farbigen Hintergrund haben (Farbe kannst du selbst wählen).
	- https://www.w3schools.com/css/css_background.asp □ Gib beim Text „E-Mail“ eine Verlinkung zu deiner Email Adresse an. 
	- https://www.w3schools.com/tags/att_a_href.asp → siehe „mailto“ 
- Der Text im Footer klebt ziemlich an den Rändern. Informiere dich über die Funktion „padding“ und erhöhe den inneren Abstand zu den Rändern. Beachte hierbei auch den Unterschied zu Margin. 
	- https://www.w3schools.com/css/css_padding.asp


[def]: Pa