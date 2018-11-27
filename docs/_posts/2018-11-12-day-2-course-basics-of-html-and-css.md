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

# Customize page

## Change title

{% highlight shell %}
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
}
{% endhighlight %}

## Add additional text with formatting and style

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
