---
layout: post
comments: true
title: "Day 2: Basics of HTML and CSS"
date: 2018-11-12 23:01:44
image: '/assets/img/'
description: Heute lernen wir HTML und CSS anzuwenden. Am Ende gibts es auch noch ein paar Übungen und Fragen
main-class: 'html'
color: green
tags:
- html
- css
categories:
twitter_text:
introduction:
---

# Erste Schritte: Seite individuell anpassen

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

{% highlight html %}
<ion-content padding>
	<h1>Überschrift H1</h1>
	<h2>Überschrift H2</h2>
</ion-content>
{% endhighlight %}

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

# Grundlagen CSS

##  Einbinden von CSS
Es gibt verschiednen Arten, CSS-Definitionen in eine Webseite oder eine ganzen Web-App einzubinden.

### Inline CSS
Hier wird die CSS-Definition direkt im HTML-Code eingefügt. Eine einfache Möglichheit mit dem Nachteil, das sie nu an dieser Stelle und für das verwendete Element gültig ist.

{% highlight html %}
<h1 style="color: blue"> Hello world! </h1>
{% endhighlight %}

### Internal CSS

{% highlight html %}
<head>
    <style>
        h1 {
            color: blue;
        }
    </style>
</head>
{% endhighlight %}

### External CSS

{% highlight html %}
<head>
    <link rel="stylesheet" href="style.css">
</head>
{% endhighlight %}

## CSS Selectors

### Element
The first way to select an HTML element is by simply using the name, which is what we did above.

{% highlight css %}
h1 {
    font-size: 20px;
}
p {
    color: green;
}
div {
    margin: 10px;
}
{% endhighlight %}

###  Class
Another way of selecting HTML elements is by using the class attribute. In HTML, we can assign different classes to our elements. Each element can have multiple classes, and each class can also be applied to multiple elements as well.

{% highlight html %}
<div class='container'>
    <h1> This is heading </h1>
</div>
{% endhighlight %}

{% highlight css %}
.container {
    margin: 10px;
}
{% endhighlight %}

## ID
Like classes, we can also use IDs to select HTML elements and apply styling to them. The only difference between class and ID is that one ID can be assigned to only one HTML element.

{% highlight html %}
<div>
    <p id='para1'> This is a paragraph </p>
</div>
{% endhighlight %}

{% highlight css %}

#para1 {
    color: green;
    font-size: 16px;
}
{% endhighlight %}

## Fonts & Colors
CSS provides us with literally hundreds of options for playing around with fonts and colors and making our HTML elements look pretty. We can choose from two types of font family names:

1. Generic Family: a group of font families with a similar look (like ‘Serif’ or ‘Monospace’)

2. Font Family: a specific font family (like ‘Times New Roman’ or ‘Arial’)

For colors, we can use predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.

{% highlight html %}
<div class='container'>
    <h1 class='heading1'>
        CSS is Coooooool!!!!
    </h1>
</div>
{% endhighlight %}

{% highlight css %}
.container {
    width: 500px;
    height: 100px;
    background-color: lightcyan;
    text-align: center;
}
.heading1 {
    font-family: 'Courier New';
    color: tomato;
}
{% endhighlight %}

# Beispiel für Formatierungen

{% highlight html %}
<table style="width: 600px">
	<colgroup>
		<col width="50%" />
		<col width="50%" />
	</colgroup>
	<thead>
		<tr class="header">
			<th align="left">HTML/CSS</th>
			<th align="left">Ergebnis</th>
		</tr>
	</thead>
	<tbody>
	<tr><td>#</td><td>#</td></tr>
	</tbody>
</table>

{% endhighlight %}
