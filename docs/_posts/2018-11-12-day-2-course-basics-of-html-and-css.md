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

{% highlight html %}
<ion-title>Arbeiten mit CSS</ion-title>
{% endhighlight %}

## Farbe des Titels: home.page.scss

{% highlight css %}
ion-title {
	color: #3880ff;
}
{% endhighlight %}

## Farbe des Hintergrund

{% highlight css %}
ion-title {
	color: #ffffff;
	background-color: #ff0000;
}
{% endhighlight %}

## Weiterer Text und Formatierung

### home.page.html

{% highlight html %}
<ion-content padding>
	<h1>Überschrift H1</h1>
	<h2>Überschrift H2</h2>
</ion-content>
{% endhighlight %}

### home.page.scss

{% highlight css %}
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

## Weitere Beispiele: home.page.html

{% highlight html %}
<ion-content padding>
  <h1>Überschrift 1</h1>
  <h2>Überschrift 2</h2>
  <h1>Überschrift 3</h1>
  <h4>Überschrift 4</h4>

  Normaler Text
  Die Welt ist <b>rund</b> und gross.
</ion-content>
{% endhighlight %}


{% highlight css %}
ion-title {
    color: #ffffff;
    background-color: #00ff00;
}

h1 {
    color: greenyellow;
}

h1 {
    color: red;
}

h3 {
    background-color: aqua;
    font-family: 'Courier New', Courier, monospace;
}
{% endhighlight %}
