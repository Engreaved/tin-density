# Tin density: the card

One page. Every number below is computed from the [CSV](DATA/tin-density.csv); the full table with the verbatim quote and link for each row is in the [README](README.md), and the workbook is [DATA/tin-density.xlsx](DATA/tin-density.xlsx).

## The numbers that matter

| Use | Density (g/cm3) | Basis |
|---|---|---|
| **White tin (beta), 20 C** | **7.287** | 18 records from 17 sources, range 7.265 to 7.336; +/- 0.014 at k=2 with the temperature stated, +/- 0.042 without |
| **Grey tin (alpha), 20 C** | **5.769** | 8 records from 8 sources, range 5.750 to 5.770 |
| **Liquid at melting** | **6.983** | 6 sources, primary measurement at 0.05 percent; median 6.9865 |
| **Sn63Pb37 solder** | **8.40** | 8 sources, range 8.340 to 8.420, three distinct values |
| **SAC305** | **7.40** | 6 sources; two of them give 7.49 and 7.50, and a rule of mixtures predicts 7.361 |
| **Sn100C** | 7.40 | 3 sources, all agreeing |
| **Sn96.5Ag3.5** | 7.36 | one maker; mixtures give 7.366 |
| **Pewter, white metal** | 7.28 | one ASM table each |
| **Tin babbitt, grades 1 to S** | 7.34 to 7.75 | 6 records, two publishers |
| **Tin powder, apparent** | 3.2 to 3.8 | bulk powder, not the metal density |

## What to watch for

- **SAC305 does not agree with itself.** Four sources sit at 7.370 to 7.400, two at 7.490 and 7.500, and the mixtures prediction of 7.361 follows the four. The 7.40 quoted here is that cluster, not an average of all six.
- **Grey and white tin are different metals for density purposes.** 5.769 against 7.287 is a 21 percent gap; anything that quotes one as the other is wrong.
- **Powder apparent density is not a material constant.** It depends on the measurement method, so it is listed and kept out of the metal values.
- **Every record keeps its quote.** No value in this table is here without a line of text on a page that says it.

## Files

| File | What it is |
|---|---|
| `README.md` | every record with its source, quote and link |
| [DATA/tin-density.xlsx](DATA/tin-density.xlsx) | three sheets: at a glance, all records with filters, excluded |
| [DATA/tin-density.csv](DATA/tin-density.csv) | the same rows as plain text |

## Limits

No certified reference material; these are nominal values. Only 15 of 75 records state a temperature. No measured high-pressure density. Six of eight categories fall short of ten independent sources, and that shortfall is stated rather than filled.
