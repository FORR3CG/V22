# FORR3CG - Skilaverkefni 3 (15%)

- **Verkefnið er einstaklingsverkefni.** Ef tveir eða fleiri nemendur skila sömu lausnunum er gefið 0 (núll) fyrir þær lausnir.
- **Ef kóði er tekinn af netinu** (eða öðrum álíka stöðum) skal taka það fram, benda á hvaðan hann kemur og skrifa skýringar (e. comment) við hverja línu kóðans. Sé það ekki gert verður gefið 0 (núll) fyrir verkefnið í heild.
- **Ekki er heimilt** að nota tilbúnar lausnir fyrir forgagnsröðina eins og t.d. `std::priority_queue`.

## Verkefnalýsing

Landhelgisgæslunni leist mjög vel á ísjaka listann sem þú gerðir fyrir hana en nú vill hún sjá ákveðnar breytingar á listaútfærslunni. Helsta breytingin er að nú þarf að hafa ísjakana raðaða í listastanum. Röðunin á að vera þannig að ísjakinn sem er næst landi á að vera fremstur í listanum. Þetta ætlarðu að leysa með því að útfæra forgangsbiðröð (e. priority queue) með **keðjulista** (e. linked list).

Þú þarft því að breyta hvernig samanburaðarvirkjarnir eru útfærðir í Ísjaka klasanum, fyrst á að horfa til fjarlægðar frá landi og síðan stærðarinnar en númerið (id) á ekki að nein áhrif á röðunina.

Úr gömlu verkefnalýsingunni:

> Hver ísjaki sem finnst fær númer (id) auk þess sem skrá þarf stærð hans í fermetrum (t.d. 500 m<sup>2</sup>) ásamt fjarlægð hans frá landi í kílómetrum (t.d. 3,5 km.) talið.
Þú þarft því að skrifa klasa sem inniheldur upplýsingar um einn ísjaka. Útfærðu smiði, getters, setters og prenta fall. Það þarf að vera hægt að bera saman tvo ísjaka þannig að þú þarft að útfæra samanburðarvirkjana (`==`, `!=`, `<`, `>`, `<=` og `>=`). ~~Samanburðurinn byggir fyrst á stærð ísjakanna og síðan hversu langt frá landi þeir eru.~~

Þú þarft svo að skrifa nýjan listaklasa (og gera Node struct/klasa) sem geymir Ísjakana í réttri röð.

Það þarf að vera hægt að:

- Skrá ísjaka í listann (bæði setja inn tilvik af ísjakaklasanum og líka með því að setja inn upplýsingar um ísjaka).
- Eyða ísjaka, eyðir fyrsta ísjakanum í listanum.
- Eyða ísjaka úr listanum eftir númeri (id) hans.
- Uppfæra stærð ísjaka út frá númeri (id) hans.
- Skrifa alla ísjakana á skjá.
- Skrifa einn ákveðinn ísjaka á skjá eftir númeri (id) hans.

Gerðu svo smiði og destructor-a eftir þörfum.

Skrifaðu svo forrit sem sýnir notkun klasanna. Ekki þarf að huga neitt að villuprófunum. Ekki þarf að bregðast við tvískráningum. Öll gögn skal harðkóða.

Mundu að skipta klösunum upp í .h og .cpp skrár.

Skilið svo öllum skránum (ættu að vera þrjár .h skrár og þrjár .cpp skrár) á Innu.
