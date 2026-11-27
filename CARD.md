# Tin density: the card

One page. For the full sheet see `TIN-DENSITY-FINAL.md`; machine-readable rows in `database.csv`.

## The four numbers

| Use | Density | How sure |
|---|---|---|
| **White tin (beta), 20 C** | **7.287 g/cm3** | 8 distinct values from 17 sources, +/- 0.014 if you state the temperature |
| **Grey tin (alpha), 20 C** | **5.769 g/cm3** | 7 sources, temperature stated by two of them |
| **Liquid at melting** | **6.99 g/cm3** | 3 sources, +/- 0.02, measurement just above mp |
| **Sn63Pb37 solder** | **8.41 g/cm3** | 4 sources, median; ASM table 8.42, mixtures agree to 0.4% |

Lead-free solders sit at 7.36 to 7.40 (Sn96.5Ag3.5 7.36, SAC305 7.37, Sn100C 7.40). Pewter 7.28. Tin babbitt 7.34 to 7.75 by grade.

## Three traps

**7.31 is not a second value.** It is 7.287 rounded to three figures. The 0.32% step would need 47 K of thermal expansion; it is a rounding artefact, not a temperature effect.

**Powder is not metal.** Apparent density 3.2 to 3.8 g/cm3 (ISO 3923/1) is bulk powder with air between the grains. Substituting it for metal density is an error of more than half.

**7.31 g/cm3 is also the density of indium.** One supplier document in this survey carried that number for indium metal on a tin-adjacent sheet. Check the element, not just the number.

## Which form

Mass and volume of a solid tin part at room temperature: use 7.287. If the part has been cold for a long time below 13.2 C and may have transformed, use 5.769, and remember the transformation is slow and volume-increasing. Melting or casting calculations: use 6.99 above the melting point.

## How this was built

51 samples from 31 sources: handbooks, reference tables, government databases, manufacturer datasheets, one journal paper. Median and MAD per crystal form, robust z as the exclusion test, three records excluded with reasons kept. Composition cross-checks on six alloys. No certified reference material was available, so these are nominal values, not certified ones.
