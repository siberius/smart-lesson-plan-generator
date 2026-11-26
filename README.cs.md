# Smart Prompt: Generátor výukových příprav na hodinu (v souladu s RVP)

[English](README.md)

Prompt pro učitele a studenty učitelství, který vytváří minutově rozvržené přípravy na 45minutovou nebo 90minutovou vyučovací hodinu podle modelu E-U-R s činnostními výstupy, Plánem B a hotovým pracovním materiálem.

## Spuštění

1. Otevřete soubor [cs/smart-prompt-generator-vyukovych-priprav-v-souladu-s-rvp.md](cs/smart-prompt-generator-vyukovych-priprav-v-souladu-s-rvp.md) (nebo anglickou verzi [en/smart-lesson-plan-generator.md](en/smart-lesson-plan-generator.md)).
2. Zkopírujte celý obsah souboru a vložte jej jako systémový prompt nebo první zprávu do svého AI asistenta (ChatGPT, Claude, Gemini či jiného kompatibilního nástroje).
3. Odpovězte na vstupní diagnostické otázky z Fáze 1. Stop-pojistka ve Fázi 6 zajistí, že AI při prvním vložení pouze pozdraví a položí 5 vstupních otázek z Fáze 1 bez předčasného generování.

## Funkce

Kontrola času započítává přechody a přípravu pomůcek. Každý cíl má určené procvičení, pozorovatelný doklad a kritérium úspěchu. Výstupem je editovatelný DOCX, pokud ho zvolený chat umí vytvořit. Jinak prompt žádá kopírovatelný Markdown. Tvorba souboru a chování této verze v konkrétních modelech zatím nemají doložený test.

Podnět ke kontrole rozpisu: [Lesson Plan Designer and Timing Checker](https://prompts.chat/prompts/cmuz82k2l000njy045jzh27v0_lesson-plan-designer-and-timing-checker), @f, prompts.chat (CC0 1.0).

- Přesný minutový harmonogram na 45 nebo 90 minut podle modelu E-U-R (Evokace, Uvědomění, Reflexe).
- Činnostní výstupy se slovesy chování žáka, SMART cíle a žákovsky srozumitelný cíl na tabuli.
- Cílená volba taxonomie podle povahy učiva: Bloomova kognitivní, psychomotorická pro dílny/laboratoře nebo afektivní.
- Konkrétní formativní ověření, diferenciace pro SVP a nadané žáky i realistický Plán B pro výpadek techniky či časovou rezervu.
- Povinný hotový doprovodný materiál k okamžitému použití (pracovní list, výstupní lístek nebo 3–5 úloh s klíčem v bodu 10).

## Co projekt není

Tento repozitář je specifikace promptu, nikoli databáze učebních osnov ani školní informační systém. Konkrétní školní kontext a RVP upřesňuje učitel.

## Jazyky

Anglická varianta (`en/smart-lesson-plan-generator.md`) je mezinárodní bez vazby na národní kurikula; česká varianta (`cs/smart-prompt-generator-vyukovych-priprav-v-souladu-s-rvp.md`) integruje RVP ZV/G/SOV, klíčové kompetence a kritéria ČŠI.

## Data a soukromí

Pouze statické Markdown soubory bez sběru dat, telemetrie a externích závislostí.

## Soubory

| Soubor | Účel |
|---|---|
| [cs/smart-prompt-generator-vyukovych-priprav-v-souladu-s-rvp.md](cs/smart-prompt-generator-vyukovych-priprav-v-souladu-s-rvp.md) | Česká varianta promptu |
| [en/smart-lesson-plan-generator.md](en/smart-lesson-plan-generator.md) | Anglická varianta promptu |
| [README.md](README.md) | Anglická dokumentace |
| [README.cs.md](README.cs.md) | Česká dokumentace |
| [CHANGELOG.md](CHANGELOG.md) | Historie verzí |
| [LICENSE](LICENSE) | Veřejné uvolnění CC0 1.0 Universal |

## Licence a autor

Texty promptů i dokumentace jsou uvolněny jako volné dílo pod licencí [CC0 1.0 Universal](LICENSE). Uvedení autora má informační charakter.

### Autor

**Luděk Sušický** — biolog, středoškolský a vysokoškolský učitel informatických předmětů

- E-mail: [ludek.susicky@gmail.com](mailto:ludek.susicky@gmail.com)
- X: [@ludeksusicky](https://x.com/ludeksusicky)
- LinkedIn: [Luděk Sušický](https://www.linkedin.com/in/ludek-susicky/)
- GitHub: [@siberius](https://github.com/siberius) — další vzdělávací projekty a otevřené aplikace

[Repozitář na GitHubu](https://github.com/siberius/smart-lesson-plan-generator)
