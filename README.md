# Tuklaty v číslech

Neoficiální přehled hospodaření, majetku, pozemků, zastupitelstva a projektů obce Tuklaty
(místní části Tuklaty a Tlustovousy, okres Kolín) sestavený výhradně z veřejně dostupných dat.

**Nejde o oficiální výstup obce Tuklaty ani o výpis z jejích účtů.** Závazné jsou vždy původní
dokumenty, na které web odkazuje.

## Zdroje dat

- Web a úřední deska obce Tuklaty (zápisy zastupitelstva, závěrečné účty, rozpočty, zpravodaj)
- Monitor státní pokladny (Ministerstvo financí)
- Český statistický úřad (demografie, sčítání, bytová výstavba), volby.cz
- ČÚZK: RÚIAN, nahlížení do katastru, ortofoto a archivní ortofoto
- Registr smluv, Hlídač státu (CEDR / IS ReD), profil zadavatele na e-zakazky.cz, SFDI
- Záznamy zasedání zastupitelstva na YouTube kanálu obce

## Licence podkladů

Mapové podklady a ortofoto © ČÚZK, licence [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
Fyzické osoby u pozemkových převodů jsou anonymizované.

## Struktura

- `index.html` – celá stránka (bez sestavovacího kroku)
- `data/` – data stránky a mapové vrstvy (GeoJSON)
- `tiles/` – dlaždice ortofota (Web Mercator, 2048 px)
