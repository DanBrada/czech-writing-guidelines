---
name: czech-writing-guidelines
description: "Pravidla pro české texty, které jsou formálně správné a snadno pochopitelné. Kombinuje typografickou úpravu podle ČSN 01 6910 (mezery, pomlčky, uvozovky, čísla, data, jednotky, měny, zkratky, tituly, adresy, dopisy, e-maily) se zásadami srozumitelné komunikace podle ASD-STE100 (krátké věty, činný rod, jednotná terminologie), ČSN EN ISO 20607 (návody ke strojům, bezpečnostní sdělení) a ČSN EN IEC/IEEE 82079-1 (informace pro použití, cílová skupina, struktura podle úkolů, varování). Použij vždy, když píšeš, upravuješ, překládáš do češtiny nebo kontroluješ jakýkoli český text pro čtenáře – odpovědi uživateli, dopisy, e-maily, zprávy, smlouvy, nabídky, zápisy, návody, dokumentaci, bezpečnostní pokyny, webové texty, prezentace i tabulky. Spusť ho i tehdy, když uživatel jen řekne „napiš to česky“, „oprav mi to“, „úřední dopis“, „návod“, „aby to bylo srozumitelné“ nebo „aby to bylo typograficky správně“, i když žádnou normu nezmíní."
---

# Czech writing guidelines

Skill má dvě vrstvy:

1. **Forma** – typografická a formální úprava podle ČSN 01 6910:2014 a navazujících doporučení Ústavu pro jazyk český (části 1–13 níže).
2. **Srozumitelnost** – zásady řízeného jazyka a informací pro použití podle ASD-STE100, ČSN EN ISO 20607 a ČSN EN IEC/IEEE 82079-1 (část 14 níže, podrobně v `references/srozumitelnost.md`).

Vše je shrnuto vlastními slovy, není to přepis norem. V hraničních jazykových případech ověř v Internetové jazykové příručce (prirucka.ujc.cas.cz), která je s ČSN 01 6910 sladěná a volně dostupná.

Proč na tom záleží: čeština má vlastní typografické konvence, které se liší od angličtiny (jiné uvozovky, mezera před procentem a jednotkou, desetinná čárka, tečka za řadovou číslovkou…). Text psaný „anglicky“ působí neprofesionálně. Modely navíc přenášejí anglické zvyky (`"quotes"`, `5%`, `1,000.50`, `10-15`) a mají sklon k dlouhým souvětím, trpnému rodu a opisům („je třeba provést kontrolu“) – přesně k tomu, co normy srozumitelnosti zakazují. Proto si obě vrstvy před odevzdáním vědomě zkontroluj.

## Pracovní postup

1. Ujasni si, **kdo bude číst a co s textem chce udělat** (část 14, bod „Čtenář“). Podle toho zvol rozsah a odbornost.
2. Napiš text obsahově. Nejdůležitější informaci dej na začátek, postupy do číslovaných kroků, varování před kroky, kterých se týkají.
3. Projdi text podle `references/checklist.md` – nejdřív srozumitelnost (délka vět, činný rod, terminologie), pak formu (čísla, jednotky, pomlčky, uvozovky, mezery).
4. Pokud generuješ soubor (DOCX, HTML, Markdown), vkládej skutečné typografické znaky (`„“ – × … ’ °`) a nezlomitelné mezery (U+00A0, v HTML `&nbsp;`), ne ASCII náhražky. Tabulka znaků je v `references/znaky.md`.
5. U obchodních dopisů a e-mailů dodrž strukturu z části 12. U návodů, dokumentace a bezpečnostních pokynů si přečti `references/srozumitelnost.md` celý.

---

## 1. Interpunkce a mezery

- Tečka, čárka, středník, dvojtečka, otazník, vykřičník se **přisazují** k předchozímu slovu, za nimi následuje jedna mezera. Nikdy dvě mezery.
- Závorky a uvozovky se přisazují k textu uvnitř: `(takto)`, `„takto“`. Mezera je vně.
- Tečka za větou v závorce: pokud je celá věta v závorce, tečka je uvnitř. `Přišel pozdě (jako obvykle).` ale `(Přišel pozdě.)`
- Za nadpisem se tečka nepíše.
- Výpustka je jeden znak `…` (U+2026), ne tři tečky. Při vynechání části slova se přisazuje (`ne…`), při vynechání slov se odděluje mezerou (`chtěl jsem … ale nešlo to`). Na konci věty se další tečka nepřidává.

## 2. Spojovník, pomlčka, mínus

Tři různé znaky, tři různé významy. Toto je nejčastější chyba.

| Znak | Název | Kdy |
|---|---|---|
| `-` (U+002D) | spojovník | uvnitř slov a spojení, **bez mezer**: `česko-slovenský`, `Frýdek-Místek`, `bude-li`, `e-mail`, `ping-pong`, `2015-2016` jen v ISO datu |
| `–` (U+2013) | pomlčka | oddělení částí věty (**s mezerami**): `Praha – hlavní město – …`; ve významu „až“, „versus“, „od–do“ (**bez mezer**): `10–15 °C`, `Praha–Brno`, `Sparta–Slavia`, `s. 5–12` |
| `−` (U+2212) | mínus | matematické znaménko: `−5 °C`, `3 − 2 = 1` |

Zásady:
- Pomlčka ve významu „až“ se píše bez mezer jen mezi jednoslovnými výrazy. Jakmile je jeden z výrazů víceslovný nebo obsahuje mezeru, piš pomlčku s mezerami, nebo raději slovo „až“: `1. 9. – 30. 9. 2026`, `20 až 25 °C`.
- Pomlčka nesmí stát na začátku řádku (nezlomitelná mezera **před** ní), pomlčka bez mezer nesmí být na konci ani začátku řádku.
- Anglický „em dash“ `—` (U+2014) se v češtině zpravidla nepoužívá.
- Spojovník na konci řádku při dělení slova se opakuje na začátku dalšího řádku (`česko-|-slovenský`) – v textovém procesoru se řeší nedělitelným spojovníkem.

## 3. Uvozovky a apostrof

- České uvozovky: dole otevírací `„` (U+201E), nahoře uzavírací `“` (U+201C). Tedy `„takto“`, ne `"takto"` ani `“takto”`.
- Vnořené uvozovky: `‚takto‘` (U+201A / U+2018).
- Přípustné jsou i `»takto«` (francouzské, jen pokud jsou v dokumentu jednotně).
- Interpunkce: pokud je v uvozovkách celá věta, tečka je uvnitř: `Řekl: „Přijdu zítra.“` Pokud je citován jen úsek věty, tečka je vně: `Nazval to „omylem“.`
- Apostrof (odsuvník) je `’` (U+2019), ne `'`: `pad’`, `O’Brien`.
- Znak `"` a `'` používej jen jako značku palce a stopy (`5' 10"`) nebo v kódu.

## 4. Čísla

- **Desetinná čárka**, ne tečka: `3,14`, `0,5 %`.
- Skupiny tisíců se oddělují **nezlomitelnou mezerou**: `1 250 000`, `12 500`. Čtyřmístná čísla lze psát bez mezery (`1250` i `1 250`), ale v jednom dokumentu jednotně. Nikdy tečka ani čárka jako oddělovač tisíců.
- Mezera se nepíše v letopočtech (`2026`), PSČ (`418 01` má vlastní tvar), číslech popisných, kódech.
- Řadová číslovka má tečku a za ní mezeru: `5. místo`, `20. století`, `v 21. patře`.
- Číslice a slovo se spojují spojovníkem bez mezer: `5násobný` (bez spojovníku) nebo `pětinásobný`; `20procentní` / `20%` / `dvacetiprocentní`.
- Rozmezí pomlčkou bez mezer: `10–15`, `1 000–2 000`. Netlač do rozmezí kombinaci `od 10–15`.
- Násobení a rozměry: znak `×` (U+00D7) s mezerami: `3 × 4 m`, `20 × 30 cm`. Ne písmeno `x`.
- Matematické operátory `+ − = < >` s mezerami z obou stran: `2 + 3 = 5`. Znaménko u čísla se přisazuje: `+5`, `−12`.
- Poměr a měřítko: dvojtečka s mezerami `1 : 50 000`; skóre bez mezer `3:1`.
- Zlomky: `1/2`, `¾`; lomítko bez mezer.
- Telefonní čísla: po trojicích, mezinárodní předvolba `+420`: `+420 601 234 567`. Nedělit na konci řádku.
- Čísla účtů: `123456789/0100`. IČO: `12345678` (bez mezer). DIČ: `CZ12345678`.

## 5. Procenta, jednotky, značky

Klíčové pravidlo: **mezera = samostatné podstatné jméno, bez mezery = přídavné jméno.**

- `5 %` = pět procent; `5%` = pětiprocentní (`5% sleva` = pětiprocentní sleva; `sleva 5 %`). Stejně `‰`.
- Jednotky vždy s (nezlomitelnou) mezerou: `10 kg`, `25 km/h`, `230 V`, `3 h`, `15 min`, `2 s`, `1 000 Kč`.
- Teplota: `20 °C` (mezera před `°C`), ale úhlový stupeň bez mezery `45°`.
- Přídavné jméno z čísla a jednotky bez mezery: `10kg pytel`, `12V baterie`, `5km běh`.
- Paragraf: `§ 12`, `§ 12 odst. 1 písm. a)`. Více paragrafů `§ 12 a 13`, rozsah `§ 12–15`. Ne `§§`.
- Ampersand `&` s mezerami: `Novák & syn`.
- Značky `©`, `®`, `™`: `© 2026 Firma, s. r. o.`; `®` a `™` se přisazují ke slovu.
- Znak `#` se v české typografii nepoužívá jako „číslo“; piš `č. 5`.

## 6. Měny

- Značka měny **za** číslem s mezerou: `1 250,50 Kč`, `100 €`, `50 $`.
- Kód měny podle ISO se píše rovněž s mezerou, v běžném textu za číslem (`1 250,50 CZK`); v účetních sestavách a tabulkách je přípustný i před číslem (`CZK 1 250,50`).
- Haléře: `1 250,50 Kč`; celé koruny `1 250 Kč` (ne `1 250,- Kč` – tento tvar norma nedoporučuje, i když je v praxi rozšířený; pokud ho uživatel výslovně chce, použij `1 250,– Kč` s pomlčkou).
- Milion, tisíc slovně: `2,5 mil. Kč`, `500 tis. Kč`, `3 mld. Kč`.

## 7. Datum a čas

- Základní tvar: `8. 9. 2026` – den a měsíc s tečkou, **mezery mezi všemi částmi**, bez úvodních nul. Nezlomitelné mezery.
- Slovní tvar: `8. září 2026`. Tento tvar je vhodný v dopisech a slavnostních textech.
- V tabulkách, formulářích a databázích: `08.09.2026` (bez mezer, s nulami) nebo ISO `2026-09-08`.
- Nikdy nemíchej tvary v jednom dokumentu. Nepoužívej anglické `9/8/2026` ani `September 8, 2026`.
- V dopise se datum uvádí bez slova „dne“: `Bílina 8. 9. 2026` nebo `V Bílině 8. 9. 2026`.
- Čas: hodiny a minuty odděluje tečka (`9.30 h`, `14.05`) nebo dvojtečka (`09:30`, `14:05`) – v dokumentu jednotně. Sekundy vždy dvojtečkou: `09:30:15`.
- Časové rozpětí: `9.30–10.15` (pomlčka bez mezer). Doba trvání: `3 h 20 min`.
- Rozmezí let: `2020–2026`; školní rok `2025/2026`.
- Století: `20. století`, `ve 30. letech`.

## 8. Zkratky a tituly

- Zkratky tvořené prvními písmeny více slov: **každá část má tečku a mezeru** (nezlomitelnou): `a. s.`, `s. r. o.`, `č. p.`, `t. r.`, `s. p.`, `v. r.`, `p. s.`
- Ustálené zkratky: `tj.`, `tzv.`, `např.`, `atd.`, `apod.`, `popř.`, `příp.`, `resp.`, `tzn.`, `č.`, `str.`/`s.`, `tel.`, `ul.`, `nám.`, `mj.`, `ř.`, `odst.`, `písm.`, `přel.`, `pozn.`
- Bez tečky: `viz`, `cca` (obojí není zkratka v pravém slova smyslu), značky jednotek (`kg`, `km`, `h`, `min`, `s`), iniciálové zkratky (`ČSN`, `ÚNMZ`, `ČR`, `DPH`, `IČO`).
- Za zkratkou na konci věty se tečka nezdvojuje: `…atd.`
- Zkratka a číslo se nedělí na konci řádku (nezlomitelná mezera): `č. 5`, `s. 12`, `tel. 601 …`.
- **Akademické tituly před jménem** (tečka a mezera): `Ing. Jan Novák`, `Mgr. Eva Malá`, `doc. PhDr. Karel Král, CSc.` Zkratka `doc.` a `prof.` malým písmenem.
- **Tituly za jménem** se oddělují čárkou: `Ing. Jan Novák, Ph.D.`, `MUDr. Anna Nová, MBA`. Pozor: `Ph.D.` se píše bez mezery.
- Pokud jméno s tituly stojí uprostřed věty, čárka i za titulem: `Přednášel Ing. Novák, Ph.D., o normách.`
- Zkratka `p.` (pan/paní) se v obchodní korespondenci nepoužívá – piš `pan`, `paní`.

## 9. Nezlomitelné mezery (U+00A0)

Nezlomitelnou mezeru vlož všude, kde by zalomení řádku vytvořilo osamocený krátký prvek. Norma to vyžaduje u těchto případů:

- za **jednopísmennými předložkami** `k`, `s`, `v`, `z`, `o`, `u` (neslabičné `k, s, v, z` závazně; `o, u` a spojky `a, i` doporučeně) – `v Praze`, `s Petrem`, `k tomu`;
- mezi číslem a jednotkou/značkou: `10 kg`, `5 %`, `§ 12`, `20 °C`;
- uvnitř čísel oddělených mezerami: `1 250 000`, `+420 601 234 567`;
- v datu: `8. 9. 2026`;
- ve zkratkách typu `a. s.`, `s. r. o.`, `č. p.`, `tj.` + slovo;
- mezi titulem a jménem, zkratkou jména a příjmením: `Ing. Novák`, `J. Novák`;
- mezi řadovou číslovkou a slovem: `5. místo`, `20. století`;
- před pomlčkou v roli vsuvky, aby nezačínala řádek.

V HTML je to `&nbsp;`, v LaTeXu `~`, ve Wordu Ctrl+Shift+mezerník, v Markdownu vlož přímo znak U+00A0.

## 10. Adresy

- Pořadí: jméno / firma, ulice a číslo, PSČ a obec, případně stát.
- Číslo popisné a orientační lomítkem: `Hlavní 123/4`. Bez „č. p.“, pokud nejde o obec bez ulic (`Lhota 45`).
- PSČ ve tvaru `418 01` (trojčíslí, mezera, dvojčíslí), za ním **jedna mezera** a název obce: `418 01 Bílina`. (Starší zvyk dvou mezer už norma nepředepisuje.)
- V řádkové adrese v textu se části oddělují čárkami: `Novák & syn, s. r. o., Hlavní 123/4, 418 01 Bílina`.
- Adresát v dopise: bez teček na koncích řádků, zarovnaný vlevo, název firmy a právní forma přesně podle rejstříku.

## 11. Struktura dokumentu, nadpisy, zvýrazňování, seznamy

- Nadpisy: bez tečky na konci. Číslované nadpisy `1`, `1.1`, `1.1.2` – za posledním číslem tečka není: `2.3 Platební podmínky`. Mezi číslem a textem nadpisu mezera (v procesoru tabulátor).
- Odstavce se oddělují buď mezerou mezi odstavci, nebo odsazením první řádky – ne obojím.
- Zvýrazňování: **tučné písmo** pro klíčové výrazy, *kurzíva* pro cizí slova, názvy děl a citace. Podtržení se nepoužívá (v elektronických textech znamená odkaz). Prostrkání a VERZÁLKY jen výjimečně. Nekombinuj více způsobů zvýraznění najednou.
- Zarovnání: vlevo (do praporku) nebo do bloku; při bloku zapni dělení slov, jinak vznikají „řeky“.
- Seznamy: každá položka začíná stejně (velké nebo malé písmeno jednotně). Jsou-li položky větami, končí tečkou. Jsou-li to úseky věty navazující na uvozovací větu, končí čárkou (poslední tečkou), nebo se interpunkce vynechá – v dokumentu jednotně. Za odrážkou/číslem následuje mezera nebo tabulátor.
- Tabulky: číslo a název nad tabulkou (`Tabulka 1 – Přehled nákladů`), jednotky v záhlaví sloupce (`Cena (Kč)`), čísla zarovnaná doprava podle desetinné čárky, text vlevo. Prázdná buňka se označí pomlčkou.
- Obrázky a grafy: popisek pod obrázkem (`Obrázek 3 – Schéma zapojení`).
- Poznámky pod čarou: odkazová číslice se píše horním indexem a stojí **za** interpunkčním znaménkem, pokud se vztahuje k celé větě, a před ním, pokud se vztahuje ke slovu.
- Stránkování: číslo stránky v záhlaví nebo zápatí, první strana dopisu bez čísla.

## 12. Dopisy a e-maily

### Obchodní / úřední dopis

Doporučená posloupnost (norma popisuje i předtisky, ale pro běžnou praxi stačí):

```
[Odesílatel – hlavička: název, adresa, IČO, kontakt]

[Adresát – jméno / firma
 ulice a číslo
 PSČ obec]

Váš dopis značky / ze dne   Naše značka   Vyřizuje / linka   Místo, datum
(nebo jednodušeji:)         Bílina 8. 9. 2026

Věc: Nabídka servisních služeb        ← tučně, bez tečky; nebo jen předmět bez slova „Věc“

Vážená paní inženýrko,                 ← oslovení, čárka, text dále malým písmenem

text dopisu, odstavce oddělené prázdným řádkem.
Odkazy na přílohy v textu.

S pozdravem                            ← bez čárky

[vlastnoruční podpis]

Ing. Jan Novák
obchodní ředitel

Příloha: Ceník 2026                    ← nebo „Přílohy: 2“ / výčet
Na vědomí: Ing. Malá
```

Zásady:
- Oslovení v 5. pádě, správným titulem/funkcí: `Vážený pane doktore,` `Vážená paní ředitelko,` `Vážený pane Nováku,` (pane Novák je také přípustné, ale méně vhodné). Firmu/neznámou osobu: `Vážené dámy a pánové,` nebo `Vážení,`.
- Po oslovení s čárkou pokračuj **malým** písmenem: `Vážený pane Nováku,\n\ndovolujeme si Vám nabídnout…` Po vykřičníku velkým (méně obvyklé).
- Zdvořilostní `Vy`, `Vám`, `Váš`, `Vaše` s **velkým V** vždy, když oslovuješ adresáta (jednotlivce i firmu). `Tykání` (`Ty`, `Tvůj`) také velkým v dopisech.
- `S pozdravem` / `S úctou` / `Se srdečným pozdravem` – bez čárky, na vlastním řádku; pod tím jméno a funkce. Nepiš `S pozdravem,`.
- Datum bez „dne“, místo bez „V“ je přípustné: `Bílina 8. 9. 2026`.
- Předmět (Věc) stručně, tučně, bez tečky.
- Přílohy uváděj na konci, nikoli v textu jako „viz příloha“ bez seznamu.

### E-mail

- Předmět: výstižný, bez tečky, s velkým písmenem na začátku.
- Oslovení a pozdrav jako u dopisu; méně formální varianty: `Dobrý den, pane Nováku,` – pak text malým písmenem na novém řádku. `Dobrý den,` samotné je přípustné.
- Zdvořilostní Vy velkým i v e-mailu.
- Podpis: jméno, funkce, firma, telefon, web – bez zdrobnělin a smajlíků v obchodní komunikaci.
- Odpověď: `S pozdravem` / `Hezký den` / `Děkuji a přeji hezký den` na vlastním řádku bez čárky.

## 13. Časté anglicismy k odstranění

| Špatně | Správně |
|---|---|
| `"text"` / `“text”` | `„text“` |
| `10-15 %` | `10–15 %` |
| `5%`, `20°C` | `5 %`, `20 °C` |
| `1,000.50` / `1.000,50` | `1 000,50` |
| `1250,- Kč` | `1 250 Kč` |
| `9/8/2026`, `8.9.2026` (v běžném textu) | `8. 9. 2026` |
| `9:30 AM` | `9.30 h` / `09:30` |
| `Ing.Novák`, `Ing. Novák Ph.D.` | `Ing. Novák, Ph.D.` |
| `s.r.o.`, `a.s.` | `s. r. o.`, `a. s.` |
| `tzn.,` `atd..` | `tzn.`, `atd.` |
| `S pozdravem,` | `S pozdravem` |
| `Vážený pane Nováku, Dovolujeme si…` | `Vážený pane Nováku,\n\ndovolujeme si…` |
| `3x4`, `3 x 4` | `3 × 4` |
| `...` | `…` |
| `—` (em dash) | `–` (pomlčka) |
| `vám`, `váš` v dopise | `Vám`, `Váš` |
| `10kg` (substantivně) | `10 kg` |
| `§12`, `§§ 5–8` | `§ 12`, `§ 5–8` |
| `1:1` (poměr) | `1 : 1` |

## 14. Srozumitelnost (ASD-STE100, ISO 20607, IEC/IEEE 82079-1)

Tyto zásady platí pro **každý text určený uživateli**, včetně běžné odpovědi v chatu. U návodů, dokumentace a bezpečnostních pokynů si přečti podrobnou verzi v `references/srozumitelnost.md`.

**Čtenář**
- Než začneš psát, věz, kdo čte a co chce udělat (rozhodnout se, nastavit, opravit, pochopit). Piš pro nejméně zkušeného pravděpodobného čtenáře.
- Odděl „co udělat“ od „proč to tak je“. První dej napřed.

**Věty**
- Věta s instrukcí do ~20 slov, popisná věta do ~25 slov, odstavec do ~6 vět a jedno téma.
- Jedna věta = jedna myšlenka. Jedna instrukce = jedna věta.
- **Činný rod, rozkazovací způsob v postupech, přítomný čas v popisech**: „Stiskněte Start“, ne „Je třeba, aby bylo stisknuto tlačítko Start“.
- Podmínka před instrukcí: „Pokud kontrolka bliká, vypněte zařízení.“
- Vyškrtni vycpávky: „jednoduše“, „stačí“, „samozřejmě“, „v podstatě“, „je třeba říci“, „v neposlední řadě“.

**Slova**
- Jedno slovo = jeden význam, jedna věc = jedno slovo v celém textu. Nestřídej synonyma (tlačítko / klávesa / ovladač).
- Krátká, konkrétní, běžná slova. „Použijte“, ne „aplikujte“. Nehromaď více než tři přívlastky před podstatným jménem.
- Zkratky rozepiš při prvním výskytu. Odborný termín při prvním výskytu krátce vysvětli, není-li čtenář odborník.
- Povinnost = **musí / musíte**, zákaz = **nesmí / nesmíte**, doporučení = **doporučujeme**, možnost = **můžete**. Nepoužívej „měl by“ pro skutečnou povinnost. V instrukcích nepoužívej „atd.“ a „apod.“ – vyjmenuj vše.

**Struktura**
- Nejdůležitější nejdřív: odpověď, výsledek, rozhodnutí; zdůvodnění potom.
- Člen text podle **úkolů čtenáře**, ne podle logiky systému. Nadpisy říkají, co čtenář v části najde („Jak změnit heslo“, ne „Správa identit“).
- Číslovaný seznam pro kroky s pořadím, odrážky pro položky bez pořadí. Jeden krok = jedna činnost.
- U každého postupu: předpoklady (co je potřeba předem) → kroky → jak poznat úspěch → co dělat při chybě.
- Názvy tlačítek, menu a ovládacích prvků přesně tak, jak je uživatel vidí, jednotně zvýrazněné (tučně).

**Bezpečnostní a varovná sdělení**
- Odstupňovaná signální slova: **NEBEZPEČÍ** (způsobí smrt/těžké zranění) → **VAROVÁNÍ** (může způsobit smrt/těžké zranění) → **UPOZORNĚNÍ** (lehké/střední zranění) → **OZNÁMENÍ** / POZOR (škoda na věcech, datech) → Poznámka / Tip (bez bezpečnostního významu). Používej je jednotně; nedevalvuj je.
- Každé varování má čtyři části v tomto pořadí: **signální slovo → druh nebezpečí → následek → jak se mu vyhnout**. Stojí **před krokem**, kterého se týká.
- Totéž platí v chatu: když v radě hrozí úraz, ztráta dat, finanční nebo právní škoda, pojmenuj riziko, následek a prevenci dřív, než dáš postup – ne až v závěrečné poznámce.
- Návod ke stroji navíc obsahuje: určené použití, předvídatelné nesprávné použití, zbytková rizika, kvalifikaci obsluhy, OOPP, a bezpečnostní informace pro každou fázi životního cyklu (doprava → instalace → provoz → údržba → likvidace).

**Vizuální prvky**
- Obrázek, schéma nebo tabulka tam, kde by slovní popis byl delší nebo méně přesný. Každý obrázek má popisek a odkaz z textu.
- Barva není nikdy jediný nositel informace. Zvýrazňuj střídmě.

**Příklad přepisu**

Před: *Před tím, než bude zahájena samotná instalace, je vhodné se ujistit, že zařízení bylo odpojeno od elektrické sítě, jelikož v opačném případě by mohlo dojít k úrazu elektrickým proudem, a následně je možné přistoupit k demontáži krytu pomocí šroubováku.*

Po:
> **VAROVÁNÍ** – Nebezpečí úrazu elektrickým proudem. Dotyk s částmi pod napětím může způsobit smrt. Před demontáží krytu odpojte zařízení od sítě.
>
> 1. Odpojte zařízení od elektrické sítě.
> 2. Vyšroubujte 4 šrouby krytu křížovým šroubovákem.
> 3. Sejměte kryt.

## Referenční soubory

- `references/checklist.md` – kontrolní seznam před odevzdáním textu (srozumitelnost i forma); projdi ho vždy, když je text delší než pár vět nebo jde o oficiální dokument.
- `references/srozumitelnost.md` – podrobné zásady ASD-STE100, ISO 20607 a IEC/IEEE 82079-1: analýza čtenáře, stavba vět, struktura podle úkolů, postupy, čtyřdílná varování, terminologie, vizuální prvky, kontrola kvality. Přečti celý u návodů, dokumentace a bezpečnostních textů.
- `references/znaky.md` – tabulka typografických znaků s kódy Unicode, klávesovými zkratkami a HTML entitami; použij při generování souborů nebo když uživatel potřebuje znak sám napsat.
