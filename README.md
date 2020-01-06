# Hemsida för skolarbete.
En hemsida för skolarbete. Html och css. OBS! Glöm inte att ta göra en lokal kopia. Viktigt med en egen lokal backup.

# Att göra innan inlämning.
* Johanna länkar till icke lokala källor.
* Ska h1 utanför main vara samma på alla sidor?
* Ska title vara samma på alla sidor och följa brödsmulor metoden?
* Zippa filer och tillsammans med länk till github pages.
* Ladda in på skolans projekt sida.

# Checklista krav för uppgifter
* ok. [index.html] hos https://validator.w3.org/ .
* ok. [style.css] hos https://jigsaw.w3.org/css-validator/#validate_by_upload+with_options .
* ok. (startsida) [index.html]
* ok. respektive gruppmedlems landningssida  - tre stycken
* ok. css-fil [style.css] - som styr utseendet för hela webbplatsen i alla medföljande HTML-sidor
* ok. minst en bild
* ok. en fungerande global navigation
* ok. minst fem semantiskt strukturerande element som [header, footer, aside, section, article, osv.] vi har header, footer, article, nav, main
* gruppmedlemmarnas landningssidor med fungerande global navigering
  * Andersson.  
  * Lindmark.
  * ok. Månsson.
* korrekt fil/mappstruktur så att länkningarna fungerar
* Webbplatsen ska följa standarden/rekommendationen för HTML 5 och alla gemensamma HTML-filer ska vara valida enligt W3C:s validator för HTML-kod. Om ni anser att ett felmeddelande är orimligt, ska ni kommentera felet i koden samt motivera varför det inte behöver åtgärdas med hänsvisning till lämpliga källor. Okommenterade fel eller svagt motiverade fel innebär att inlämningen underkänns.
* Alla gemensamma HTML-filer ska uppfylla WCAG2 level AA, utan varningar från AChecker. (Följande problemtyper kan ni bortse från: ”Likely Problems” och ”Potential Problems”)
* Innehållet i den gemensamma HTML-filen skall märkas upp med beaktande av strukturen och semantiken i HTML, alltså med hänsyn till vilket innehåll de olika elementen ska användas för.  Exempelvis ska elementen h1, h2 och h3 användas för respektive rubriknivå, elementet blockquote ska enbart användas för just blockcitat och så vidare.
* Element som markeras som ”Deprecated” i specifikationen av HTML 5 skall inte användas.
* Använda den style som finns i relaterad CSS-fil på ett korrekt sätt (undvik redundans i koden).
* Alla gemensamma CSS-filer ska vara valida enligt W3C:s validator för CSS-kod för CSS3. Om ni anser att ett felmeddelande är orimligt, ska ni kommentera felet i koden samt motivera varför det inte behöver åtgärdas med hänsvisning till lämpliga källor.  Okommenterade fel eller svagt motiverade fel innebär att inlämningen underkänns.
* CSS-regler ska sparas i en separat CSS-fil och länkas från HTML-dokumenten med en relativ länk.
* All formgivning skall styras med hjälp av CSS och inte genom att modifiera HTML-koden. Exempelvis skall en följd av radbrytningar inte användas för att åstadkomma större utrymme mellan två stycken, eftersom samma effekt kan uppnås genom att precisera margin med CSS.
* Använda id och class på ett korrekt sätt försök undvika redundans. 

# Information från skolan
Validatorer

Ni kommer att behöva använda W3Cs validatorer. Notera att ingen validator är perfekt så det är fortfarande viktigt att ni följer den standard som validatorn hänvisar till. Validatorerna kan endast validera en sida i taget, dvs. de kan inte validera hela webbplatsen.
HTML: The W3C markup validation service

https://validator.w3.org/#validate_by_upload
CSS: The W3C CSS validation service

https://jigsaw.w3.org/css-validator/#validate_by_upload+with_options (se till att CSS level 3 är vald)

När det gäller CSS-validatorn (CSS3 ska väljas), finns det buggliknande företeelser. Om ni anser att ett felmeddelande är orimligt vid en examination, ska ni skriva vilket felmeddelande ni fått och varför ni anser att det inte behöver åtgärdas, motivera med hjälp av rimliga källor som standarder och kurslitteraturen. Lärarna kommer att dubbelkolla felmeddelandet och ta ställning till huruvida det är rimligt. CSS-validatorn anger felmeddelanden när det finns icke-stardardiserade CSS-regler (webbläsarspecifika regler som "-moz-column-rule-style", t.ex). Dessa ska du undvika i kursen. 
WCAG: WAVE

http://wave.webaim.org/

Tjänsten kontrollerar endast publicerade webbsidor (med URI). En bra tjänst, men du måste lära känna hur den fungerar.
WCAG: AChecker

http://achecker.ca/checker/index.php

Se till WCAG 2 (level AA) är vald.

Denna tjänst brukar ge ett felmeddelande ang. färgkontrast även om en bakgrundfärg är täckt/gömt av annan så att den synliga färgkontrasten på skärmen inte är problematiskt. 
