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

| Software  | Check  | Installation |
| --|----- | ---- |
| Node JS | `node --version`  | [Download](https://nodejs.org/download/release/latest-v8.x/) |
| Ionic | `ionic --version`  | [unter Unix](http://blog.via-internet.de/blog/2018/11/09/ionic-4-installation-on-unix/) |
| Visual Studio Code | `code`  | [Homepage](https://code.visualstudio.com/) |
| Git Versionskontrolle | `git`  | [Windows](https://git-scm.com/download/win) [Linux](https://git-scm.com/download/linux) [Mac OS](https://git-scm.com/download/mac) |
    
### Beispielanwendungen funktionieren

| Anwendung | Check |
| ----------| ----- |
| sidemenu  | Ja/Nein|
| tabs      | Ja/Nein|
| blank     | Ja/Nein|

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

| Seite  |Verzeichnis |
| --|-- |
| list | `____________________________________________________` |
| home | `____________________________________________________` |
 
### In welchem Verzeichnis liegt die Startdatei eurer Anwendung `index.html`

| Seite  |Verzeichnis |
| --|-- |
| index.html | ____________________________________________________ |

### In welchen Dateien werden die folgenden Inhalt eurer Anwendung gespeichert?

| Inhalt  |Verzeichnis |
| --|-- |
| Aufbau der Seite|-- |
| Überschriften|-- |
| Bilder|-- |
| Texte|-- |
| Aussehen, Farben | ____________________________________________________ |


### In welchen Dateien wird der Programmcode eurer Anwendung definiert?

| Frage  |Antwort |
| --|-- |
| Programmiersprache | ____________________________________________________ |
| Dateierweiterung | ____________________________________________________ |

### Welche Bedeutung haben die folgenden Dateierweiterungen?

| Dateierweiterung | Bedeutung  |
| ---------------- |:---------- |
| .html          | ____________________________________________________ |
| .css           | ____________________________________________________ |
| .scss          | ____________________________________________________ |
| .js            | ____________________________________________________ |
| .ts            | ____________________________________________________ |
| .spec.ts       | ____________________________________________________ |
| .json          | ____________________________________________________ |
| .spec.json     | ____________________________________________________ |
