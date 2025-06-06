# Exportálás

## Exportálás előtt

`Preflight` ellenőrzés. Alsó sor színes karika melleti nyíl, vagy ++ctrl+alt+shift+f++.
Erre figyeljünk, ha ilyen hiba marad benne az semmiképp sem jó.

Csinálhatunk saját preflight profilt is, ha még nincsen. Hamburger menü, `Define Preflight Profiles...`, majd `+`.

- `COLOUR`
    - `Colour Spaces and Modes Not Allowed`
        - válasszunk ki mindent ami nem CMYK (helyzetfüggő)
    - `[Registration] applied`
- egyéb finomságok ízlés szerint

Ellenőrizzük a színeket és előnézetet! `View > Proof Setup` után `View > Proof Colours` vagy ++ctrl+y++.

### Adatok ellenőrzése

- borítón az évfolyam római számmal, szám arab számmal
- 2\. oldalon az adatok stimmelnek

!!! info "Fájlnév"
    A fájl neve kövesse az alábbi konvenciót: `Impulzus_[évfolyam]_[szám:02]_[olvszerk|print|issu|...]_[próbálkozás:03].pdf`
    
    Például: `Impulzus_50_01_print_001.pdf`

## PDF exportálás olvasószerkesztésre

!!! tip "Emlékeztető"
    Könyvet ne a nyomtató ikonnal exportáld, hanem a hamburgermenüben lévő `Export Book to PDF...` menüponttal.

Ez csak egy előnézet, szóval nem baj, ha a képek minősége alacsonyabb.
Ami viszont fontos, hogy kétoldalas exportot csináljunk.

- `General`
    - `Adobe PDF Preset`: `High Quality Print`
    - `Compatibility`: `Acrobat 4 (PDF 1.3)`
    - `Pages > Export As`: `Spreads`

Ha esetleg túl nagy lenne a fájl:

- `Compression`
    - `Colour Images` és `Grayscale Images`
        - `Image Quality`: `Medium` de ezzel az értékkel lehet játszadozni


## PDF exportálás a nyomdának

!!! danger "Nyomdafüggő"
    Minden esetben úgy exportálj, ahogy a nyomdád elvárja!

!!! danger "CMYK"
    Ügyeljünk rá, hogy mindenhol (főleg a képeknél) CMYK színmódot használjunk!

Nálunk ez az alábbi lépéseket jelenti:

- `General`
    - `Adobe PDF Preset`: `Press Quality`
    - `Compatibility`: `Acrobat 4 (PDF 1.3)`
- `Marks and Bleeds`
    - `Marks`
        - [x] `Crop Marks`
        - [ ] `Bleed Marks`
        - [x] `Registration Marks`
        - [x] `Colour Bars`
        - [x] `Page Information`
    - az `Offset` és a `Bleed` minden irányban legyen annyi, amennyit a dokumentumban is használtunnk (5mm)
    - [x] `Include Slug Area`
- `Output`
    - `Colour`
        - `Colour Conversion`: `No Colour Conversion`
        - `Profile Inclusion Policy`: `Don't Include Profiles`
- `Advanced`
    - `Transparency Flattener`: `High Resolution`
