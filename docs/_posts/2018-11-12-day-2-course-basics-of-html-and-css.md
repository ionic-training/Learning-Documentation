---
layout: post
comments: true
title: "Day 2: Basics of HTML and CSS"
date: 2018-11-12 23:01:44
image: '/assets/img/'
description: Heute lernen wir HTML und CSS anzuwenden. Am Ende gibts es auch noch ein paar Übungen und Fragen
main-class: 'html'
color:
tags:
- html
- css
categories:
twitter_text:
introduction:
---

# Seite individuell anpassen

## Titel ändern

{% highlight shell %}
<<<<<<< HEAD
	<ion-title>CSS 01</ion-title>
	<ion-buttons slot="start">
		<ion-menu-button></ion-menu-button>
	</ion-buttons>
{% endhighlight %}

## Farbe des Titels: home.page.scss

{% highlight shell %}
ion-title {
	color: #3880ff;
}
{% endhighlight %}

## Farbe des Hintergrund

{% highlight shell %}
ion-title {
	color: #ffffff;
	background-color: #ff0000;
=======
<ion-title>CSS 01</ion-title>
<ion-buttons slot="start">
	<ion-menu-button></ion-menu-button>
</ion-buttons>
{% endhighlight %}

## Change title color: add in file css01.page.scss

{% highlight shell %}
ion-title {
    --color: #3880ff;
}
{% endhighlight %}

 ## Add background color
 
{% highlight shell %}
ion-title {
    color: #ffffff;
    background-color: #ff0000;
>>>>>>> b25b08b30ea8d888b560ae0c90bad092c89db021
}
{% endhighlight %}

##Weiterer Text und Formatierung

### home.page.html

{% highlight shell %}
<ion-content padding>
	<h1>Überschrift H1</h1>
	<h2>Überschrift H2</h2>
</ion-content>
{% endhighlight %}

### home.page.scss

{% highlight shell %}
h1 {
	color: #ff0000;
	background-color: #000000;
	font-family: 'Courier New', Courier, monospace;
}

h2 {
	color: #000000;
	background-color: #ff0000;
	font-style: italic;
}
{% endhighlight %}
<<<<<<< HEAD

## Weitere Beispiele: home.page.html

{% highlight shell %}
<ion-content padding>
  <h1>Überschrift 1</h1>
  <h2>Überschrift 2</h2>
  <h1>Überschrift 3</h1>
  <h4>Überschrift 4</h4>

  Normaler Text
  Die Welt ist <b>rund</b> und gross.
</ion-content>
{% endhighlight %}


{% highlight shell %}
ion-title {
    color: #ffffff;
    background-color: #00ff00;
}

h1 {
    color: greenyellow;
}

h1 {
    color: red
}

h3 {
    background-color: aqua;
    font-family: 'Courier New', Courier, monospace;
}
{% endhighlight %}
=======
>>>>>>> b25b08b30ea8d888b560ae0c90bad092c89db021
