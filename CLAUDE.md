# Instrukce pro Clauda

Tento repozitář je obecná logika. Osobní údaje uživatele jsou v samostatném soukromém repozitáři `nutrition-data` (typicky vedle tohoto, `../nutrition-data`). Do tohoto repozitáře nikdy nezapisuj nic osobního: míry, zdravotní údaje, jména, ceny konkrétních nákupů, jídelníčky. Komunikuj v jazyce uživatele (výchozí čeština).

## Při sestavování týdenního jídelníčku

Když má uživatel restauraci s menu zveřejněným až v týdnu (`restaurants.md` v datech), sestavuje se jídelníček i košík až po zveřejnění menu, ne předem.

1. Přečti `framework/` v tomto repozitáři.
2. V data repozitáři přečti `profil.md`, poslední soubor v `jidelnicky/` včetně poznámek, co fungovalo, poslední záznam v `mereni/`, `roadmap.md` a `restaurants.md`.
3. Spočítej denní cíle podle `framework/01-cile-a-vypocty.md` a aktuální fáze z profilu.
4. Vyber produkty primárně z `produkty.yaml` v datech. U nových produktů na Rohlíku ověř složení podle vylučovacího seznamu v profilu a nutriční hodnoty, pak je do `produkty.yaml` přidej.
5. Ověř ceny a dostupnost na Rohlíku, mění se (slevy, vyprodané zboží).
6. Hlídej limity z `framework/02-zlata-pravidla.md`, rozpočet a trvanlivost. Oběd v restauraci a hotový oběd z Rohlíku jsou rovnocenné a pevný počet restauračních dnů neexistuje; postup je v `framework/03-struktura-dne.md`, část Restaurace v plánu.
7. Projdi každé jídlo, jestli v něm není něco z mrazáku (`skladovani: mrazak` v `produkty.yaml`, pečivo, mražené ovoce, maso). Do tabulky „Z mrazáku“ v jídelníčku napiš, kdy to vytáhnout (navázané na předchozí jídlo) a záchranu, když se zapomene, podle `framework/03-struktura-dne.md`. Co je potřeba v pondělí, patří na neděli večer.
8. Jídelníček ulož do dat jako `jidelnicky/RRRR-MM-DD.md` (datum pondělí) podle `sablony/jidelnicek.md`.
9. Pokud to profil zapíná, vytvoř jídla v kalendáři podle `framework/03-struktura-dne.md`, část Jídla v kalendáři. Před vytvořením ukaž uživateli přehled událostí. Když vznikají uprostřed týdne, nejdřív se zeptej, jestli dosavadní dny šly podle plánu; prohozené jídlo posune i ty další.
10. Košík naplň přes Rohlík MCP. Objednávku nikdy nepotvrzuj, to dělá uživatel.

## Při změně pravidel

- Obecné pravidlo, které by platilo pro kohokoli → upravit `framework/`.
- Osobní preference nebo parametr → upravit `profil.md` v datech.
- Jídelníčky jsou historické záznamy, zpětně se neupravují.

Co se při práci pokazilo nebo překvapilo a proč pravidla vypadají, jak vypadají, je v `LESSONS.md`.
