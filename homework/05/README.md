# 5. házi feladat – Információarchitektúra és feladatfolyamok

## Projekt

FoodLens – élelmiszer-értékelő alkalmazás koncepciója.

## Feladat célja

Az alkalmazás információarchitektúrájának megtervezése, a tartalmak és funkciók logikus csoportosítása, valamint a fő felhasználói feladat útvonalának meghatározása. A cél egy olyan sitemap és user flow elkészítése, amely megalapozza a következő házi feladat wireframe-jeit.

## Tartalomleltár és kártyarendezés

A projekt korábbi szakaszában összeállítottam a FoodLens fő tartalmi elemeit és funkcióit tartalmazó, 18 elemből álló tartalomleltárt.

A tartalmakat az alkalmazásban betöltött szerepük alapján csoportosítottam:

- **Termékek:** termékkeresés, vonalkód-beolvasás, termékadatok, összetevők, tápértékadatok és összehasonlítás.
- **Személyre szabás:** egyéni táplálkozási preferenciák és kerülendő összetevők.
- **Beállítások:** az alkalmazás általános beállításai.
- **Segítség:** súgó és használati útmutató.

A címkéket igyekeztem röviden és közérthetően megfogalmazni. Például a „Termék neve és alapadatai” helyett a „Termék adatlapja”, a „Kedvencek mentése” helyett pedig a „Kedvencek” elnevezést használom.

A tényleges, legalább három résztvevővel végzett kártyarendezés nem történt meg, ezért a csoportosítás tervezői döntéseken alapul, nem felhasználói kutatási eredményeken.

## Sitemap

Elkészítettem az alkalmazás oldalszerkezetét bemutató sitemapet.

A kezdőlap alatt két fő területet különítettem el:

- **Termékek:** keresési találatok, termékadatlap, részletes értékelés, összetevők listája, korábban megtekintett termékek és kedvencek.
- **Személyre szabás:** egyéni táplálkozási preferenciák és kerülendő összetevők beállítása.

A Beállítások és a Segítség külön területként jelenik meg.

A kezdőlapon két fontos belépési pontot jelöltem meg: a vonalkód beolvasását és a név szerinti termékkeresést.

## User flow és kivételes állapotok

A fő felhasználói cél:

„Szeretném megtudni, hogy milyen összetevőket tartalmaz ez a termék.”

A fő feladat útvonala:

Kezdőlap → Vonalkód beolvasása → Termék keresése az adatbázisban → Termék adatlapja → Összetevők elemzése → Sikeres lezárás.

A folyamatban döntési pontokat is elhelyeztem, amelyekhez külön cetliken feltüntettem a szükséges információkat.

A megtervezett kivételes állapotok:

- Sikertelen vonalkód-beolvasás: újrapróbálás vagy név szerinti keresés.
- Nem található termék: új keresés vagy másik termék beolvasása.
- Hiányos termékadatok: a hiányzó adatok jelzése és a rendelkezésre álló információk megjelenítése.
- Megszakított beolvasás: visszatérés a kezdőlapra.

A sikeres és a sikertelen, illetve részleges kimeneteket külön jelöltem.

## Kiválasztott wireframe-képernyők

A következő, 6. házi feladatban a fő feladat útvonalához kapcsolódó négy képernyőt tervezem wireframe formájában kidolgozni:

1. Kezdőlap.
2. Vonalkód beolvasása.
3. Termék adatlapja.
4. Összetevők elemzése.

A kezdőlap, a termék adatlapja és az összetevők elemzése már korábban elkészült a Figma Design felületén. A vonalkód-beolvasás képernyő új elemként kerül majd kidolgozásra.

## Ellenőrizhető eredmény

https://www.figma.com/board/adxANJ9pDY3aONvekZi487/UX-projekt-%E2%80%93-1.-kiindul%C3%A1s?node-id=32-291&t=TuUCReqDCxXZ427g-1

## Megjegyzés

A sitemap és a user flow a FoodLens korábban meghatározott céljára és funkcióira épül. A kártyarendezés nem tényleges résztvevőkkel végzett kutatás eredménye, hanem a tartalomleltár alapján kialakított tervezői csoportosítás. A kivételes állapotok a tervezett működést mutatják, a tényleges alkalmazásban való megvalósításuk a későbbi fejlesztési szakasz feladata.
