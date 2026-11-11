# Srozumitelná komunikace: ASD-STE100, ISO 20607, IEC/IEEE 82079-1

Shrnutí vlastními slovy. Nejde o přepis norem; jde o jejich principy přenesené do češtiny a do situace, kdy agent píše text pro uživatele (odpověď v chatu, návod, dokumentaci, zprávu, e-mail).

Obsah:
1. Kdo je čtenář (82079-1)
2. Věty a slova (STE)
3. Struktura a orientace (82079-1, 20607)
4. Postupy a instrukce (STE, 82079-1)
5. Bezpečnostní a varovná sdělení (20607, 82079-1)
6. Terminologie (všechny tři)
7. Vizuální prvky a média (82079-1, 20607)
8. Kontrola kvality

---

## 1. Kdo je čtenář

IEC/IEEE 82079-1 začíná analýzou cílové skupiny: informace jsou užitečné jen tehdy, když odpovídají znalostem, jazyku a situaci čtenáře.

- Před psaním si odpověz: **Kdo to bude číst? Co už ví? Co s textem chce udělat?** (rozhodnout se, něco nastavit, opravit chybu, pochopit princip).
- Piš pro nejméně zkušeného pravděpodobného čtenáře. Odborník přeskočí, co zná; laik se bez toho ztratí.
- Neptej se na to, co lze rozumně odvodit z kontextu, ale pokud je cílová skupina opravdu nejasná a rozdíl by změnil celý text, zeptej se jednou.
- Rozliš **informace k jednání** (co má uživatel udělat) a **informace k pochopení** (proč to tak je). Uživatel většinou chce nejdřív první; druhé nabídni odděleně, ne vpleteně do postupu.
- Přizpůsob rozsah: chat = krátce, dokument = úplně. Ale nikdy nevynechej krok nebo varování jen kvůli stručnosti.

## 2. Věty a slova (zásady STE přenesené do češtiny)

ASD-STE100 je řízený jazyk pro technickou angličtinu. Jeho slovník do češtiny přenést nelze, jeho pravidla pro stavbu vět ano.

**Délka**
- Věta s instrukcí: nejvýše asi **20 slov**. Věta popisná: nejvýše asi **25 slov**. Když je delší, rozděl ji.
- Odstavec: nejvýše asi **6 vět**, jedno téma. První věta říká, o čem odstavec je.
- Jedna věta = jedna myšlenka. Jedna instrukce = jedna věta.

**Slovesa**
- **Činný rod.** „Stiskněte tlačítko“, ne „Tlačítko musí být stisknuto“. „Systém uloží soubor“, ne „Soubor je systémem uložen“.
- Trpný rod jen tam, kde konatel opravdu není důležitý nebo známý.
- V postupech **rozkazovací způsob**: „Otevřete“, „Zkontrolujte“, „Vypněte“. Ne „Je třeba otevřít“, „Doporučuje se zkontrolovat“, „Měl by být vypnut“.
- V popisech **přítomný čas**: „Čerpadlo dodává olej“, ne „Čerpadlo bude dodávat olej“.
- Sloveso nevynechávej ani v odrážkách, pokud odrážka vyjadřuje činnost.
- Vyhni se řetězcům slovesných podstatných jmen („provedení kontroly nastavení“ → „zkontrolujte nastavení“).

**Slova**
- **Jedno slovo = jeden význam** v celém textu. Nestřídej synonyma pro stejnou věc (tlačítko / klávesa / ovladač; soubor / dokument / položka).
- Jeden význam = jedno slovo. Když jsi věc jednou pojmenoval, drž se toho i v nadpisech, tabulkách, popiscích.
- Přednost mají krátká, běžná, konkrétní slova. „Použijte“, ne „aplikujte“; „začněte“, ne „iniciujte“; „spusťte“, ne „proveďte spuštění“.
- Vyhni se slangu, žargonu, zkratkám bez vysvětlení, přenesenému významu a humoru, který nemusí čtenář sdílet.
- Nehromaď přívlastky před podstatným jménem (nejvýše tři): „nastavení výchozího síťového bezdrátového rozhraní zařízení“ → „výchozí nastavení bezdrátového rozhraní zařízení“.
- Nepoužívej „atd.“, „apod.“, „a podobně“ v instrukcích – čtenář neví, co si má domyslet. Vyjmenuj vše, nebo řekni, že výčet je příkladový.
- Pozor na slova s více významy: „případně“, „eventuálně“, „resp.“, „popř.“ – nahraď jednoznačným „nebo“, „a“, „tj.“.

**Modalita**
- Povinnost: **„musí“** / „musíte“. Ne „měl by“, „je vhodné“, „doporučuje se“, pokud jde o skutečnou povinnost.
- Zákaz: **„nesmí“** / „nesmíte“.
- Doporučení: „doporučujeme“, „lépe je“.
- Možnost: „můžete“, „lze“.
- Nemíchej: „musí“ nesmí znamenat jednou povinnost a podruhé předpoklad.

**Čísla a hodnoty**
- V instrukcích číslice, ne slova: „Počkejte 5 minut“, ne „pět minut“.
- Ke každé hodnotě jednotka a tolerance, pokud existuje: „Utáhněte na 25 N·m ± 2 N·m.“
- Podmínky před instrukcí: „Pokud kontrolka svítí červeně, vypněte zařízení.“ Ne „Vypněte zařízení, pokud kontrolka svítí červeně.“ (čtenář by mohl vypnout dřív, než dočte).

## 3. Struktura a orientace

- **Nejdůležitější nejdřív.** Odpověď, výsledek, rozhodnutí na začátku; zdůvodnění a podrobnosti potom.
- Rozděl text podle **úkolů čtenáře**, ne podle vnitřní logiky systému. „Jak změnit heslo“, ne „Modul správy identit“.
- Nadpisy říkají, co čtenář v části najde a udělá. Slovesné nebo otázkové nadpisy jsou u návodů srozumitelnější než jmenné („Připojení k síti“ / „Jak se připojit k síti“ místo „Síť“).
- Používej **jednotný vzor** pro opakující se části: každá kapitola návodu má stejnou stavbu (účel → předpoklady → postup → výsledek → co dělat při chybě).
- Delší dokument má obsah, číslované kapitoly, rejstřík nebo alespoň jasné nadpisy, aby se v něm dalo hledat. Uživatel návody nečte od začátku, ale hledá konkrétní věc.
- Informace, které čtenář potřebuje na jednom místě, dej na jedno místo. Neodkazuj přes půl dokumentu kvůli jedné hodnotě.
- Odkazy (viz kapitola X) jen tam, kde by opakování bylo dlouhé. Odkazuj přesně (číslo kapitoly, název), ne „viz výše“.
- Pro stroje a zařízení (ISO 20607) je osvědčený rámec podle **fází životního cyklu**: doprava a manipulace → instalace a uvedení do provozu → seřízení → provoz → údržba a čištění → odstraňování poruch → vyřazení a likvidace. Ke každé fázi patří vlastní bezpečnostní informace.
- U návodů ke strojům nesmí chybět: určené použití, rozumně předvídatelné nesprávné použití, zbytková rizika, požadavky na kvalifikaci obsluhy, osobní ochranné prostředky, technické údaje, kontakt na výrobce.

## 4. Postupy a instrukce

- **Číslovaný seznam** pro kroky, které mají pořadí. Odrážky pro položky bez pořadí. Nikdy nekombinuj v jednom seznamu.
- Jeden krok = jedna činnost. „Stiskněte OK a počkejte, až se rozsvítí zelená kontrolka“ jsou dva kroky.
- Před postupem uveď **předpoklady** (co musí být hotovo, jaké nástroje, jaká oprávnění, kolik času).
- Kroky formuluj v rozkazovacím způsobu v 2. osobě množného čísla (vykání): „Otevřete“, „Zadejte“, „Potvrďte“.
- U kroku uveď, **kde** se to dělá (kde je tlačítko, menu, konektor) a **jaký je očekávaný výsledek**, pokud není zřejmý: „Stiskněte Start. Kontrolka začne blikat.“
- Na konci postupu řekni, jak čtenář pozná, že uspěl, a co dělat, když ne.
- Názvy ovládacích prvků, tlačítek, položek menu piš přesně tak, jak jsou na zařízení nebo obrazovce, a jednotně zvýrazni (např. tučně): „Klepněte na **Uložit**.“
- Nepoužívej „stačí“, „jednoduše“, „samozřejmě“ – nic neříkají a čtenáře, kterému to nejde, urazí.
- Varování, které se týká konkrétního kroku, stojí **před tím krokem**, ne za ním a ne na začátku celého dokumentu jako jediné místo.

## 5. Bezpečnostní a varovná sdělení

IEC/IEEE 82079-1 a ISO 20607 (s odkazem na ISO 3864 a ANSI Z535.6) používají odstupňovaná signální slova. Českým ekvivalentem jsou:

| Signální slovo | Význam |
|---|---|
| **NEBEZPEČÍ** | bezprostřední ohrožení, které **způsobí** smrt nebo těžké zranění |
| **VAROVÁNÍ** | ohrožení, které **může** způsobit smrt nebo těžké zranění |
| **UPOZORNĚNÍ** | ohrožení, které může způsobit lehké nebo střední zranění |
| **OZNÁMENÍ** (POZOR) | riziko poškození věcí, dat nebo zařízení, bez ohrožení osob |
| **Poznámka** / **Tip** | doplňující informace bez bezpečnostního významu |

Každé varovné sdělení má **čtyři části** v tomto pořadí:

1. **Signální slovo** (výrazně, jednotně, případně s piktogramem).
2. **Druh nebezpečí** – co hrozí (elektrický proud, horký povrch, ztráta dat).
3. **Následek** – co se stane, když čtenář nedbá (úraz, popálení, nevratné smazání).
4. **Jak se mu vyhnout** – konkrétní příkaz.

Příklad:

> **VAROVÁNÍ** – Nebezpečí úrazu elektrickým proudem. Dotyk se svorkami pod napětím může způsobit smrt. Před otevřením krytu odpojte zařízení od sítě a ověřte nepřítomnost napětí.

Zásady:
- Varování musí být tam, kde ho čtenář potřebuje: u příslušného kroku. Souhrnná kapitola „Bezpečnostní pokyny“ na začátku ho nenahrazuje, jen doplňuje.
- Používej stejné signální slovo pro stejnou závažnost v celém dokumentu. Nepoužívej „VAROVÁNÍ“ na věci, které jen znepříjemní práci; devalvuje to opravdová varování.
- Varování je krátké a konkrétní. Neobsahuje postup, jen to, co je nutné k odvrácení nebezpečí.
- Piktogramy podle ISO 7010 (výstražné trojúhelníky, zákazové kruhy, příkazové modré kruhy) tam, kde se dokument tiskne nebo zobrazuje na zařízení. V textovém chatu piktogramy nahraď signálním slovem.
- Zbytková rizika (ta, která konstrukce neodstranila) musí být v návodu vyjmenována – uživatel má právo je znát.

**V chatu:** když radíš s něčím, kde hrozí úraz, ztráta dat, finanční škoda nebo právní riziko, použij stejnou logiku: pojmenuj riziko, jeho následek a jak se mu vyhnout, a to **dřív**, než dáš postup. Nedávej to do závěrečné poznámky.

## 6. Terminologie

- Veď si (v hlavě nebo v dokumentu) **slovníček**: každý pojem má jeden český termín, jednu definici a případně anglický ekvivalent.
- Termín, který se objeví poprvé, krátce vysvětli, pokud čtenář nemusí být odborník: „firmware (vestavěný software zařízení)“.
- Zkratky rozepiš při prvním výskytu: „programovatelný logický automat (PLC)“. V delším dokumentu přidej seznam zkratek.
- Nepřekládej ustálené názvy tlačítek a menu, pokud je zařízení nemá v češtině; piš je přesně tak, jak je uživatel uvidí, a případně přidej český popis v závorce.
- Když existuje zavedený český termín (Terminologická databáze ČSN, oborové normy), použij ho; nevymýšlej vlastní.
- Konzistence platí i napříč médii: tentýž termín v návodu, na štítku stroje, v softwaru a v e-mailu podpory.

## 7. Vizuální prvky a média

- Obrázek, schéma nebo tabulka tam, kde by slovní popis byl delší nebo méně přesný (umístění součástí, zapojení, srovnání variant).
- Každý obrázek má popisek, co ukazuje, a v textu se na něj odkazuje. Obrázek bez textu není návod.
- Tabulky pro data, která se čtou po sloupcích (parametry, srovnání, chybové kódy → příčina → řešení).
- Zvýraznění (tučné, rámečky, barvy) používej střídmě a jednotně; když je tučně půl stránky, není tučně nic.
- Barva nikdy není jediný nositel informace (barvoslepí čtenáři, černobílý tisk).
- Písmo dostatečně velké pro podmínky použití: v tištěném návodu ne pod 9–10 bodů, na štítku stroje ještě větší; kontrast textu a pozadí vysoký.
- Pokud návod doprovází více médií (tisk, PDF, obrazovka zařízení, video), musí být obsahově shodná a musí být jasné, které je závazné.

## 8. Kontrola kvality

Před odevzdáním si polož tyto otázky (odpovídají požadavkům 82079-1 na ověřování informací pro použití):

1. Může čtenář podle textu **skutečně vykonat** úkol, aniž by potřeboval něco dalšího?
2. Je každá věta s instrukcí do 20 slov, v činném rodě, v rozkazovacím způsobu?
3. Používám pro každou věc v celém textu jen jedno pojmenování?
4. Jsou varování před příslušnými kroky a mají všechny čtyři části?
5. Je nejdůležitější informace na začátku?
6. Vyškrtl jsem vycpávky („jednoduše“, „samozřejmě“, „v podstatě“, „je třeba říci“)?
7. Jsou předpoklady, výsledek a řešení chyb u každého postupu?
8. Odpovídá délka a odbornost tomu, kdo to bude číst?

Ideální je test s reálným uživatelem: nechat ho podle textu úkol provést a sledovat, kde se zasekne. Když to není možné, čti text jako někdo, kdo o tématu nic neví.
