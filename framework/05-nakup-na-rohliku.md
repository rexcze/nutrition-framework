# Nákup na Rohlíku

Nákup jednou týdně, ideálně v neděli s doručením v pondělí. Ověřené produkty se ukládají do `produkty.yaml` v data repozitáři.

## Kritéria pro hotová jídla

1. Aspoň 30 g bílkovin na porci, jinak doplnit (2 vejce ≈ 13 g).
2. Zhruba do 850 kcal na porci.
3. Žádná složka z vylučovacího seznamu v profilu; kontrolovat složení, ne jen název (skrytá zelenina v omáčkách).
4. Smažená jídla a jídla s uzeninou se počítají do týdenních limitů.

Rybí hotová jídla s 30 g bílkovin na Rohlíku chyběla (stav 10/2026); ryba se dá řešit konzervou nebo steakem na grilu.

## Trvanlivost

| Položka | Jak skladovat |
| --- | --- |
| Čerstvé pečivo | hned po doručení zamrazit, rozmrazit nebo opéct (viz níže) |
| Bobulové ovoce | kupovat mražené, porci večer do lednice (viz níže) |
| Vejce natvrdo | neloupaná v lednici asi týden, lépe vařit ve dvou várkách |
| Baby mrkev | lednice, 1–2 týdny |
| Avokádo „ready to eat“ | sníst do 2–3 dnů, načaté zakrýt; hnědý povrch seškrábnout |
| Banány | pokojová teplota mimo ostatní ovoce, zralé do lednice |
| Balené maso, šunka | po otevření do 24 hodin |
| Hotová jídla | podle data spotřeby, podle něj prohodit dny |

## Mrazák a rozmrazování

Co se musí rozmrazit, se snadno zapomene vytáhnout. Proto každá zmražená věc v jídelníčku dostane připomínku „vytáhni z mrazáku“ s dostatečným předstihem.

**Kdy je věc zmražená:** koupená mražená, nebo se hned po doručení zamrazí (pečivo, maso na později). V `produkty.yaml` má `mrazak: true`, dobu rozmrazování `rozmrazit_h` a místo `rozmrazit_kde`.

**Orientační doby** (když produkt nemá vlastní údaj):

| Co | Kde | Předstih |
| --- | --- | --- |
| Pečivo | na lince v sáčku | 2–3 h; nebo bez rozmrazení rovnou do toastovače či trouby |
| Bobulové ovoce | v lednici | 8–12 h, tedy večer na ráno; do jogurtu jde i napůl zmražené |
| Plátky hotového masa, uzená ryba | v lednici | 8–12 h |
| Syrové maso a ryba | v lednici | 12–24 h, větší kusy 24 h |
| Mražené hotové jídlo | rovnou do trouby | bez rozmrazení, pokud obal neříká jinak |

Neznámý produkt bez údaje: **večer před jídlem po večeři do lednice**. Maso a ryba se rozmrazují v lednici, ne na lince.

**Kdy připomínka padne:** na nejbližší chvíli dne, kdy člověk stejně je v kuchyni a která dá dost času: snídaně, odpolední svačina, nebo po večeři. Vybere se nejpozdější taková chvíle, která ještě splní předstih. Nikdy ne na dobu spánku; když by vycházela na noc, posune se na večer předtím. Věci, které jdou do trouby nebo toastovače rovnou zmražené, připomínku nedostanou.

**Jak se zapíše:** pravidelné každodenní vytahování jako vlastní řádek v denní tabulce jídelníčku (ve chvíli, kdy se má vytáhnout), jednorázové v sekci „Z mrazáku“ po dnech. Každá připomínka říká co, kolik, kam a na které jídlo. Řádek pro první den týdne se týká večera před ním, tedy neděle.

## Postup

1. Sestavit jídelníček, z něj košík.
2. U zmražených věcí doplnit připomínky na vytažení z mrazáku.
3. Ověřit dostupnost a ceny (slevy se mění).
4. Zkontrolovat rozpočet z profilu, včetně plánovaných restaurací.
5. Objednávku potvrzuje vždy člověk, ne Claude.
