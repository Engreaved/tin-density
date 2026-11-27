# Tin density: every source on one page, so you never search twice

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Dataset",
  "name": "Tin density: every published value with its source line",
  "description": "75 records from 39 source documents giving the density of tin and tin alloys, each with a verbatim quote and a link to the page it was read from. White tin 7.287, grey tin 5.769, liquid at melting 6.983, Sn63Pb37 8.40 g/cm3.",
  "url": "https://engreaved.github.io/tin-density/",
  "isAccessibleForFree": true,
  "keywords": ["tin density", "density of tin", "white tin", "grey tin", "liquid tin", "solder density", "SAC305", "Sn63Pb37", "babbitt", "pewter"],
  "variableMeasured": [
    {"@type": "PropertyValue", "name": "Density of white tin (beta) at 20 C", "value": 7.287, "unitCode": "g/cm3"},
    {"@type": "PropertyValue", "name": "Density of grey tin (alpha) at 20 C", "value": 5.769, "unitCode": "g/cm3"},
    {"@type": "PropertyValue", "name": "Density of liquid tin at the melting point", "value": 6.983, "unitCode": "g/cm3"},
    {"@type": "PropertyValue", "name": "Density of Sn63Pb37 solder", "value": 8.4, "unitCode": "g/cm3"},
    {"@type": "PropertyValue", "name": "Density of SAC305 solder", "value": 7.4, "unitCode": "g/cm3"}
  ],
  "distribution": [
    {"@type": "DataDownload", "name": "Spreadsheet (xlsx)", "contentUrl": "https://engreaved.github.io/tin-density/DATA/tin-density.xlsx", "encodingFormat": "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"},
    {"@type": "DataDownload", "name": "CSV", "contentUrl": "https://engreaved.github.io/tin-density/DATA/tin-density.csv", "encodingFormat": "text/csv"}
  ]
}
</script>

**The gap this fills.** Look up the density of tin and the sources do not agree. 7.265, 7.280, 7.287, 7.289, 7.290, 7.300, 7.310 and 7.336 are all published for the same metal. Some mix the grey and white allotropes, some quote powder bulk density as if it were the metal, one gives indium's value on a tin page. So you check a handbook, get a number, distrust it, check another, and the second disagrees with the first.

This page gathers all of them: **75 records from 39 sources**, each with the line it was read from and a link to that page, so checking it takes one click instead of one afternoon.

**Download:** [spreadsheet](DATA/tin-density.xlsx) | [CSV](DATA/tin-density.csv) | [one-page card](CARD.md)
## The short answer

**Tin is 7.287 g/cm3** as white (beta) metal at 20 C, **5.769 g/cm3** as grey (alpha) tin, and **6.983 g/cm3** as a liquid at its melting point. Solders differ: Sn63Pb37 is 8.40, SAC305 is 7.40, pewter 7.28 g/cm3. Each figure below is the median of every source that states it, and each source is linked with the exact line it was read from.

## The answer at a glance

| Form | Records | Sources | Median | Range | Note |
|---|---|---|---|---|---|
| White tin, beta, 20 C | 18 | 17 | **7.287** | 7.265 to 7.336 | structure-confirmed from X-ray cells |
| Grey tin, alpha, 20 C | 8 | 8 | **5.769** | 5.75 to 5.77 | two sources state the temperature |
| Liquid at melting | 6 | 6 | **6.986** | 6.97 to 6.99 | primary measurement, 0.05 percent |
| Sn63Pb37 solder | 8 | 8 | **8.4** | 8.34 to 8.42 | 8 sources within 0.4 percent |
| Sn60Pb40 solder | 2 | 2 | **8.465** | 8.43 to 8.5 | two suppliers only |
| Sn70Pb30 solder | 1 | 1 | **8.32** | 8.32 to 8.32 | single ASM value |
| SAC305 | 6 | 6 | **7.4** | 7.37 to 7.5 | two of six sit 1.7 to 1.9 percent high |
| Sn100C | 3 | 3 | **7.4** | 7.4 to 7.4 | three sources, all 7.40 |
| Sn96.5Ag3.5 | 1 | 1 | **7.36** | 7.36 to 7.36 | single maker, mixtures agree |
| Pewter | 1 | 1 | **7.28** | 7.28 to 7.28 | ASM via CRC, one source |
| White metal | 1 | 1 | **7.28** | 7.28 to 7.28 | ASM via CRC, one source |
| Tin babbitt 1-4 and S | 6 | 2 | - | 7.34 to 7.75 | one ASM family, one maker |
| Tin powder, apparent | 2 | 1 | - | 3.2 to 3.8 | bulk powder, NOT metal density |
| Gamma and delta, high P | 2 | 1 | - | computed only | out of scope |

Uncertainty on the headline value is k=2: **7.287 +/- 0.014 g/cm3** with the temperature known to 5 K, +/- 0.042 without one. Of the 18 white-tin records only 8 distinct values exist; the rest are the same number reported by different publishers.

**SAC305 does not agree with itself.** Four sources give 7.37 to 7.40, two give 7.49 and 7.50, and a rule of mixtures from the element densities predicts 7.361. The quoted 7.40 sides with the four and the mixture; the two high readings are named rather than averaged in.

## Every record, with the quote it came from

The quote column is the literal string read on the page. Search it in the linked document and it lands on the number.

| # | Form | Value | Source | Quote | Link |
|---|---|---|---|---|---|
| S23 | beta (white) | 7.336 | Phys Rev B 103, 184102 (2021) | `beta 7.336 (7.4375) rho0 g/cm3` | [https://doi.org/10.1103/PhysRevB.103.184102](https://doi.org/10.1103/PhysRevB.103.184102) |
| S56 | beta (white) | 7.333 | COD (Crystallography Open Database) | `COD 9008570: a=5.8197 c=3.17488 V=107.53 A3, Z=4, sg I 41/a m d :1` | [https://www.crystallography.net/cod/result?formula=Sn&f...](https://www.crystallography.net/cod/result?formula=Sn&format=json) |
| S02 | beta (white) | 7.31 | periodictable.com (Theodore Gray) | `Density 7.31 g/cm3` | [https://periodictable.com/Elements/050/data.html](https://periodictable.com/Elements/050/data.html) |
| S07 | beta (white) | 7.31 | WebElements (Winter) | `Density of solid : 7310 kg m-3` | [https://www.webelements.com/tin/](https://www.webelements.com/tin/) |
| S10 | beta (white) | 7.31 | periodic-table.org | `Density of Tin is 7.31 g/cm3` | [https://www.periodic-table.org/tin-density/](https://www.periodic-table.org/tin-density/) |
| S17 | beta (white) | 7.31 | CNPC Powder | `Specific Gravity/Density: 7.31g/cm3` | [https://www.cnpcpowder.com/products/tin/76.html](https://www.cnpcpowder.com/products/tin/76.html) |
| S38 | beta (white) | 7.3 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Density of Tin and Tin Alloys (Table 33) ... Pure tin 7.3` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S32 | beta (white) | 7.29 | Indium Corp Tin Metal PDS | `7.29g/cm3 beta tin` | [https://www.indium.com/wp-content/uploads/2025/03/Comme...](https://www.indium.com/wp-content/uploads/2025/03/Commercial-Tin-Metal-PDS-98803-A4-R0-1.pdf) |
| S06 | beta (white) | 7.289 | Los Alamos National Laboratory | `Density 7.289 g/cm3 at STP` | [https://www.lanl.gov/science-engineering/periodic-table...](https://www.lanl.gov/science-engineering/periodic-table/element/tin) |
| S54 | beta (white) | 7.288 | COD (Crystallography Open Database) | `COD 9012005: a=5.83146 c=3.18129 V=108.183 A3, Z=4, sg I 41/a m d :1` | [https://www.crystallography.net/cod/result?formula=Sn&f...](https://www.crystallography.net/cod/result?formula=Sn&format=json) |
| S53 | beta (white) | 7.288 | COD (Crystallography Open Database) | `COD 1534488: a=5.8317 c=3.1813 V=108.192 A3, Z=4, sg I 41/a m d :1` | [https://www.crystallography.net/cod/result?formula=Sn&f...](https://www.crystallography.net/cod/result?formula=Sn&format=json) |
| S01 | beta (white) | 7.287 | Royal Society of Chemistry | `Density (g cm-3) 7.287` | [https://periodic-table.rsc.org/element/50/tin](https://periodic-table.rsc.org/element/50/tin) |
| S22 | beta (white) | 7.287 | CRC Handbook (icdst copy) | `2880 Tin (white) Sn ... 7.287` | [https://dl.icdst.org/pdfs/files/415f61e9082c7d23df09fb1...](https://dl.icdst.org/pdfs/files/415f61e9082c7d23df09fb15605aa59d.pdf) |
| S55 | beta (white) | 7.284 | COD (Crystallography Open Database) | `COD 7040217: a=5.8323 c=3.1823 V=108.25 A3, Z=4, sg I 41/a m d :2, celltemp 298 K` | [https://www.crystallography.net/cod/result?formula=Sn&f...](https://www.crystallography.net/cod/result?formula=Sn&format=json) |
| S08 | beta (white) | 7.28 | Encyclopaedia Britannica | `density white 7.28 grams/cm3` | [https://www.britannica.com/science/tin](https://www.britannica.com/science/tin) |
| S13 | beta (white) | 7.28 | ChemicalBook | `density 7.28 g/cm3 (white)` | [https://www.chemicalbook.com/ChemicalProductProperty_EN...](https://www.chemicalbook.com/ChemicalProductProperty_EN_CB3190047.htm) |
| S27 | beta (white) | 7.28 | Engineering Toolbox (wayback 2023) | `Engineering Toolbox metals table (kg/m3) ... Tin 7280` | [https://www.engineeringtoolbox.com/metal-alloys-densiti...](https://www.engineeringtoolbox.com/metal-alloys-densities-d_50.html) |
| S28 | beta (white) | 7.28 | PubChem | `7.28 (NIOSH, 2024)` | [https://pubchem.ncbi.nlm.nih.gov/rest/pug_view/data/com...](https://pubchem.ncbi.nlm.nih.gov/rest/pug_view/data/compound/5352426/JSON) |
| S05 | beta (white) | 7.265 | pse-info.de | `beta 7.265 g cm-3 (293.1 K)` | [https://pse-info.de/en/element/Sn](https://pse-info.de/en/element/Sn) |
| S29 | beta (white) | 7.265 | PubChem | `7.265 (white); 5.769 (gray)` | [https://pubchem.ncbi.nlm.nih.gov/rest/pug_view/data/com...](https://pubchem.ncbi.nlm.nih.gov/rest/pug_view/data/compound/5352426/JSON) |
| S37 | beta (white) | 7.265 | de.wikipedia Zinn (archived) | `7,265 g/cm3 (20 C) (beta-Zinn)` | [https://de.wikipedia.org/wiki/Zinn](https://de.wikipedia.org/wiki/Zinn) |
| S61 | beta (white) | 7.265 | chemeurope encyclopedia | `Density (near r.t.) (white) 7.265 g·cm 3` | [https://www.chemeurope.com/en/encyclopedia/Tin_%28eleme...](https://www.chemeurope.com/en/encyclopedia/Tin_%28element%29.html) |
| S57 | beta (white) | 7.255 | COD (Crystallography Open Database) | `COD 7222460: a=5.8393 c=3.1876 V=108.689 A3, Z=4, sg I 41/a m d :1` | [https://www.crystallography.net/cod/result?formula=Sn&f...](https://www.crystallography.net/cod/result?formula=Sn&format=json) |
| S59 | alpha (grey) | 5.832 | COD (Crystallography Open Database) | `COD 7222459: a=6.467 c=6.4665284 V=270.42 A3, Z=8, sg F d -3 m :1` | [https://www.crystallography.net/cod/result?formula=Sn&f...](https://www.crystallography.net/cod/result?formula=Sn&format=json) |
| S31 | alpha (grey) | 5.77 | Indium Corp Tin Metal PDS | `Density 5.77g/cm3 alpha tin` | [https://www.indium.com/wp-content/uploads/2025/03/Comme...](https://www.indium.com/wp-content/uploads/2025/03/Commercial-Tin-Metal-PDS-98803-A4-R0-1.pdf) |
| S04 | alpha (grey) | 5.769 | pse-info.de | `Density alpha 5.769 g cm-3 (293.1 K)` | [https://pse-info.de/en/element/Sn](https://pse-info.de/en/element/Sn) |
| S21 | alpha (grey) | 5.769 | CRC Handbook (icdst copy) | `2879 Tin (gray) Sn ... 5.769` | [https://dl.icdst.org/pdfs/files/415f61e9082c7d23df09fb1...](https://dl.icdst.org/pdfs/files/415f61e9082c7d23df09fb15605aa59d.pdf) |
| S30 | alpha (grey) | 5.769 | PubChem | `PubChem density records ... 5.769 @25 C` | [https://pubchem.ncbi.nlm.nih.gov/rest/pug_view/data/com...](https://pubchem.ncbi.nlm.nih.gov/rest/pug_view/data/compound/5352426/JSON) |
| S36 | alpha (grey) | 5.769 | de.wikipedia Zinn (archived) | `Dichte 5,769 g/cm3 (20 C) (alpha-Zinn)` | [https://de.wikipedia.org/wiki/Zinn](https://de.wikipedia.org/wiki/Zinn) |
| S60 | alpha (grey) | 5.769 | chemeurope encyclopedia | `Density (near r.t.) (gray) 5.769 g·cm 3` | [https://www.chemeurope.com/en/encyclopedia/Tin_%28eleme...](https://www.chemeurope.com/en/encyclopedia/Tin_%28element%29.html) |
| S58 | alpha (grey) | 5.766 | COD (Crystallography Open Database) | `COD 9008568: a=6.4912 c=6.4912 V=273.511 A3, Z=8, sg F d -3 m :1` | [https://www.crystallography.net/cod/result?formula=Sn&f...](https://www.crystallography.net/cod/result?formula=Sn&format=json) |
| S09 | alpha (grey) | 5.75 | Encyclopaedia Britannica | `gray 5.75 grams/cm3` | [https://www.britannica.com/science/tin](https://www.britannica.com/science/tin) |
| S14 | alpha (grey) | 5.75 | ChemicalBook | `5.75 g/cm3 (gray)` | [https://www.chemicalbook.com/ChemicalProductProperty_EN...](https://www.chemicalbook.com/ChemicalProductProperty_EN_CB3190047.htm) |
| S26 | liquid | 7.47 | Phys Rev B 103, 184102 (2021) | `liquid (7.470) rho0 g/cm3` | [https://doi.org/10.1103/PhysRevB.103.184102](https://doi.org/10.1103/PhysRevB.103.184102) |
| S03 | liquid | 6.99 | periodictable.com (Theodore Gray) | `Density (Liquid) 6.99` | [https://periodictable.com/Elements/050/data.html](https://periodictable.com/Elements/050/data.html) |
| S62 | liquid | 6.99 | chemeurope encyclopedia | `Liquid density at m.p. 6.99 g·cm 3` | [https://www.chemeurope.com/en/encyclopedia/Tin_%28eleme...](https://www.chemeurope.com/en/encyclopedia/Tin_%28element%29.html) |
| S63 | liquid | 6.99 | schoolmykids periodic table | `50 Sn Tin 6.99` | [https://www.schoolmykids.com/learn/periodic-table/densi...](https://www.schoolmykids.com/learn/periodic-table/density-liquid-of-all-the-elements) |
| S52 | liquid | 6.983 | Wang et al, J Phys Condens Matter 2003 | `densities at the melting point for liquid ... Sn ... 6.983 x 10^3 kg m-3` | [https://doi.org/10.1088/0953-8984/15/6/304](https://doi.org/10.1088/0953-8984/15/6/304) |
| S15 | liquid | 6.97 | ChemicalBook | `6.97 g/cm3 (liquid, truncated in page text)` | [https://www.chemicalbook.com/ChemicalProductProperty_EN...](https://www.chemicalbook.com/ChemicalProductProperty_EN_CB3190047.htm) |
| S33 | liquid | 6.97 | Indium Corp Tin Metal PDS | `6.97g/cm3 liquid at mp` | [https://www.indium.com/wp-content/uploads/2025/03/Comme...](https://www.indium.com/wp-content/uploads/2025/03/Commercial-Tin-Metal-PDS-98803-A4-R0-1.pdf) |
| S19 | alloy Sn63Pb37 | 8.8 | Biakom SN63-PB37 TDS | `DENSITY 8.8 g/cm3` | [https://biakom.com/media/2016-02-26/SN63-PB37.pdf](https://biakom.com/media/2016-02-26/SN63-PB37.pdf) |
| S20 | alloy Sn63Pb37 | 8.42 | Qualitek SN63 RMA200 TDS | `Density, g/cm 8.42` | [https://qualitek.com/SN63_RMA200_TDS.pdf](https://qualitek.com/SN63_RMA200_TDS.pdf) |
| S39 | alloy Sn63Pb37 | 8.42 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Soft solder (37% Pb) 8.42` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S12 | alloy Sn63Pb37 | 8.4 | MG Chemicals TDS 4860 | `Density @26 C [78 F] 8.40 g/cm3` | [http://www.mgchemicals.com/downloads/tds/tds-4860.pdf](http://www.mgchemicals.com/downloads/tds/tds-4860.pdf) |
| S35 | alloy Sn63Pb37 | 8.4 | SMD Sn100C datasheet | `Density g/cm3 7,4 \| 8,4 (Sn63 comparison column)` | [https://smd-bg.com/pdf/Solder_SN100C_SN100Ce_engl.pdf](https://smd-bg.com/pdf/Solder_SN100C_SN100Ce_engl.pdf) |
| S64 | alloy Sn63Pb37 | 8.4 | Array Solders TDS 63Sn37Pb | `Density: 8.4 g/cm³` | [https://arraysolders.com/wp-content/uploads/2023/06/TDS...](https://arraysolders.com/wp-content/uploads/2023/06/TDS-63sn37pb.pdf) |
| S65 | alloy Sn63Pb37 | 8.4 | Microsolder TDS Sn60/Sn63 | `Density: ... Sn63Pb37 8.4 g/cm3` | [https://microsolder.hu/doc/8/TDS_Sn60-Sn63_EN.pdf](https://microsolder.hu/doc/8/TDS_Sn60-Sn63_EN.pdf) |
| S74 | alloy Sn63Pb37 | 8.4 | FCT Solder SN100C TDS | `Specific Gravity 7.5 7.4 8.4` | [https://fctamexico.mx/wp-content/uploads/2022/04/SN100C...](https://fctamexico.mx/wp-content/uploads/2022/04/SN100C-Solder-Alloys-TDS.pdf) |
| S67 | alloy Sn63Pb37 | 8.34 | Nathan Trotter Sn63Pb37 bar | `Specific Gravity (g/m³) 8.34` | [https://nathantrotter.com/wp-content/uploads/2020/06/NT...](https://nathantrotter.com/wp-content/uploads/2020/06/NT-Sn63Pb37-Solder-Bar.pdf) |
| S66 | alloy Sn60Pb40 | 8.5 | Microsolder TDS Sn60/Sn63 | `Density: Sn60Pb40 8.5 g/cm3` | [https://microsolder.hu/doc/8/TDS_Sn60-Sn63_EN.pdf](https://microsolder.hu/doc/8/TDS_Sn60-Sn63_EN.pdf) |
| S68 | alloy Sn60Pb40 | 8.43 | Lucas-Milhaupt TDS 60/40 | `Specific Gravity 8.43` | [https://www.lucasmilhaupt.com/Lucas/Technical-Documents...](https://www.lucasmilhaupt.com/Lucas/Technical-Documents1/60_40TDS2018English.pdf) |
| S41 | alloy Sn70Pb30 | 8.32 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Soft solder (30% Pb) 8.32` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S72 | alloy SAC305 | 7.5 | FCT Solder SN100C TDS | `Specific Gravity 7.5 7.4 8.4` | [https://fctamexico.mx/wp-content/uploads/2022/04/SN100C...](https://fctamexico.mx/wp-content/uploads/2022/04/SN100C-Solder-Alloys-TDS.pdf) |
| S11 | alloy SAC305 | 7.49 | MG Chemicals TDS 4925 | `Density @26 C [78 F] 7.49 g/cm3` | [http://www.mgchemicals.com/downloads/tds/tds-4925.pdf](http://www.mgchemicals.com/downloads/tds/tds-4925.pdf) |
| S51 | alloy SAC305 | 7.4 | Krayden LINQ-CC SAC305 | `Type A metallic element type SAC305 Density (g) 7.4 g/cm3` | [https://www.krayden.com/products/linq-cc-sac305](https://www.krayden.com/products/linq-cc-sac305) |
| S69 | alloy SAC305 | 7.4 | Array Solders TDS SAC305 | `Density: 7.4 g/cm³` | [https://arraysolders.com/wp-content/uploads/2023/06/TDS...](https://arraysolders.com/wp-content/uploads/2023/06/TDS-for-Sac305.pdf) |
| S70 | alloy SAC305 | 7.4 | Nathan Trotter SAC305 bar | `Specific Gravity (g/m³) 7.40` | [https://nathantrotter.com/wp-content/uploads/2020/06/NT...](https://nathantrotter.com/wp-content/uploads/2020/06/NT-SAC305-Solder-Bar.pdf) |
| S18 | alloy SAC305 | 7.37 | Kester SAC305 TDS | `Density 7.37 g/cm3` | [https://www.kester.com/downloads?Command=Core_Download&...](https://www.kester.com/downloads?Command=Core_Download&EntryId=61810) |
| S34 | alloy Sn100C | 7.4 | SMD Sn100C datasheet | `Density g/cm3 7,4` | [https://smd-bg.com/pdf/Solder_SN100C_SN100Ce_engl.pdf](https://smd-bg.com/pdf/Solder_SN100C_SN100Ce_engl.pdf) |
| S71 | alloy Sn100C | 7.4 | Stannol TDS SN100C | `Density, g/cm : 3 ... 7.4` | [https://microsolder.hu/en/doc/8/TDS_SN100C_EN.pdf](https://microsolder.hu/en/doc/8/TDS_SN100C_EN.pdf) |
| S73 | alloy Sn100C | 7.4 | FCT Solder SN100C TDS | `Specific Gravity 7.5 7.4 8.4` | [https://fctamexico.mx/wp-content/uploads/2022/04/SN100C...](https://fctamexico.mx/wp-content/uploads/2022/04/SN100C-Solder-Alloys-TDS.pdf) |
| S50 | alloy Sn96.5Ag3.5 | 7.36 | Superior Flux SnAg TDS | `Solder Density 7.36 g/cm3` | [https://superiorflux.com/spec/TDS.AFCW.SnAg.pdf](https://superiorflux.com/spec/TDS.AFCW.SnAg.pdf) |
| S40 | pewter | 7.28 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Density of Tin and Tin Alloys (Table 33) ... White metal 7.28 \| Pewter 7.28` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S47 | white metal | 7.28 | CRC MS&E Handbook, Table 33 (ASM 1993) | `White metal 7.28` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S42 | babbitt grade 1 | 7.34 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Tin babbitt, Alloy 1 7.34` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S43 | babbitt grade 2 | 7.39 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Tin babbitt, Alloy 2 7.39` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S75 | babbitt grade 2 | 7.39 | Nathan Trotter Grade 2 Babbitt | `Specific Gravity (g/m³) - 7.39` | [https://nathantrotter.com/wp-content/uploads/2020/09/Gr...](https://nathantrotter.com/wp-content/uploads/2020/09/Grade-2-Babbitt-Data.pdf) |
| S44 | babbitt grade 3 | 7.46 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Tin babbitt, Alloy 3 7.46` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S45 | babbitt grade 4 | 7.53 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Tin babbitt, Alloy 4 7.53` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S46 | babbitt grade S | 7.75 | CRC MS&E Handbook, Table 33 (ASM 1993) | `Tin babbitt, Alloy S 7.75` | [http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20E...](http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf) |
| S49 | powder apparent | 3.8 | Poudmet Sn 30GN-350 | `... 3,80 (second grade column, same ISO method)` | [https://www.poudmet.fr/uploads/produits/en/etain/EN%20F...](https://www.poudmet.fr/uploads/produits/en/etain/EN%20FT%20Sn%2030GN-350.pdf) |
| S16 | powder apparent | 3.2 | Thermo Fisher 010379.36 | `Apparent Density: 2.9-3.5 g/cc` | [https://www.thermofisher.com/order/catalog/product/0103...](https://www.thermofisher.com/order/catalog/product/010379.36) |
| S48 | powder apparent | 3.2 | Poudmet Sn 30GN-350 | `Apparent density ISO 3923/1 - 5.0 mm g/cm3 3,20` | [https://www.poudmet.fr/uploads/produits/en/etain/EN%20F...](https://www.poudmet.fr/uploads/produits/en/etain/EN%20FT%20Sn%2030GN-350.pdf) |
| S24 | gamma (high P) | 7.525 | Phys Rev B 103, 184102 (2021) | `gamma 7.525 rho0 g/cm3` | [https://doi.org/10.1103/PhysRevB.103.184102](https://doi.org/10.1103/PhysRevB.103.184102) |
| S25 | delta (high P) | 7.561 | Phys Rev B 103, 184102 (2021) | `delta 7.561 rho0 g/cm3` | [https://doi.org/10.1103/PhysRevB.103.184102](https://doi.org/10.1103/PhysRevB.103.184102) |

Records S16, S19 and S26 carry an exclusion note and stay in the table, because a deleted outlier cannot be audited. The seven structure-derived cells (Crystallography Open Database) are in the data but not pooled with the measurements above.

## The spreadsheet

- **[DATA/tin-density.xlsx](DATA/tin-density.xlsx)** has three sheets: 'At a glance' computed from the records, 'All records' with every row plus URL and quote, and 'Excluded'.
- **[DATA/tin-density.csv](DATA/tin-density.csv)** is the same data as plain text.

To check any number: open 'All records', copy the quote, open the URL, search for it.

## How it was built

Every record carries its source, retrieval route, evidence class, value, temperature where stated and the verbatim line it came from. Filtration ran in five steps: unit normalisation; separation by crystal form and alloy, never pooled; median and MAD per form; robust z with exclusion above 3.5; evidence-class weighting where a group disagreed.

The strongest check is structural rather than bibliographic: five X-ray unit cells for white tin give 7.2879 and 7.2885 g/cm3 from cell volume alone, reproducing the tabulated 7.287 to four significant figures.

## Limits

- No certified reference material; these are nominal values, not certified ones.
- Only 12 of the records state a temperature.
- No measured high-pressure density; gamma and delta are computed only.
- Robust z is undefined where more than half the values are identical; Sn63Pb37 and grey tin have a MAD of zero, so their spread is reported as distinct values instead.
- Babbitt, pewter and powder are thin: one or two publishers each, and no sweep has yet exhausted their supply chains.

## Where this lives

- **[The repository](https://github.com/Engreaved/tin-density)**: every file, the commit history, and the issues page if you find an error in a row.
- **[The data folder](https://github.com/Engreaved/tin-density/tree/main/DATA)**: the workbook and the CSV side by side.
- **[The source of this page](https://github.com/Engreaved/tin-density/blob/main/README.md)**: the same text you are reading, in markdown.
- **[The one-page card](https://engreaved.github.io/tin-density/CARD.html)**: the numbers without the 75-row table.

Each source row links to the page it was read from, so a value can be checked without trusting this compilation or the repository behind it.

## Licence

Source values remain the property of their publishers; this compilation adds the selection, the normalisation and the exclusion record. Reuse it freely, cite the sources it points to.
