---
date:         2021-02-18
category:     blog
tags:         bezpečnost cenzura legislativa
layout:       post
title:        "Piráti prosadili stopku Vojenskému zpravodajství na sledování online komunikace. Nedostatečné ošetření zásahů a děravá kontrola přetrvávají"
image:        articles/2021/2021-02-18-pirati-prosadili-stopku-vojenskemu-zpravodajstvi-na-sledovani-online-komunikace.jpg
author:       František Kopřiva, Ondra Profant
---

Vojenské zpravodajství dostalo za úkol vykonávat kybernetickou obranu už v minulém volebním období, kdy byla také předložena první verze novely zákona, která měla zpravodajské službě Armády ČR umožnit odpovídající pravomoci a nastavit zákonný rámec obrany důležitých zájmů státu v kyberprostoru. Novela byla tehdy právem rozcupována a spadla pod stůl mj. i díky tlaku Pirátů, kteří v roce 2016 uspořádali demonstraci. Zákon byl totiž napsaný tak, že by zpravodajci mohli sledovat obsah komunikace na internetu, tedy de facto zavedení možnosti odposlechu občanů bez povolení soudu.

**Šmírování uživatelů na internetu?**  
Další pokus už jsme měli možnost sledovat ze sněmovních lavic, když byla další verze novely představena na jaře 2018. Návrh byl však stejně nepřijatelný jako předchozí verze. Ve stejném duchu se vyjádřili jak zástupci odborné veřejnosti, tak i provozovatelé internetových sítí a také řada státních institucí v mezirezortním připomínkovém řízení.

Zatímco návrh zásadním způsobem rozšiřoval pravomoci Vojenskému zpravodajství, nenastavoval těmto novým pravomocím žádné mantinely a zcela nedostatečně ošetřoval kontrolu. Konkrétně zákon zaváděl možnost umisťovat tzv. sondy bez vymezení toho, jaká všechna data mohou sbírat, jakým způsobem se budou do komunikační sítě umisťovat ani zda tyto “černé krabičky” budou aktivní či pasivní. Dále návrh umožňoval provádět v podstatě neomezeně tzv. aktivní zásahy, opět bez bližšího upřesnění. Ačkoliv se Vojenské zpravodajství dušovalo, že cílem není sledovat obsah komunikace na internetu a aktivní zásah má být jen tím nejzazším řešením, formulace byly vágní a ponechávaly možnost zneužitelného výkladu.

Začali jsme tedy okamžitě jednat jak se zástupci Vojenského zpravodajství, tak s profesními sdruženími, nevládními organizacemi i soukromým sektorem, abychom zákon opravili a více odpovídal naší představě zodpovědné, vyvážené kyberbezpečnosti. Naším cílem bylo, aby Vojenské zpravodajství mělo možnost sledovat provoz v síti (netflow), identifikovat podezřelé signatury a odhalit tak včas chystaný útok na kritickou infrastrukturu.

12. 2. 2021 Poslanecká sněmovna zákon schválila. V zákoně zůstalo několik nedostatků a Poslanecká sněmovna nepodpořila naše pozměňovací návrhy, rozšiřující například možnosti kontroly, proto jsme pro zákon ruku nezvedli. Podařilo se nám však prosadit řadu změn, které napravily aspoň ty nejzásadnější nedostatky.

**Co se povedlo opravit**  
Jedním z hlavních nedostatků byla vágnost pojmů a definic. Ve světě internetové a komunikační bezpečnosti je potřeba pravomoce a povinnosti detailně specifikovat, protože technologie se neustále vyvíjí, a jestliže nechceme zákon měnit každých pár let, je třeba jasně definovat pravomoce, kterými bude Vojenské zpravodajství disponovat.

Hlavním úspěchem je bezesporu jasnější vymezení dat, které mohou nástroje detekce (dříve sondy) v kybernetickém prostoru monitorovat a sbírat - v zákoně je nakonec explicitně uvedeno, že nástroje detekce mohou monitorovat pouze metadata, tedy nikoliv obsah komunikace.

Stejně tak se podařilo v zákoně nastavit model spolupráce mezi Vojenským zpravodajstvím a provozovateli sítí (typicky velcí operátoři nebo lokální poskytovatelé) tak, že zpravodajci budou data přebírat primárně na základě smlouvy, umístění nástroje detekce by tak mělo být řešením až v případě, že poskytovatel odmítne spolupráci.

S tím souvisí další pozitivní změna, protože se podařilo prosadit jasné podmínky správního řízení, které by rozhodovalo o umístění detekčních zařízení do komunikační infrastruktury. Zákon také nově provozovatelům sítě zlepšuje vymahatelnost náhrady za škodu a náklady, které jim v souvislosti s činností Vojenského zpravodajství (např. umístěním nástroje detekce) mohou vzniknout.  
  
**Co se nepovedlo opravit**  
Bohužel se nám nepodařilo přesvědčit předkladatele, aby se lépe vymezily podmínky pro aktivní zásahy, které mohou být fakticky protiútokem v kyberprostoru. V původním návrhu zákona nebyly žádné podmínky, na základě našich připomínek jsou sice v zákoně uvedeny podmínky, že musí být ohroženy důležité zájmy státu, útok bezprostředně hrozí a nelze odvrátit jiným způsobem, což je rozhodně krok správným směrem. Tyto podmínky jsou však nedostatečné v tom smyslu, že mohou být naplněny celou řadou i méně závažných situací, neboť v kyberprostoru se obtížně posuzují. Uvedené podmínky jsou stále ještě mírnější, než je ukládáno mezinárodním právem dle takzvaného Talinského manuálu, který kybernetické operace omezuje více než tento zákon.

Ačkoliv Vojenské zpravodajství předpokládá nasazení pouze pasivních nástrojů detekce pro záznam metadat, v zákoně není explicitně uvedeno, že tato zařízení nemohou být i aktivní. To je problematické z toho důvodu, že aktivní sonda by mohla do komunikace přímo zasahovat (přesměrování, editace, mazání), případně blokovat přístup k některým webům nebo se vydávat za někoho z účastníků komunikace.

Při finálním hlasování sněmovna vyškrtla výjimku z mlčenlivosti pro provozovatele sítí, aby se tito mohli obrátit na kontrolní orgány v případě podezření na překročení pravomocí Vojenského zpravodajství. Většina ve sněmovně také nepodpořila naše pozměňovací návrhy, které rozšiřovali možnosti kontroly jak ze strany tzv. Orgánu nezávislé kontroly, tak ze strany sněmovní Stálé komise pro kontrolu činnosti Vojenského zpravodajství. Stejně tak neprošel náš návrh, upravující spolupráci Vojenského zpravodajství a Policie ČR. Zákon tak stále implicitně umožňuje provedení aktivního zásahu, určeného pro obranu státu, na žádost Policie, což by bylo zneužití armády k boji s běžnou, domácí kriminalitou.

**Co zákon přináší**  
Z pohledu běžného uživatele internetu se nová úprava pravomocí Vojenského zpravodajství téměř neprojeví. Pozice provozovatelů komunikačních sítí se v zákoně narovnala, takže i na ně by novela neměla mít zásadní dopad. Armádě ČR i její zpravodajské službě důvěřujeme a je i naším zájmem, aby měli práva a povinnosti odpovídající aktuálním trendům. Důvodem, proč jsme se tomuto zákonu věnovali takhle intenzivně, je snaha o dodržení principu, že s rozšířením pravomocí má jít ruku v ruce rozšíření kontroly a co nejpřesněji vymezit mantinely, ve kterých se stát (tajná služba) pohybuje.

Další informace a naše výstupy k zákonu o Vojenském zpravodajství jsou dostupné na webu  [https://zachransoukromi.cz/](https://zachranasoukromi.cz/)[.](https://zachransoukromi.cz/)

**Tiskové zprávy - jak šel čas:**  
- [Piráti: Soukromí občanů v ohrožení. Vláda chce zavést možnost zpravodajských služeb šmírovat občany na internetu](https://www.pirati.cz/tiskove-zpravy/soukromi-obcanu-v-ohrozeni-vojenska-rozvedka.html)  
- [Piráti navrhují opatření proti šmírovaní na internetu](https://www.pirati.cz/tiskove-zpravy/internet-smirovani-zpravodajcu-pirati-zamezi.html)  
- [Na programu vlády je kontroverzní novela vojenského zpravodajství, Piráti varují před ztrátou soukromí na internetu](https://www.pirati.cz/tiskove-zpravy/internet-pod-dohledem-zpravodajcu.html)  
- [Pirátům se podařilo prosadit, aby Vojenské zpravodajství nemohlo sledovat online komunikaci, nedostatečné ošetření aktivních zásahů a děravá kontrola však přetrvávají](https://www.pirati.cz/tiskove-zpravy/online-komunikace-smirovani-vojenske-zpravodajstvi.html)
