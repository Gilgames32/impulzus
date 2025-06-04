# Hozzájárulás

Nyiss egy [issue](https://github.com/Gilgames32/impulzus/issues/new)-t, vagy csináld magad:

1. Forkold a repót.
2. Add hozzá, amit szeretnél.
3. Nyiss egy [pull requestet](https://github.com/Gilgames32/impulzus/compare).

## Segédanyag

A markdown fájlok szerkesztéséhez találsz [egy rövid útmutatót](markdown.md).

Ha új tartalmat szeretnél hozzáadni, akkor a `docs/` mappában a megfelelő almappában hozd létre a fájlt, ez határozza meg az URL-ben az elérési útvonalat is. Hogy el lehessen érni az oldalsó sávról, keresd meg az `mkdocs.yml` fájlban a `nav` részt, majd add hozzá az oldal nevét és elérési útvonalát.

### Fordítás

> python szükséges hozzá

1. célszerű egy virtuális környezetet létrehozni (`.venv`)
2. telepítsd a függőségeket: `pip install -r requirements.txt`
3. elindítani az `mkdocs serve` paranccsal tudod, a weboldalt a http://127.0.0.1:8000/impulzus/index.html címen éred el
4. ++ctrl+c++-vel tudod leállítani a szervert
