# Tördelés az Impulzusnál

!!! example "Átdolgozás alatt"
    A tördelés régi folyamata (avagy minden egy nagy dokumentumban) nem kimondottan bizonyosult hatékonynak az együttes munkát illetően, emiatt szerettem volna újítani ezen.

    Kezdésképp elkezdjük használni a könyv (`Book`) funkciót, és újítunk a kiinduló fájlokon.

## Mappaszervezés

`D:\#Újság\`

- `ReDesign`: minden kiinduló fájl és erőforrás (képek, font stb.)
- évenként és számonként bontva a mappák
    - `Képek`
    - `Export`
    - ...

> átdolgozás alatt...

### Lock fájlok

![](img/lockfile.png)

Ha ehhez hasonló lock fájlokat látsz, akkor azt a dokumentumot éppen valaki szerkeszti. Amíg be nem zárja, addig más nem fér hozzá. Feleslegesen ne hagyjunk nyitva dokumentumokat!

## Hogyan kezdj neki

- legyen nyitva az adott számhoz tartozó könyv
    - benne 
        - a borítóhoz tartozó dokumentum
        - a kategóriákhoz tartozó dokumentumok
    - **legyen a borító a stílus forrása** (kis ikon az indesign file logó mellett)
    - ![](img/starter_book.png)

- az oldalak legyenek megfelelően beállítva
    - `Pages > Numbering & Section Options`
    - első oldal és terjedelem legyen beállítva
    - a `Section Marker` legyen a kategória címe
    - az oldalak kövessék a K-Kategória mesteroldalt

- a `ReDesign` mappában található az Impulzus Design Library
    - érdemes ezt is megnyitni, és valahova kitenni

### Impulzus könyvtár

> avagy Design Library

Ez egy `.indl` fájl, ami tartalmaz pár előre definiált elrendezést.
Nyissuk meg és tegyük ki valamelyik panelre.
Válasszuk ki a kívánt elemet és húzzuk be a dokumentumba.
Ügyeljünk, hogy **illeszkedjen a margókhoz és a dokumentum széleihez!**

Magyarázat:

- `J`: jobb oldal
- `B`: bal oldal
- `M`: mindkét oldalon működik
- általában van egy főcím, egy alcím, egy bevezető és a két hasábban a szöveg törzse
- vannak erre egyesített elemek, de egyesével is berakhatjuk
- figyeljünk, hogy az elemek szélei érjenek össze (a margók jól be kéne legyenek állítva)

### Rétegek

A kiinduló fájlok valószínűleg tartalmazni fognak rétegeket:

- **Előtér**: ami minden esetben legfelül kell legyen
- **Munkaterület**: a legtöbb szöveg és alapesetben minden, ami nem máshova megy
- **Grafikák**: képek, illusztrációk, stb.
- **Háttér**: amit mindenképpen hátra szeretnél tenni, érdemes lezárni, ami fix

## Stílusok és egységesség

Amihez csak tudunk használjunk stílusokat, mintákat, könyvtári elemeket stb.

- egyedileg kevert színek helyett használjunk színmintákat és színárnyalatokat
- szöveghez használjunk bekezdésstílusokat, csak indokolt esetben formázzuk egyedileg
- ha nem találod a stílusokat vagy a palettát, ellenőrizd, hogy szinkronizálva vagy-e a könyvvel, és hogy jó kiindulófájlból dolgozol


## Képek

- körbefutás
    - szögletes képekhez kb. 3mm
    - szabad formáknál akár 5mm is, ahogy jól néz ki
- grafikákat **vektoros** formátumban (svg), ha létezik ilyen változat
- mellőzzük a díszes képkereteket
- a lekerekítés legyen egységes, vagy sehol, vagy mindenhol, de akkor ugyanannyi (jelenleg nem használunk ilyet)
- fotók forrása legyen megjelölve
    - a SPOT-ot nem szoktuk egyesével minden képhez megjelölni, őket külön megemlítjük az elején
- szabad formájú körbefuttatott képekhez külön formákat csak indokolt esetben, különben [`Pen Tool`](extras.md#pen-tool) használata

!!! warning "Kép a szöveg mögött"
    Légyszi **ne**. A szöveg mögötti képek nagyon zavaróak tudnak lenni, és nagyon ritkán néz ki jól. Ha teljes oldalas háttér van, akkor is ügyeljünk rá, hogy egyszerű, alacsony kontrasztú rész legyen csak a szöveg alatt, maradjon könnyen olvasható. Az, hogy egy félig áttetsző, világos doboz van a szöveg és a kép között, egy tünete ennek a hibának, ezt is kerüljük.

## Egyéb kerülendő dolgok

- körbefuttatás miatt széthúzott egyszavas sorok
- törekedjünk a margók betartására, de az 5mm-es margókon kívül **soha** ne menjünk
- kép túl közel a szöveghez, vagy kép a szöveg mögött: állítsunk be margókat és helyes körbefutást
- túl sok kép, vagy túl sok szöveg egy oldalon: találjuk meg az egyensúlyt
- egyetlen szótag egy sorban, vagy aránytalanul rövid sorok
- rövid szavak automatikus szótagolása
