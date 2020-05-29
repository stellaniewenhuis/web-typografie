# Web-Typografie

Als je doof bent, of als je om een andere reden geen geluid kunt horen, dan mis je veel informatie als je een film kijkt. Knisperende voetstappen, langzaam aanzwellende muziek, nerveus getik op een deur, je hoort het natuurlijk allemaal niet. Nu bestaat er zoiets als closed caption, wat een type ondertiteling is waarbij ook dingen als omgevingsgeluiden en de muziek beschreven worden. Hierdoor krijgt een kijker die informatie wel binnen.

Alleen wordt die auditieve informatie nogal neutraal beschreven. Het geluid van huilend persoon zou bijvoorbeeld beschreven kunnen worden als snikgeluid op de achtergrond. En iemand die lacht zou geschreven kunnen worden als iemand lacht. Heel neutraal, bijna zakelijk, en bovendien allebei in precies hetzelfde neutrale lettertype. Terwijl het toch echt over twee heel verschillende emoties gaat.

Dat kan visueel sterker.

De afgelopen 3 weken heb ik dit bij twee fragmenten van Blade Runner 2049 (de baseline test in het begin van de film en het einde) mogen doen. Door middel van HTML en CSS was het aan mij de taak om de geluiden en closed capions te visualiseren zodat de user experience voor Marie zou verbeteren. 

# Wie is Marie?









# Test 1

## Het ontwerp 

Ik had voor test 1 alleen het eerste fragment uitgewerkt. Waar ik me op had gefocust, was in eerste instantie de positie van de close captions. Ik probeerde vanalles uit; boven het scherm tekst en onder het scherm tekst, of links onder en rechts onder. Uiteindelijk had ik voor het laatste gekozen. De stem van de machine had ik links uitgelijnd van het scherm en de stem van K had ik rechts uitgelijnd. Verder had ik stem 4 in het midden uitgelijnd. Verder had ik een fel blauwe dropshadow op de video-placeholder gezet die ik van kleur liet veranderen bij de climax voor het einde van frament 2 (waar ingezoomd wordt op de hoofdpersoon). Hierbij veranderde ook de grootte en dikte van de letters op dat moment. Ik hoopte natuurlijk dat dit iets zou doen met Marie... 

## Feedback Marie 

- De ondertitels waren nu niet fijn te lezen. Het leek wel alsof ze naar een tenniswedstrijd aan het kijken was. 
- De climax kwam totaal niet over. 
- Ze vond de blauwe video-placeholder te abstract. Als de kleursveranding van de dropshadow staat voor verandering van het geluid, dan wil ze weten wat dat geluid dan is. 
- Comments erbij zou ze dus fijn vinden. 
- Marie vond het cool dat ik had gedacht aan hoe ik de letters wilde weergeven (niet meteen zichtbaar, maar woord voor woord).

## Feedback Vasilis
- Vasilis vond dat ik goed bezig was en vertelde eigenlijk aan ons alledrie (Rebecca Lisa en ik), dat we vooral moesten kijken naar hoe we het geluid zouden gaan visualiseren. We waren nu best wel bezig geweest met de closed captions zelf namelijk.

# Test 2

## Mijn ontwerp

Ik heb veel aangepast na de eerste feedback van Marie. Zo heb ik zelf tekst toegevoegd om duidelijker te maken om wat voor geluid het gaat. Daarvoor heb ik best wel een tijdje nagedacht over de juiste tekst (in het Engels).  Ook het implementeren van de 'nieuwe tekst' ging niet erg makkelijk helaas, dus daar was ik veel tijd aan kwijt waardoor ik nog steeds alleen bezig was met het eerste fragment. Verder heb ik de closed captions een glow meegegeven en de achtergrond donkerder gemaakt zodat het er nog spannender uit zou zien. Ook heb de closed captions op 1 regel gezet i.p.v. links - rechts. Door middel van kleur heb ik onderscheid gemaakt tussen de stemmen. De extra tekst heb ik onder de closed captions gezet.  

## Feedback Marie 

- Ze vond het in het algemeen goed wat ik had. Dat was het eerste wat ze zei. 
- Ze was super enthousiast over de sfeer/kleur gebruik en het glow effect op de tekst. 
- De tekst was goed te lezen.  
- Ze vond het cool dat ik ook een shake animatie in de 'extra tekst had toegevoegd'.  
- Ze zei dat ik nog moest kijken naar de uiting van de beschrijving. Er zat nu wel een animatie in de tekst maar nog niet in de video-placeholder (alleen op de plek van de climax). Daar kon ik nog naar gaan kijken. 
- De climax kwam heel goed op haar over, ze voelde 'm echt goed (ik vroeg hier specifiek naar). 

## Feedback Vasilis
- Vond de algemene sfeer erg goed. 
- Vond de climax niet goed over komen (dit heb ik daarna nog snel aangepast voordat we de tekst met Marie hadden. Ik had de letters van SUDDDEN SILENCE groter gemaakt). 

# Eindresultaat - belangrijkste ontwerpkeuzes

## Font

Ik hebben gekozen voor het Brenner font omdat er keuze was uit veel verschillende fonts. In het begin had ik Brenner Display voor de Machine en Brenner Mono voor K. Maar uiteindelijk ben ik toch gegaan voor Mono bij alle tekst maar heb ik gevarieerd in italic, normal en light. Verder heb ik bij de stem van de machine een roze dropshadow gezet. 


<img width="1086" alt="Schermafbeelding 2020-05-29 om 07 30 12" src="https://user-images.githubusercontent.com/45544342/83224748-7343dd00-a17e-11ea-91d2-1ea284936943.png">

De roze dropshadow bij de machine/ in combinatie met blauwe hightlights. De woorden worden 1 voor 1 laten zien bij het eerste fragment. Bij het tweede fragment wordt alles meteen laten zien omdat er meer spanning is en het sneller gaat. 

<img width="1098" alt="Schermafbeelding 2020-05-29 om 07 38 37" src="https://user-images.githubusercontent.com/45544342/83225168-78555c00-a17f-11ea-8b80-661a3b54a568.png">

Het was lastig om hier een foto van te maken. Maar er is veel variatie in hoe de tekst verschijnt bij K. Zo zijn de antwoorden van K light wanneer de baseline test nog niet is begonnen en verschijnt het antwoord in een keer. Wanneer hij bezig is met de baseline test, zie je de tekst al staan alleen worden de woorden 1 voor 1 dikgedrukt. Dit heb ik gedaan om naar voren te laten komen dat hij een stuk tekst voorleest wat in zijn systeem zit. Daarom staat het er al, maar worden de woorden 1 voor 1 dikker. Bij fragment 2 zijn is dit effect weggehaald en zie je alles in 1 keer. Dat heb ik gedaan om het directer te laten overkomen, omdat er in fragment 2 meer spanning is. Ook heeft K meer meegemaakt in de film waardoor hij het riedeltje niet echt meer voorleest. 


## Geluid - belangrijkste 

<img width="1102" alt="Schermafbeelding 2020-05-29 om 07 43 02" src="https://user-images.githubusercontent.com/45544342/83225663-92dc0500-a180-11ea-846b-50bec370cb3f.png">

Na de feedback van Marie, heb ik naast de animaties in de toegevoegde tekts, tegelijkertijd een animatie gezet op de video-placeholder. Zo is de beschrijving echt gelinkt aan de omschrijving, en geeft de kleursverandering en het ritme en  van de beweging van de video-placeholder ook meer over het geluid. 

<img width="1680" alt="Schermafbeelding 2020-05-29 om 07 49 46" src="https://user-images.githubusercontent.com/45544342/83225880-04b44e80-a181-11ea-8505-1ff7d8024300.png">


Het scherm wordt langzaam gevuld met grijze waas. Dit grote effect heb ik bedacht voor het laatste fragment, omdat je de muziek continue best hard hoort en deze tot het einde doorgaat. De spanning houdt aan. Ik wilde een groot verschil maken 






















# Exclusive Design Principles
















# Wat heb ik geleerd? 


































