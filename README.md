# Stravovací framework

Systém pravidel, jak jíst bez každodenního rozhodování a skoro bez vaření. Určený pro rekompozici (méně tuku, víc svalů) a pro lidi, pro které je příprava jídla věčný boj. Nákupy přes Rohlík.cz, plánování s Claudem.

Framework je jen logika. Osobní údaje (míry, preference, jídelníčky) patří do samostatného, soukromého repozitáře s daty.

## Dva repozitáře

| Repozitář | Viditelnost | Obsah |
| --- | --- | --- |
| `nutrition-framework` (tento) | veřejný | principy, pravidla, výpočty, šablony, instrukce pro Clauda |
| `nutrition-data` | soukromý | profil, preference, měření, jídelníčky, ověřené produkty |

Data repozitář se zakládá ze šablon ve složce `sablony/`.

## Jak to funguje

1. **Profil** v datech určuje parametry: hmotnost, cíl, fázi, co jíš a co ne, rozpočet, denní rozvrh.
2. **Framework** z nich odvodí denní čísla a pravidla.
3. **Jídelníček** se každý týden sestaví podle frameworku a profilu a uloží do dat.
4. **Měření** ukazuje, jestli to funguje, a podle něj se upravuje fáze.

## Týdenní rutina

- **Neděle:** zapsat měření, zhodnotit uplynulý týden, sestavit jídelníček a košík. Když jsou v plánu obědy v restauraci s menu zveřejněným až v pondělí, jídelníček a košík se dělají až po jeho zveřejnění.
- **Pondělí:** doručení, pečivo do mrazáku.
- **Během týdne:** jíst podle šablony, poznámky zapsat do jídelníčku.

## Struktura

```
framework/
  01-cile-a-vypocty.md      # jak z profilu spočítat bílkoviny, kalorie, cíl
  02-zlata-pravidla.md
  03-struktura-dne.md       # šablony jídel a načasování
  04-sladke-a-chute.md
  05-nakup-na-rohliku.md    # kritéria výběru, trvanlivost, postup
  06-faze.md                # rekonvalescence, udržení, rekompozice
  zdroje.md
sablony/                    # kostra data repozitáře
CLAUDE.md                   # instrukce pro Clauda
```

## Upozornění

Nejde o lékařské ani nutriční doporučení. Čísla jsou orientační odhady a pokyny lékaře mají vždy přednost.
