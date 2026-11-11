# Typografické znaky pro české texty

| Znak | Název | Unicode | HTML | Windows (Alt) | macOS | LaTeX |
|---|---|---|---|---|---|---|
| ` ` | nezlomitelná mezera | U+00A0 | `&nbsp;` | Ctrl+Shift+mezerník (Word), Alt+0160 | Alt+mezerník | `~` |
| `„` | uvozovka otevírací | U+201E | `&bdquo;` | Alt+0132 | Alt+Shift+W | `\glqq` |
| `“` | uvozovka uzavírací | U+201C | `&ldquo;` | Alt+0147 | Alt+Shift+N (CZ) | `\grqq` |
| `‚` | vnořená otevírací | U+201A | `&sbquo;` | Alt+0130 | – | `\glq` |
| `‘` | vnořená uzavírací | U+2018 | `&lsquo;` | Alt+0145 | – | `\grq` |
| `»` `«` | francouzské uvozovky | U+00BB / U+00AB | `&raquo;` `&laquo;` | Alt+0187 / Alt+0171 | – | `\flqq \frqq` |
| `–` | pomlčka (en dash) | U+2013 | `&ndash;` | Alt+0150, Ctrl+Num− (Word) | Alt+- | `--` |
| `-` | spojovník | U+002D | `-` | klávesa | klávesa | `-` |
| `−` | mínus | U+2212 | `&minus;` | Alt+8722 (Unicode vstup) | – | `$-$` |
| `…` | výpustka | U+2026 | `&hellip;` | Alt+0133 | Alt+; | `\dots` |
| `’` | apostrof | U+2019 | `&rsquo;` | Alt+0146 | Alt+Shift+] | `'` |
| `×` | krát | U+00D7 | `&times;` | Alt+0215 | Alt+Shift+= (CZ)? / vložit | `$\times$` |
| `°` | stupeň | U+00B0 | `&deg;` | Alt+0176 | Alt+Shift+8 | `^\circ` |
| `§` | paragraf | U+00A7 | `&sect;` | Alt+0167 | Alt+6 | `\S` |
| `%` | procento | U+0025 | `%` | klávesa | klávesa | `\%` |
| `‰` | promile | U+2030 | `&permil;` | Alt+0137 | Alt+Shift+R | `\textperthousand` |
| `€` | euro | U+20AC | `&euro;` | Alt+0128, AltGr+E | Alt+Shift+2 | `\euro` |
| `©` | copyright | U+00A9 | `&copy;` | Alt+0169 | Alt+G | `\copyright` |
| `®` | registrovaná známka | U+00AE | `&reg;` | Alt+0174 | Alt+R | `\textregistered` |
| `™` | ochranná známka | U+2122 | `&trade;` | Alt+0153 | Alt+2 | `\texttrademark` |
| `‑` | nedělitelný spojovník | U+2011 | `&#8209;` | Ctrl+Shift+- (Word) | – | `\mbox{-}` |

Poznámky:
- Alt kódy na Windows vyžadují numerickou klávesnici a zapnutý NumLock.
- Ve Wordu lze zapnout automatickou náhradu `"` na české uvozovky: Soubor → Možnosti → Kontrola pravopisu → Automatické opravy → Automatické úpravy formátu při psaní → „Rovné“ uvozovky nahradit „oblými“ (při českém jazyku textu).
- V Markdownu a prostém textu vlož znaky přímo; nezlomitelná mezera je viditelná jen v editorech s vizualizací bílých znaků, proto ji po vložení zkontroluj.
- Při generování DOCX přes python-docx vkládej `\u00a0`, `\u201e`, `\u201c`, `\u2013` atd. přímo do řetězců.
