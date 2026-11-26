# 8. házi feladat – Használhatósági tesztelés és UI-irányelv

## 1. A feladat célja

A nyolcadik feladat két fő témakört dolgoz fel:
- Használhatósági tesztelés tervezése, vezetése és az eredmények értékelése.
- A FoodLens alkalmazás vizuális rendszerének egységesítése egy mini UI-irányelv segítségével.

## 2. Használhatósági tesztelés

A tananyag alapján a használhatósági teszt célja annak megfigyelése, hogy a felhasználók mennyire képesek önállóan elvégezni egy adott feladatot a terméken vagy prototípuson.

A tesztelés fontos szempontjai:
- Világos tanulási célok meghatározása.
- A célfelhasználókhoz illeszkedő résztvevők kiválasztása.
- Tájékozott beleegyezés és a résztvevők adatainak védelme.
- A feladatvégzés megfigyelése és dokumentálása.
- A problémák súlyosságának és javítási prioritásának meghatározása.

A használhatósági leletek a megfigyeléseket, bizonyítékokat, felhasználói következményeket és feltételezett okokat tartalmazzák. A problémák súlyosságát a hatás, a gyakoriság és a helyreállíthatóság alapján értékeljük.

## 3. FoodLens – Mini UI-irányelv

A Figma Design fájlban létrejött egy külön `UI-irányelv` oldal, amely a FoodLens vizuális rendszerének szabályait dokumentálja.

### Színpaletta

Létrejött a `Paletta` nevű Color collection, amely az alkalmazás alapvető színeit tartalmazza:
- Zöld árnyalatok.
- Semleges színek.
- Siker, figyelmeztetés és hiba állapotszínek.
- A sötét módhoz szükséges további színek.

### Szemantikus változók és témák

Létrejött a `Téma` nevű Color collection, amely a színek felhasználási szerepét határozza meg.

A változók többek között:
- `szöveg/elsődleges`
- `szöveg/másodlagos`
- `felület/háttér`
- `felület/kártya`
- `felület/keret`
- `művelet/elsődleges`
- `állapot/siker`
- `állapot/figyelmeztetés`
- `állapot/hiba`

A gyűjtemény két módot tartalmaz:
- Világos
- Sötét

A szemantikus változók a Paletta gyűjtemény alapértékeire hivatkoznak aliasok segítségével.

### Térközváltozók

Létrejött a `Térközök` nevű Number collection.

| Változó | Érték |
|---|---:|
| térköz/1 | 4 |
| térköz/2 | 8 |
| térköz/3 | 16 |
| térköz/4 | 24 |
| térköz/5 | 32 |
| térköz/6 | 48 |

### Tipográfia

Az alkalmazás egységes tipográfiai rendszere öt újrafelhasználható Text Style-ból áll:

| Stílus | Betűméret / sorköz |
|---|---|
| Főcím | 28 / 34 px |
| Alcím | 20 / 28 px |
| Törzsszöveg | 16 / 24 px |
| Címke | 14 / 20 px |
| Gombfelirat | 16 / 24 px |

A választott betűcsalád az Inter.

## 4. UI-szabályok

### Gombok
- Képernyőnként egy elsődleges művelet kapjon hangsúlyos megjelenést.
- A felirat egyértelműen nevezze meg a műveletet.
- A fontos állapotok: alap, fókusz, lenyomott, tiltott és betöltő.

### Beviteli mezők
- Minden mezőhöz jól látható címke tartozzon.
- A hibás állapotot szöveges üzenet is jelezze.
- A mezők megjelenése legyen következetes.

### Ikonok
- Egységes ikonkészletet kell használni.
- A fontos vagy félreérthető műveleteknél szöveges címke is jelenjen meg.
- Az ikonokhoz szükség esetén szöveges alternatíva tartozzon.

## 5. Hozzáférhetőség és kontraszt

A normál szöveg és háttér közötti kontraszt célértéke legalább 4,5:1, a nagy méretű szövegeké és információt hordozó felületi elemeké legalább 3:1.

A sikeres, figyelmeztető és hibás állapotokat nem kizárólag színnel kell megkülönböztetni.

## 6. További teendők

A változók és stílusok létrehozása megtörtént, azonban a teljes alkalmazás egységesítése még hátravan.

A következő lépések:
- A szemantikus színváltozók alkalmazása a végleges képernyőkön.
- A szövegstílusok alkalmazása a képernyők szövegein.
- A térközváltozók hozzárendelése az Auto Layout elemekhez.
- A világos és sötét mód működésének ellenőrzése.
- A kontrasztarányok ellenőrzése a tényleges felületeken.

Ezeket a lépéseket a képernyők elrendezésének véglegesítése után érdemes elvégezni.
