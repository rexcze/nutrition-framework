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
| Čerstvé pečivo | hned po doručení zamrazit, rozmrazit podle sekce Z mrazáku nebo opéct |
| Bobulové ovoce | kupovat mražené, porci večer předem do lednice |
| Vejce natvrdo | neloupaná v lednici asi týden, lépe vařit ve dvou várkách |
| Baby mrkev | lednice, 1–2 týdny |
| Avokádo „ready to eat“ | sníst do 2–3 dnů, načaté zakrýt; hnědý povrch seškrábnout |
| Banány | pokojová teplota mimo ostatní ovoce, zralé do lednice |
| Balené maso, šunka | po otevření do 24 hodin |
| Hotová jídla | podle data spotřeby, podle něj prohodit dny |

## Z mrazáku

Co se musí rozmrazit, se zapomíná vytáhnout. Proto má každý zmražený produkt v `produkty.yaml` dobu rozmrazování a jídelníček z ní počítá připomínky „vytáhni z mrazáku“.

- Připomínka se váže na jídlo, které už v rozvrhu je („při večeři vytáhni…“), ne na hodinu. Na jídlo se nezapomíná, takže nese i připomínku.
- Maso, ryby a hotová jídla se rozmrazují jen v lednici, ne na lince.
- Kde to jde, uvést i záchranu pro případ, že se zapomene (opéct z mrazu, ohřát z mrazu).
- Zmražené věci, které se používají rovnou z mrazu (zelenina do trouby, hotová jídla určená k ohřevu z mrazu), připomínku nepotřebují: `rozmrazit_h: 0`.

Výchozí doby, když obal nebo zkušenost neříká jinak:

| Co | Kde | Doba | Kdy vytáhnout |
| --- | --- | --- | --- |
| Pečivo | na lince v sáčku | 1–2 h | při předchozím jídle; záchrana: opéct z mrazu v toastovači |
| Bobulové ovoce, porce | lednice | 6–8 h | večer předem; záchrana: rovnou do jogurtu, za 15 min povolí |
| Maso, ryba, porce do 0,5 kg | lednice | 12–24 h | večer předem, na oběd i na večeři |
| Maso nad 0,5 kg, hotové jídlo v bloku | lednice | 24 h | ráno předchozího dne |

## Postup

1. Sestavit jídelníček, z něj košík a připomínky Z mrazáku.
2. Ověřit dostupnost a ceny (slevy se mění).
3. Zkontrolovat rozpočet z profilu, včetně plánovaných restaurací.
4. Objednávku potvrzuje vždy člověk, ne Claude.
