# Tin density: what the numbers actually are

A single, sourced density table for tin in the forms a working chemist meets, assembled from 59 records across 28 sources, with every disagreement between those sources recorded rather than averaged away.

## The problem

Ask five references for the density of tin and you get five answers. In this collection alone the white form appears as **7.265, 7.280, 7.289, 7.290, 7.300, 7.310 and 7.336** depending on the source, a spread of about 1 percent. That spread is not measurement noise:

- **It is not temperature.** Converting every temperature-stated sample to 20 C removed only 2.1 percent of the variance. If the sources disagreed because they measured at different temperatures, normalising would have collapsed most of it.
- **It is partly rounding.** Sources publishing two decimals average 7.2944; those publishing three average 7.2849, a 0.13 percent offset that tracks each publisher's precision rather than the sample.
- **It is partly duplication.** The 17 white-tin records contain only **8 distinct values**. Four sources reporting 7.31 are close to one observation copied four times.
- **It is partly conflation.** Grey tin (5.769) and white tin (7.287) are 21 percent apart, and secondary sources mix them. Powder apparent density (3.2) is not a metal density at all. And 7.31 is also the density of **indium**, which appears on at least one supplier sheet filed beside tin.

So the useful answer is not a single number pulled from a favourite handbook. It is a number, the form and temperature it belongs to, and the size of the disagreement behind it.

## The answer

| Form | n | Best value | Range | Spread | Confidence |
|---|---|---|---|---|---|
| beta tin, white, 20 C | 17 | **7.287** | 7.265 to 7.336 | 0.97% | high |
| alpha tin, grey, 20 C | 7 | **5.769** | 5.750 to 5.770 | 0.35% | high |
| liquid at melting point | 4 | **6.983** (primary); median of four 6.977 | 6.970 to 6.990 | 0.29% | high: primary measurement, 0.05% |
| Sn63Pb37 eutectic solder | 4 | **8.41** (median; ASM table 8.42) | 8.400 to 8.420 | 0.24% | high |
| Sn70Pb30 solder | 1 | 8.32 | - | - | medium |
| SAC305 lead-free | 3 | 7.40 | 7.370 to 7.490 | 1.62% | medium |
| Sn100C lead-free | 1 | 7.40 | - | - | medium |
| Sn96.5Ag3.5 lead-free | 1 | 7.36 | - | - | medium |
| pewter | 1 | 7.28 | - | - | medium |
| white metal | 1 | 7.28 | - | - | medium |
| tin babbitt, grades 1 to S | 5 | 7.34 to 7.75 | ladder | - | medium |
| tin powder, apparent | 2 | 3.2 | 3.20 to 3.80 | - | not a metal density |
| gamma phase, high P | 1 | 7.525 | - | - | computed only |
| delta phase, high P | 1 | 7.561 | - | - | computed only |

Uncertainty is k=2, dominated by whether a temperature is quoted: plus or minus 0.014 g/cm3 with the temperature known to 5 K, 0.042 without one.

**The strongest evidence is structural, not bibliographic.** Five X-ray unit cells for white tin give 7.2879 and 7.2885 g/cm3 from cell volume alone (rho = Z*M/(N_A*V)), reproducing the tabulated 7.287 to four significant figures. The value is not a chain of compilers repeating each other; it is what the crystal requires.

## Sources

Every value traces to one of these. Records marked excluded are kept for audit.

| Source | What it supplied | Link |
|---|---|---|
| Royal Society of Chemistry | periodic table entry, beta density | <https://periodic-table.rsc.org/element/50/tin> |
| CRC Handbook of Chemistry and Physics | inorganic compounds table, white and grey tin rows | <https://dl.icdst.org/pdfs/files/415f61e9082c7d23df09fb15605aa59d.pdf> |
| CRC Materials Science and Engineering Handbook | Table 33 tin and tin alloys (via ASM 1993); thermal expansion table | <http://nguyen.hong.hai.free.fr/EBOOKS/SCIENCE%20AND%20ENGINEERING/MECANIQUE/MATERIAUX/Crc%20Materials%20Science%20And%20Engineering%20Handbook-1928S.pdf> |
| Crystallography Open Database | five white-tin and two grey-tin unit cells, query API | <https://www.crystallography.net/cod/result?formula=Sn&format=json> |
| Wang et al., J. Phys.: Condens. Matter 15 (2003) 777 | primary liquid measurement, improved Archimedean method | <https://doi.org/10.1088/0953-8984/15/6/304> |
| Wang et al., corrigendum, J. Phys.: Condens. Matter 19 (2007) 139001 | corrected liquid temperature equation | <https://doi.org/10.1088/0953-8984/19/13/139001> |
| Deffrennes et al., J. Alloys Compd. (2022) | review, compilation of liquid datasets | <https://doi.org/10.1016/j.jallcom.2022.165675> |
| Phys. Rev. B 103, 184102 (2021) | DFT equation of state, high-pressure phases | <https://doi.org/10.1103/PhysRevB.103.184102> |
| Encyclopaedia Britannica | white and grey values; direct link blocks scripts, archived copy used | <https://www.britannica.com/science/tin> · <https://web.archive.org/web/2024id_/https://www.britannica.com/science/tin> |
| WebElements (Winter) | solid density; direct link blocks scripts, archived copy used | <https://www.webelements.com/tin/> · <https://web.archive.org/web/2024id_/https://www.webelements.com/tin/> |
| Los Alamos National Laboratory | value at STP | <https://www.lanl.gov/science-engineering/periodic-table/element/tin> |
| PubChem, compound record | density records incl. the temperature-stated grey value | <https://pubchem.ncbi.nlm.nih.gov/rest/pug_view/data/compound/5352426/JSON> |
| periodictable.com (Theodore Gray) | solid and liquid values | <https://periodictable.com/Elements/050/data.html> |
| periodic-table.org | value at STP | <https://www.periodic-table.org/tin-density/> |
| pse-info.de | alpha and beta at a stated temperature | <https://pse-info.de/en/element/Sn> |
| ChemicalBook | white, grey and liquid values | <https://www.chemicalbook.com/ChemicalProductProperty_EN_CB3190047.htm> |
| de.wikipedia, Zinn | alpha and beta both at 20 C | <https://de.wikipedia.org/wiki/Zinn> |
| Engineering Toolbox | metals density table; linear expansion range | <https://www.engineeringtoolbox.com/linear-expansion-coefficients-d_95.html> |
| Indium Corporation, tin metal PDS | alpha, beta and liquid at melting point | <https://www.indium.com/wp-content/uploads/2025/03/Commercial-Tin-Metal-PDS-98803-A4-R0-1.pdf> |
| MG Chemicals TDS 4925 | SAC305 alloy | <http://www.mgchemicals.com/downloads/tds/tds-4925.pdf> |
| MG Chemicals TDS 4860 | Sn63Pb37 alloy | <http://www.mgchemicals.com/downloads/tds/tds-4860.pdf> |
| Kester SAC305 TDS | SAC305 alloy | <https://www.kester.com/downloads?Command=Core_Download&EntryId=61810> |
| Krayden LINQ-CC SAC305 | SAC305 alloy, third maker | <https://www.krayden.com/products/linq-cc-sac305> |
| Qualitek SN63 RMA200 TDS | Sn63Pb37 alloy | <https://qualitek.com/SN63_RMA200_TDS.pdf> |
| SMD Sn100C datasheet | Sn100C and Sn63Pb37 | <https://smd-bg.com/pdf/Solder_SN100C_SN100Ce_engl.pdf> |
| Superior Flux SnAg TDS | Sn96.5Ag3.5 alloy | <https://superiorflux.com/spec/TDS.AFCW.SnAg.pdf> |
| Poudmet Sn 30GN-350 | powder apparent density to ISO 3923/1 | <https://www.poudmet.fr/uploads/produits/en/etain/EN%20FT%20Sn%2030GN-350.pdf> |
| Thermo Fisher, product 010379.36 | powder apparent density range | <https://www.thermofisher.com/order/catalog/product/010379.36> |
| CNPC Powder | manufacturer density value | <https://www.cnpcpowder.com/products/tin/76.html> |
| Biakom SN63-PB37 TDS | excluded outlier | <https://biakom.com/media/2016-02-26/SN63-PB37.pdf> |

## Composition cross-check

Alloy values were tested against a rule of mixtures using element densities from the same CRC table (Pb 11.3, Ag 10.5, Cu 8.96, Sb 6.68). Deviations under about 0.5 percent sit inside the model's own error:

| Alloy | Predicted | Measured | Deviation |
|---|---|---|---|
| Sn63Pb37 | 8.389 | 8.400 | +0.13% |
| Sn63Pb37 | 8.389 | 8.420 | +0.37% |
| Sn96.5Ag3.5 | 7.366 | 7.360 | -0.08% |
| pewter, 91 Sn 7.5 Sb 1.5 Cu | 7.258 | 7.280 | +0.30% |
| SAC305 | 7.361 | 7.370 (Kester) | +0.12% |
| SAC305 | 7.361 | 7.400 (Krayden) | +0.52% |
| SAC305 | 7.361 | 7.490 (MG Chemicals) | **+1.75%** |
| Sn100C | 7.297 | 7.400 | **+1.42%** |
| Sn70Pb30 | 8.156 | 8.320 | **+2.01%** |

## How this was built

Samples were taken from handbooks, reference tables, government databases, manufacturer datasheets and two journal publications. Each record stores the source, the retrieval route, the quoted line, the crystal form or alloy, the value, the temperature where stated, and an evidence class.

Filtration ran in five steps: unit normalisation; separation by crystal form and alloy, never pooled; median and MAD per form; robust z with exclusion above 3.5, keeping the excluded record and its reason; and evidence-class weighting where a group disagreed.

Three records are excluded: a supplier figure of 8.800 for Sn63Pb37 (robust z +12.8 against two independent 8.40 and 8.42 values), a DFT liquid value of 7.470 (a model reference density, not a measurement), and a powder range superseded by an ISO 3923/1 result. Two further documents were rejected before entry: one whose 7.31 belongs to indium rather than tin, and one giving a single figure for three different alloys.

## Limits

- No certified reference material. These are nominal values, not certified ones.
- 12 of 59 records state a temperature; the rest are silent.
- No measured high-pressure density. The gamma and delta phases appear only as computed values.
- Single-crystal anisotropy is not covered.
- The spread within a form is reported rather than hidden, so the table can be used to judge a competing figure instead of replacing one authority with another.

## Files

- DATA/tin-density.csv - all 59 records with source, route, class, value, temperature and exclusion reason.
- CARD.md - the one-page version: four numbers and three traps.

## Licence and provenance

Compiled 2026-11-27. Source values remain the property of their publishers; this compilation adds only the selection, normalisation and exclusion record. Reuse the compilation freely, cite the sources it points to.
