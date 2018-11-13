---
layout: post
comments: true
title: "Day 1: Introduction"
date: 2018-11-12 23:01:44
image: '/assets/img/'
description:
main-class: 'info'
color:
tags:
categories:
twitter_text:
introduction:
---

## Checkliste

### Software ist installiert
<table style="width: 100%">
	<tbody>
		<tr>
			<th align="left">Software</th>
			<th align="left">Check</th>
			<th align="left">Installation</th>
	</tr>
	<tr><td>Node JS/td>				</td><td>`node --version`	</td><td><a href="https://nodejs.org/download/release/latest-v8.x/">Download</a>						</td></tr>
	<tr><td>Ionic/td>				</td><td>`ionic --version`	</td><td>[unter Unix](http://blog.via-internet.de/blog/2018/11/09/ionic-4-installation-on-unix/)		</td></tr>
	<tr><td>Visual Studio Code		</td><td>`code`				</td><td>[Homepage](https://code.visualstudio.com/)														</td></tr>
	<tr><td>Git Versionskontrolle	</td><td>`git`				</td><td>[Windows](https://git-scm.com/download/win) [Linux](https://git-scm.com/download/linux) [Mac OS](https://git-scm.com/download/mac)</td></tr>

	</tbody>
</table>

### Beispielanwendungen funktionieren

<table style="width: 100%">
	<tbody>
		<tr>
			<th align="left">App</th>
			<th align="left">Check</th>
	</tr>
	<tr><td>sidemenu</td><td>Ja / Nein</td></tr>
	<tr><td>tabs</td><td>Ja / Nein</td></tr>
	<tr><td>blank</td><td>Ja / Nein</td></tr>
	</tbody>
</table>

### Screendump an Kursleiter gesendet

1. Starte bitte die Kommandoeingabe und eine Anwendung
2. öffne den Programmcode in Visual Studio Code und
3. erstelle einen Screendump auf dem man alle 3 Fenster sehen kann: 
   - VS Code, 
   - Anwendung/Internet Explorer
   - Kommandozeile

## Übungen

### Erstelle eine neue App, basierend auf der Vorlagen `sidemenu`

### Starte die neu erstellte App

### Erstelle eine neue App, basierend auf der Vorlagen `tabs`

### Starte die neu erstellte App

### Installieren eine Demo-App
    
   Öffne die Enrichment-Kommandozeile
   
{% highlight shell %}
mkdir 02_beispiele
cd    02_beispiele

git clone https://github.com/ionic-team/ionic-preview-app.git
cd ionic-preview-app

npm install
ionic serve
{% endhighlight %}   

## Fragen

### In welchem Verzeichnis liegen die Dateien für die beiden Seiten `home` und `list`

<table style="width: 100%">
	<tbody>
		<tr>
			<th align="left">Seite</th>
			<th align="left">Verzeichnis</th>
	</tr>
	<tr><td>list</td><td>____________________________________________________</td></tr>
	<tr><td>home</td><td>____________________________________________________</td></tr>
	</tbody>
</table>

 
### In welchem Verzeichnis liegt die Startdatei eurer Anwendung `index.html`

<table style="width: 100%">
	<tbody>
		<tr>
			<th align="left">Datei</th>
			<th align="left">Verzeichnis</th>
	</tr>
	<tr><td>index.html</td><td>____________________________________________________</td></tr>
	</tbody>
</table>

### In welchen Dateien werden die folgenden Inhalt eurer Anwendung gespeichert?

<table style="width: 100%">
	<tbody>
		<tr>
			<th align="left">Inhalt</th>
			<th align="left">Verzeichnis</th>
	</tr>
	<tr><td>Aufbau der Seite</td><td>____________________________________________________</td></tr>
	<tr><td>Überschriften</td><td>____________________________________________________</td></tr>
	<tr><td>Bilder</td><td>____________________________________________________</td></tr>
	<tr><td>Texte</td><td>____________________________________________________</td></tr>
	<tr><td>Farben</td><td>____________________________________________________</td></tr>
	<tr><td>Schriftarten</td><td>____________________________________________________</td></tr>
	</tbody>
</table>

### In welchen Dateien wird der Programmcode eurer Anwendung definiert?

| Frage  |Antwort |
| --|-- |
| Programmiersprache | ____________________________________________________ |
| Dateierweiterung | ____________________________________________________ |

### Welche Bedeutung haben die folgenden Dateierweiterungen?

| Dateierweiterung | Bedeutung                                            |
| ---------------- | :--------------------------------------------------- |
| .html            | ____________________________________________________ |
| .css             | ____________________________________________________ |
| .scss            | ____________________________________________________ |
| .js              | ____________________________________________________ |
| .ts              | ____________________________________________________ |
| .spec.ts         | ____________________________________________________ |
| .json            | ____________________________________________________ |
| .spec.json       | ____________________________________________________ |
