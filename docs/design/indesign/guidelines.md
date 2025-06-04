# Tördelés az Impulzusnál

!!! example "Átdolgozás alatt"
    A tördelés régi folyamata (avagy minden egy nagy dokumentumban) nem kimondottan bizonyosult hatékonynak az együttes munkát illetően, emiatt szerettem volna újítani ezen.

    Kezdésképp elkezdjük használni a könyv (`Book`) funkciót, és újítunk a kiinduló fájlokon.

## Mappaszervezés

!!! danger ""
    TODO

### Lock fájlok

![](img/lockfile.png)

Ha ehhez hasonló lock fájlokat látsz, akkor azt a dokumentumot éppen valaki szerkeszti. Amíg be nem zárja, addig más nem fér hozzá, feleslegesen ne hagyjunk nyitva dokumentumokat.

## Kiinduló fájlok és könyvtárak

!!! danger ""
    TODO

### Rétegek

A kiinduló fájlok valószínűleg tartalmazni fognak rétegeket:

- **Előtér**: ami minden esetben legfelül kell legyen
- **Munkaterület**: a legtöbb szöveg és alapesetben minden, ami nem máshova megy
- **Grafikák**: képek, illusztrációk, stb.
- **Háttér**: amit mindenképpen hátra szeretnél tenni, érdemes lezárni, ami fix

## Stílusok és egységesség

Amihez csak tudunk használjunk stílusokat, mintákat, könyvtári elemeket stb.

- egyedileg kever színek helyett használjunk színmintákat és színárnyalatokat
- szöveghez használjunk bekezdésstílusokat, csak indokolt esetben formázzuk egyedileg
- ha nem találod a stílusokat vagy a palettát, ellenőrizd, hogy szinkronizálva vagy-e a könyvvel, és hogy jó kiindulófájlból dolgozol

### Impulzus könyvtár

> avagy Design Library

Ez egy `.indl` fájl, ami tartalmaz pár előre definiált elrendezést.
Nyissuk meg és tegyük ki valamelyik panelre.
Válasszuk ki a kívánt elemet és húzzuk be a dokumentumba.
Ügyeljünk, hogy illeszkedjen a margókhoz és a dokumentum széleihez!

## Képek

- körbefutás
    - szögletes képekhez kb. 3mm
    - szabad formáknál akár 5mm is, ahogy jól néz ki
- grafikákat **vektoros** formátumban (svg), ha létezik ilyen változat
- mellőzzük a díszes képkereteket
- a lekerekítés legyen egységes, vagy sehol, vagy mindenhol, de akkor ugyan annyi (jelenleg nem használunk ilyet)
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
