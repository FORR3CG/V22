# FORR3CG - Skilaverkefni 2 (15%)

- **Verkefnið er einstaklingsverkefni.** Ef tveir eða fleiri nemendur skila sömu lausnunum er gefið 0 (núll) fyrir þær lausnir.
- **Ef kóði er tekinn af netinu** (eða öðrum álíka stöðum) skal taka það fram, benda á hvaðan hann kemur og skrifa skýringar (e. comment) við hverja línu kóðans. Sé það ekki gert verður gefið 0 (núll) fyrir verkefnið í heild.
- **Ekki er heimilt** að nota tilbúnar lausnir fyrir listaklasann eins og t.d. std::vector.

## Verkefnalýsing

Nú er [hafísinn](https://www.mbl.is/200milur/frettir/2022/02/02/fundu_enn_staerri_isjaka_og_lentu_a_honum/) farinn að sjást við landið og því vantar þyrslusveit Landhelgisgæslunnar forrit til að halda utan um ísjaka sem hún finnur.

Hver ísjaki sem finnst fær númer (id) auk þess sem skrá þarf stærð hans í fermetrum (t.d. 500 m<sup>2</sup>) ásamt fjarlægð hans frá landi í kílómetrum (t.d. 3,5 km.) talið.

Þú þarft því að skrifa klasa sem inniheldur upplýsingar um einn ísjaka. Útfærðu smiði, getters, setters og prenta fall. Það þarf að vera hægt að bera saman tvo ísjaka þannig að þú þarft að útfæra samanburðarvirkjana (`==`, `!=`, `<`, `>`, `<=` og `>=`). Samanburðurinn byggir fyrst á stærð ísjakanna og síðan hversu langt frá landi þeir eru.

Skrifaðu svo annan klasa (listaklasa) sem heldur utan um upplýsingar um marga ísjaka. Þessi klasi á að nota kviklegt fylki (e. dynamic array) til að geyma mörg tilvika af ísjaka klasanum (**ATH.** þarf ekki að vera raðað). Upphafsstærð fylkisins skal vera fimm stök og skal það svo stækka um tíu stök í hvert sinn sem það þarf að stækka. Passa þarf upp á að endurnýta laus stök ef ísjaka hefur verið eytt úr listanum. Skrifaðu smiði og eyði (e. destructor) eftir þörfum.

Það þarf að vera hægt að:

- Skrá ísjaka í listann (bæði setja inn tilvik af ísjakaklasanum og líka með því að setja inn upplýsingar um ísjaka).
- Eyða ísjaka úr listanum eftir númeri (id) hans.
- Uppfæra fjarlægð ísjaka frá landi út frá númeri (id) hans.
- Skrifa alla ísjakana á skjá.
- Skrifa einn ákveðinn ísjaka á skjá eftir númeri (id) hans.

Skrifaðu svo forrit sem sýnir notkun klasanna. Ekki þarf að huga neitt að villuprófunum. Ekki þarf að bregðast við tvískráningum. Öll gögn skal harðkóða.

Mundu að skipta klösunum upp í .h og .cpp skrár.

Skilið svo öllum skránum (ættu að vera tvær .h skrár og þrjár .cpp skrár) á Innu.
