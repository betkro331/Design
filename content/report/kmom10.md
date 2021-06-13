---
Title: Kmom 10
Description: Report for sub-course 10 (project)
---

<div class="wrapper">
    <div class="aside-left">
        <a href="../report/kmom01">Kmom 1</a>
        <a href="../report/kmom02">Kmom 2</a>
        <a href="../report/kmom03">Kmom 3</a>
        <a href="../report/kmom04">Kmom 4</a>
        <a href="../report/kmom05">Kmom 5</a>
        <a href="../report/kmom06">Kmom 6</a>
        <a href="../report/kmom10">Kmom 10</a>
</div>
    <div class=kmom-content>
    <h2>Redovisning för projektet (kmom 10)</h2>
    <p><b>1.1 Uppdrag 1:</b> Jag valde kund 1 eftersom jag tyckte att det verkade roligast att försöka göra en "affärsmässig" hemsida för en advokat- eller managamentfirma. Min kund är en advokatfirma på Östermalm i Stockholm. Jag valde att kopiera från portfolio eftersom det kändes säkrare än att börja om från början. Det är förhållandevis mycket text på vissa av sidorna men advokatfirman riktar sig till företag, och företag vill i första hand ha information om vad advokatfirman kan erbjuda dem snarare än flashiga bilder. Därför är förstasidan informativ medan ”om oss”-sidan ska ge lite mer familjär känsla där advokatfirmans medarbetare presenterar sig med foto och beskrivning av meriter för att skapa ett förtroende och förhoppningsvis få besökaren att vilja välja ”dessa trevliga proffs”. </p>

    <p><b>1.1 Uppdrag 2:</b> Färgerna guldmetallic och bourgogne-röd valde jag ut som basfärger efter att ha tittat på många hemsidor för advokatfirmor och managementkonsulter. Loggan och faviconen har dessa två basfärger och motivet balansvågen, som står för rättvisa - något en advokatfirma gärna signalerar. Som hero-image valde jag hustaken på Strandvägen på Östermalm i Stockholm för att skapa en ”exklusiv” känsla. Basfärgerna mörk bourgogne och guld går även igen i footern och som ram runt presentationen av advokatfirmans medarbetare. Jag använde samma nav och footer på alla sidor, för igenkänning och trygghetskänsla. Basfärgerna går igen på alla sidor mer eller mindre mycket (t ex i rubrikerna) tillsammans med vitt och svart. Jag har försökt balansera dessa ganska tunga färger med en del vita ytor så att sidorna ”andas”, men också för kontrast.</p>

    <p><b>1.1 Uppdrag 3:</b> Att å enda sidan tänka kreativt och försöka göra något som andas lyx och exklusivitet samtidigt som Lighthouse lätt klagar på kontraster, är förstås lite knepigt. Eftersom 100 % tillgänglighet var ett krav fick det andra stå tillbaka. Jag testade Google Lighthouse tidigt i processen och sedan löpande för att se till att få 100 % tillgänglighet ”från början” och inte behöva göra om. Jag har använt CSS-grid på alla sidor och testade responsiviteten i flera browsers. Mobilläget såg oftast bra ut men när man i devtool drar mellan stor och liten skärm blev det ibland hoppigt. Bilderna är anpassade efter Cimage crop-to-fit ratio 1:1 och såg ut att fungera bra på minde enheter medan de markerade gridboxarna ibland fick viss eftersläpning. Jag valde att inte ha video eller stora flashiga bilder, dels med tanke på de resurser som krävs men också med tanke på uppdraget från kunden. Af Solstråles målgrupp är företag, dvs hyfsat ofta medelålders personer som söker en juridisk samarbetspartner, och vill ha läsbarhet och lättillgänglig information framför en ”säljpitch med stora glassiga foton”. </p>

    <p><b>1.1 Uppdrag 4</b> är inte implementerat.</p>  

    <p><b>1.1 Uppdrag 5:</b> Eftersom jag i detta projekt har valt att göra en hemsida åt en fiktiv advokatfirma var det både roligt och passande att välja att göra analys av advokatbyråers webbplatsdesign. Jag utgick ifrån en artikel som tog upp sju aktuella webbdesign-trender och analyserade huruvida de fyra utvalda advokatfirmorna följer dessa sju trender eller inte.</p>

    <p><b>1.1 Uppdrag 6:</b> Jag valde att göra en färganalys och använde mallen från kmom04 i möjligaste mån. Jag försökte att ”titta utifrån” och jämföra med ett gäng helt nyvalda advokatfirmor. Jag ser ju tydligt att jag har mängder av idéer på hur jag skulle vilja att af Solstråles hemsida ser ut, men att jag inte har kunskapen och erfarenheten (och tiden) för att åstadkomma detta.</p> 

    <p><b>1.2 Allmänt stycke om projektet:</b> Det var ett mastigt men roligt projekt. Jag har lärt mig mycket genom trial-and-error i CSS. Frustrerande men också givande. När jag hade fixat navbar med hero-image och förstasidans grid-boxar med informationstext så kollade jag Lighthouse för accessibility för att se att jag var på rätt väg. Det gick förhållandevis bra med allt på förstasidan. Sidan två (om oss) med medarbetarpresentationen var mycket svårare. Jag hade problem med att få till Cimage med crop-to-fit ratio 1:1 som jag ville ha. Jag vet inte om jag gjorde en fullösning med att lägga texten i {{ content }} under forloopen för bilderna. Responsiviteten blev kanske inte optimal men den fungerade i de olika browsers som jag testade.</p>

    <p><b>1.3 Tankar om kursen:</b> Det var ett kul projekt men med många trådar att hålla i. Jag har inte följt kursveckorna utan försökt göra klart respektive kursmoment nu inför restinlämningarna juni 2021. Det är förstås inte optimalt om man inte får godkänt på ett kursmoment och redan har lämnat in resten. Men bortsett från det har det fungerat mycket bra för mig att göra denna kurs i min egen takt. Kursen har varit mycket lärorik, kreativ och rolig med stor bredd som inkluderade även prestanda och tillgänglighet.  Det jag kanske saknar så här i efterhand är att vi inte gick igenom Lighthouse Performance. Eftersom vissa hemsidor har bra tillgänglighet men dålig performance så hade det varit intressant att få exempel på hur dessa bäst skulle kunna åtgärdas. En ytterligare synpunkt är önskemål om att ni förklarar vissa saker lite bättre. Begrepp som ”hero-bild” eller ”flash-image” är för er lärare självklara saker men inte för en nybörjare. Jag hittade en mycket bra yt-video som förklarade detta, men allt sådant tar tid och en enkel förklaring från er hade inte skadat. Det var lite rörigt att får ordning på Github i början och den genomgången kändes lite forcerad. En mer genomgripande förklaring av bregrepp, t ex skillnaden på git commit och git tags men också vad "to be staged" betyder. Överlag är nöjd med kursen och ger den betyg 7/10.</p>

</div>
