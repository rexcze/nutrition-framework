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
| Čerstvé pečivo | hned po doručení zamrazit, rozmrazit večer nebo opéct |
| Bobulové ovoce | kupovat mražené, porci večer do lednice |
| Vejce natvrdo | neloupaná v lednici asi týden, lépe vařit ve dvou várkách |
| Baby mrkev | lednice, 1–2 týdny |
| Avokádo „ready to eat“ | sníst do 2–3 dnů, načaté zakrýt; hnědý povrch seškrábnout |
| Banány | pokojová teplota mimo ostatní ovoce, zralé do lednice |
| Balené maso, šunka | po otevření do 24 hodin |
| Hotová jídla | podle data spotřeby, podle něj prohodit dny |

## Rozmrazování

Co se musí rozmrazit, se zapomíná. Proto každá zmražená položka v jídelníčku dostane připomínku „vytáhni z mrazáku“ s konkrétním časem.

- Připomínka se váže na jídlo, které tou dobou stejně probíhá (při večeři, při odpolední svačině), ne na hodinu. Na jídlo se nezapomene, na budík ano.
- Rozmrazovat v lednici, ne na lince, kromě pečiva a malých porcí do 2 hodin.
- Doba rozmrazování je u produktu v `produkty.yaml` (`rozmrazeni`). Když chybí, platí výchozí hodnoty:

| Položka | Kdy vytáhnout | Kam |
| --- | --- | --- |
| Pečivo | 2 hodiny před jídlem, nebo rovnou do toastovače | na linku v sáčku |
| Mražené ovoce na snídani | večer předem | do lednice |
| Maso, ryba do 300 g | večer předem (asi 12 hodin) | do lednice na talíř |
| Větší kus masa | 24 hodin předem | do lednice na talíř |
| Mražené hotové jídlo | podle obalu; bez údaje večer předem | do lednice |
| Cokoli neznámého | večer předem | do lednice |

Položka, která jde rovnou z mrazáku do trouby nebo na gril (`rozmrazeni: neni_treba`), připomínku nedostane.

## Postup

1. Sestavit jídelníček, z něj košík.
2. Ověřit dostupnost a ceny (slevy se mění).
3. Zkontrolovat rozpočet z profilu, včetně plánovaných restaurací.
4. Objednávku potvrzuje vždy člověk, ne Claude.
