# Kőkataszter weblap
rövid használati leírás

## verzió

A korábbi honlapverzió változtatás nélkül az ```_old_web``` mappában található.
Az újabb változat a ```web``` mappába került, az eredeti fájlok módosításával, kiegészítésével és az eredeti, nem módosult fájlok megtartása mellett.

## mappa és fájlstruktúra

A projekt mappastruktúrája megegyezik a korábbi változatával a könnyebb karbantartás érdekében.
A főoldal a web mappában található ```index.html```
Az almappák maradtak az eredeti struktúrának megfelelőek.
A _banyak_ mappában almappákba rendezve az egyes bányákra vonatkozó képek és ```index.html```, mely az adott bányára vonatkozó aloldalnak megfelelő lap.
A _kellekek_ mappában a weboldal megfelelő működéséhez szükséges állományok kaptak helyet: főként javascript kódfájlok, stíluslapok, és képek
A _segedanyagok_ mappa tartalma nem módosult

## Tartalom feltöltése

Új bánya hozzáadásához a kódot az alábbi helyeken szükséges módosítani:
* főoldalon (```web/index.html```) jelenleg a 144. sornál kommenttel jelölt helyen új area tag beszúrásával a térképen klikkelhető pont keletkezik
* szintén a főoldalon jelenleg a 227. sornál, szintén kommenttel jelezve új sorba másolva a bányákra mutató mappa útvonalát másolva, a válaszó mezőben új elem keletkezik
* a _banyak_ mappában a meglévő struktúra szerint új mappa létrehozása, az index.html-t egy másik bánya alapján másolni lehet természetesen a tartalom módosítása mellett.
    egyes esetekben nem volt link megadva, ilyenkor is található kikommentezett link elem, ezek mintájára lehet az esetleges linkeket beszúrni