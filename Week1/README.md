# Assignment 1.1 - Breaking the web

## Summary
This assignment is about 'breaking' the web by disabling some features on the browser. 
The features that I had to disable/limit are color and bandwidth.

## 1. Color blindness
Color blindness affects around 1 in 12 men and 1 in 200 women worldwide. 
This means that for every 100 users that visit your website, 
up to 8 people could actually experience the content much differently. 
This could result the website being less usable or not usable at all for them, if not optimized.

### 1.1 Types of color blindness
Most color blind people are able to see things just as clearly as the rest of the population, the difference is their inability to distinguish red, green or blue light.

#### 1.1.1 Protanopia & Deuteranopia
The most common is red/green color blindness, where sufferers mix up all colors which have red or green as part of the whole color. Those affected by Protan color blindness are less sensitive to red light, whilst sufferers of Deuteranopia have the same problem with green.

#### 1.1.2 Tritanopia 
The third type of color deficiency, Tritanopia, is the least common and refers to sufferers who struggle to distinguish blue or yellow light.

#### 1.1.3 Monochromacy 
People with monochromatic vision can see no color at all and their world consists of different shades of grey ranging from black to white.

#### 1.1.3 What they see
The image below shows what colors look like for color blind individuals.

<img src="https://github.com/Arash217/browser-technologies-1819/blob/master/Week1/docs/color-blindness.png"/>

### 1.2 How to test
- [Toptal](https://www.toptal.com/designers/colorfilter/) is a website that simulates color blindness.
- [Colorblinding](https://chrome.google.com/webstore/detail/colorblinding/dgbgleaofjainknadoffbjkclicbbgaa) is a Google Chrome extension that simulates color blindness.

### 1.3 Examples
- [ATG tickets](https://atg.nliven.co/tickets/series/wicked/wicked-103989?startDate=03-27-2019&_ga=2.180328228.1492796431.1552309213-323361853.1552309213#mapView) is not color friendly for any type of color blindness when buying a ticket. 
- [De Beren reservation](https://www.beren.nl/welkom/reserveer-online/?new=1&res=1&i=c84a127447a251b6d038b97aa86096725c31ba3a) is not color friendly for people with monochromacy when choosing a reservation time.

### 1.4 Tips for better color accessibility
- Don’t only rely on color to convey a message
- Keep your color palette limited to 2 or 3 colors
- Use texture and patterns to show contrast
- Carefully select any contrasting colors and shades
- Avoid using bad color combinations

## 2. Low bandwidth
Smartphone users expect a website to load in under 3 seconds, and may leave a website that takes longer. 
Furthermore, when Google assesses page ranks, the websites that load faster rank higher. 
Unless your business delivers content aimed at high-bandwidth connections (video streaming for example) it is best to design a website that performs quickly on low-bandwidth connections and cuts down on external requests. 
This ensures a fast page load time on all connection types and bandwidth limits.

### 2.1 How to test
- Google Chrome: Developer tools > Network tab > Change from online/no throttling to custom preset.
- [Charles](https://www.charlesproxy.com/) is a cross-platform desktop tool for simulating bandwidth.

### 2.2 Examples
- [Simple website of a friend](http://de-klus-specialist.nl/) takes 11.87 seconds to load with the slow 3G simulation of Google Chrome.
- [Website of the barber that I visit](http://haarstudioclass.nl/) takes 13.47 seconds to load with the slow 3G simulation of Google Chrome.

### 2.3 How to reduce load times
Website of friend:
- Images are too big. Compression can be used to reduce the size. The green background image on the homepage can even be replaced with a gradient.
- CSS files can be compressed.
- JavaScript files can be compressed.

Website of the barber:
- Images are used for bullets and arrows. Those can be made with css.
- CSS files can be compressed.
- JavaScript files can be compressed.

## Source
- https://usabilla.com/blog/how-to-design-for-color-blindness/
- http://www.colourblindawareness.org/colour-blindness/types-of-colour-blindness/
- https://smallbusiness.chron.com/bandwidth-affect-website-performance-69958.html
