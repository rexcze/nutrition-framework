# Instrukce pro Clauda

Tento repozitář je obecná logika. Osobní údaje uživatele jsou v samostatném soukromém repozitáři `nutrition-data` (typicky vedle tohoto, `../nutrition-data`). Do tohoto repozitáře nikdy nezapisuj nic osobního: míry, zdravotní údaje, jména, ceny konkrétních nákupů, jídelníčky. Komunikuj v jazyce uživatele (výchozí čeština).

## Při sestavování týdenního jídelníčku

1. Přečti `framework/` v tomto repozitáři.
2. V data repozitáři přečti `profil.md`, poslední soubor v `jidelnicky/` včetně poznámek, co fungovalo, poslední záznam v `mereni/` a `roadmap.md`.
3. Spočítej denní cíle podle `framework/01-cile-a-vypocty.md` a aktuální fáze z profilu.
4. Vyber produkty primárně z `produkty.yaml` v datech. U nových produktů na Rohlíku ověř složení podle vylučovacího seznamu v profilu a nutriční hodnoty, pak je do `produkty.yaml` přidej.
5. Ověř ceny a dostupnost na Rohlíku, mění se (slevy, vyprodané zboží).
6. Hlídej limity z `framework/02-zlata-pravidla.md`, rozpočet a trvanlivost.
7. U každé zmražené věci (`mrazak: true` v `produkty.yaml`, nebo co se má po doručení zamrazit) naplánuj připomínku „vytáhni z mrazáku“ podle `framework/05-nakup-na-rohliku.md`, část Mrazák a rozmrazování. U nového produktu doplň do `produkty.yaml` `mrazak`, `rozmrazit_h` a `rozmrazit_kde`; když dobu neznáš, použij výchozí „večer před jídlem do lednice“ a napiš to do poznámky.
8. Jídelníček ulož do dat jako `jidelnicky/RRRR-MM-DD.md` (datum pondělí) podle `sablony/jidelnicek.md`.
9. Košík naplň přes Rohlík MCP. Objednávku nikdy nepotvrzuj, to dělá uživatel.

## Při změně pravidel

- Obecné pravidlo, které by platilo pro kohokoli → upravit `framework/`.
- Osobní preference nebo parametr → upravit `profil.md` v datech.
- Jídelníčky jsou historické záznamy, zpětně se neupravují.
