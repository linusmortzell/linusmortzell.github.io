---
layout: post
title:  "Reflektion av olika uppgifter i exam 1"
date:   2017-11-17 12:10:01 +01:00
categories: jekyll update
comments: true
image: https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTrPBPB4eMkT7ie1iD20a-X2xsGJMp-OpkKPc3Q87OJ0qltvS15QQ
---

* What do you think of pre-compiling your CSS?
    * Compare to regular CSS   
    Smidigt att återanvända saker. 
    Lättare att få överblick och läsa koden.

    * Which techniques did you use?   
    Jag använde mig av variabler för lite olika saker i min css-kod, dessa ligger tillsammans i en annan fil som det är lätt att överskåda samt att mycket av det är olika färger m.m. vilket gör det väldigt enkelt att ändra utséende på sidan. De flesta fanns sedan tidigare men någon if-sats har lagts till.

    * Pros and cons?   
        * Pros   
        Många webbplatser har relativt lika strukturella element. Genom att använda sig av variabler kan man enkelt ändra färger och andra effekter genom att bara ändra några värden istället för att söka runt i koden och ersätta värden på massa olika ställen.
        Man slipper skriva samma sak många gånger för att få liknande styling för separata element. Man kan definera globala stilar som man sedan kan använda där man behöver dem bara genom en liten kodrad.   

        * Cons   
        Det är ett nytt/annat språk så alla som ska jobba med projektet måste vara med på det.
        Eftersom det inte fungerar utan kompilering finns det ingen möjlighet att live-editera en webbplats för en snabb ändring.
        Man kan även råka ut för att få en CSS-fil med kaos om man inte hanterar det på rätt sätt.

* What do you think of static site generators?   
Till en början var det kaos tycker jag, filer överallt och massa kod som man inte kände igen.   
Nu efter åtskilliga timmar framför det finner jag det mer och mer smidigt, jag känner att jag har en lång bit kvar innan jag 
till fullo bemästrar det men jag ser det inte som en omöjlighet att jag skulle använda mig av det igen i något projekt.

* What type of projects are they suitable for?   
Bloggar och webbshoppar. 

* What is robots.txt and how have you configure it for your site?   
Det används för att sätta olika åtkomst för robotar. Jag har förbjudit alla robotar förutom google och facebook.

* What is humans.txt and how have you configure it for your site?  
En fil med information riktat till människor, t ex vem/vilka som har utvecklat sidan, olika kontaktinformation, vilket / vilka språk som använts, vilka program osv.

* How did you implements comments to blog posts?   
Jag följde guiden som disqus hade. Man fick en komplett kod som man kunde kopiera och lägga till på lämpligt ställe i sin kod.

* What is Open Graph and how do you make use of it?   
Det är delningsinformation om min sida. När någon delar/länkar till en sida på exempelvis facebook vill man helst att den synliga informationen ska matcha innehållet på sidan. T ex bild och text ska relatera till innehållet på sidan.
Jag la in sidans titel, lite av sidans innehåll som beskrivning. Om en bloggpost har en bild angiven så visas den m.m. 