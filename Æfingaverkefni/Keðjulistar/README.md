# FORR3CG - Æfingaverkefni

## Bílastæði með keðjulista

Þetta forrit á að halda utan um bíla á bílastæði. Skiptu öllum klösum í .cpp og .h skrár (nema Node, nóg að hafa það bara í .h skrá).

Notaðu bílastæðaklasann sem þú gerðir í [þessu](https://gist.github.com/gestskoli/6ce1f3234158e12bd5c8fc60de30a0d3) æfingaverkefni. Ef þú ert búinn að týna bílaklasanum þínum getur þú notað [þennan](https://gist.github.com/gestskoli/910f1989c389c963256b6114b62f280f).

Búðu svo til *BilaNode* `struct`.

Skrifaðu svo klasann *Bilastaedi*, sem á að halda utan um keðjulista (e. linked list) af bílum. Klasinn á að eiga eina gagnabreytu og á það að vera bendir (e. pointer) á fyrstu nóðuna. Klasinn þarf að eiga eftirfarandi föll:

- Smið (e. constructor).
- Tvö föll til að setja bíl **aftast** í listann:
  - Annað sem tekur inn tilvik af *Bill* klasanum.
  - Hitt tekur inn upplýsingar um bíl (id, tegund, litur), býr til tilvik af *Bill* klasanum og setur aftast í listann.
- Tvö föll til að eyða bíl úr listanum (þurfa ekki að skila bílnum).
  - Annað sem eyðir fremsta bílnum úr listanum.
  - Hitt tekur inn *id* og eyðir bíl með því *id*.
  - Bæði föllin skulu birta viðeigandi skilaboð ef listinn er tómur eða bíll með því *id* sem leitað var að finnst ekki.
- Skrifa ákveðinn bíl á skjáinn. Fallið tekur inn *id* á bíl, leitar að honum í listanum og skrifar hann á skjáinn. Finnist enginn bíl með því *id* eða listinn er tómur skal birta viðeigandi skilaboð.
- Skrifa alla bílana í listanum út á skjáinn.
- Eyðir (e. destructor).

Skrifaðu svo forrit sem sýnir virkni *Bilastaedi* klasans.

## Betrumbætur (fyrir þá sem vilja)

Breyttu *Bilastaedi* klasanum þannig að hann hafi tvo benda, annan sem bendir á fremstu nóðuna og hinn sem bendir alltaf á síðustu nóðuna.

Hverju þarf að breyta? Það er nóg að breyta smiðnum, fallinu sem setur í listann og svo fallinu sem eyðir ákveðnum bíl.
