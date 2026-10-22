# Poučení

Co se při používání frameworku pokazilo nebo překvapilo a co s tím. Pravidla samotná jsou ve `framework/` a v `CLAUDE.md`, tady jsou důvody.

## Sestavování jídelníčku

**Pokyn „zamrazit“ bez kroku „vytáhnout“ nefunguje.**
První jídelníček říkal jen „rohlíky hned zamrazit“ a večeře pak počítala s rohlíky, které byly ještě zmražené. Na rozmrazení si člověk sám nevzpomene, navíc stará poznámka „rozmrazit večer“ byla pro večeři pozdě.
Proto má jídelníček nahoře tabulku „Z mrazáku“: každé vytažení je navázané na předchozí jídlo a každá mražená věc má záchranu, když se zapomene (`framework/03-struktura-dne.md`).

**Upozornění v kalendáři jen tam, kde je potřeba jednat.**
Jídla v kalendáři pomáhají jako přehled, ale upozornění ke každému jídlu by bylo kolem 30 týdně a začala by se odklikávat i ta důležitá. Uživatel nejdřív chtěl upozornění jen u kroků přípravy, pak přidal svačiny, protože se na ně zapomíná jíst.
Upozornění proto dostává událost s krokem z mrazáku a jídla, která vyjmenuje profil; ostatní jídla jsou v kalendáři potichu.

**Kalendář uprostřed týdne vychází z toho, co se opravdu snědlo, ne z plánu.**
Události na zbytek týdne vznikly podle původního plánu, ale jedno jídlo už se předtím prohodilo. Načaté balení tak bylo v kalendáři jako „první půlka“ a další obědy se posunuly.
Před vytvořením událostí uprostřed týdne se zeptat, jestli dosavadní dny šly podle plánu, a posun zapsat do poznámek jídelníčku.

**Počet restauračních obědů se nestanovuje předem.**
Uživatel dosud chodil na oběd do restaurace každý den, protože nevařil. První návrh s restaurací jako pevným bodem by to jen potvrdil. Chtěl flexibilitu: restaurace a hotový oběd z Rohlíku jsou rovnocenné a vybírá se podle menu, ceny a zbytku týdne, bez minima i maxima.
Menu je známé až v pondělí, takže první nápad kupovat v neděli zásobu hotových obědů na jistotu nahradil lepší: jídelníček a objednávku dělat až po zveřejnění menu a koupit jen to, co se opravdu bude jíst.

## Nástroje

**Kalendář přidává výchozí upozornění, pokud se výslovně nevypne.**
Kalendář měl nastavené výchozí upozornění 10 minut předem. Události vytvořené bez nastavení upozornění by ho dostaly a „tichá“ jídla by pípala taky.
U událostí bez upozornění proto výchozí upozornění vypínat (v Google Kalendáři `useDefaultReminders: false`) a po vytvoření je zkontrolovat výpisem.
