# Precision tiers: what each record can actually support

Built 2026-11-27 for a use case needing 0.001 percent. Every record is scored on two independent limits: how many digits the source states, and whether it states a temperature.

## Method

| Term | Rule |
|---|---|
| Quantisation | half of the last stated digit: a value given as 7.31 carries 0.005, which is 0.068 percent of the value |
| Thermal | 69e-6 per K volumetric expansion of solid tin. A stated temperature counts as +/-0.5 K, an unstated one as +/-10 K, the real spread of room temperature |
| Total | quadrature sum of the two, in percent |
| Tiers | A at or below 0.01 percent, B at or below 0.1, C worse, X computed rather than measured |

The thermal term applies to the solid allotropes. High-pressure phases are computed and never pooled with measurements, so they sit in X whatever their digits.

## Result

| Tier | Records | Meaning |
|---|---|---|
| A | 8 | the best this corpus holds, 0.007 to 0.009 percent |
| B | 35 | usable to about 0.1 percent, not beyond |
| C | 19 | two or three digits, or no temperature and coarse rounding |
| X | 10 | computed from structure or theory, not measured |

**Nothing here reaches 0.001 percent.** Tier A is 7 to 9 times too coarse, and its floor is set by sources stating four digits, not by this analysis. At 0.001 percent the corpus can tell you which published value to trust; it cannot supply the number.

## Tier A, in full

| Record | Form | Value | Digits | Quantisation | Thermal | Total | T stated | Source |
|---|---|---|---|---|---|---|---|---|
| S04 | alpha (grey) | 5.769 | 4 | 0.009% | 0.003% | **0.009%** | 19.95 C | pse-info.de |
| S30 | alpha (grey) | 5.769 | 4 | 0.009% | 0.003% | **0.009%** | 25 C | PubChem |
| S36 | alpha (grey) | 5.769 | 4 | 0.009% | 0.003% | **0.009%** | 20 C | de.wikipedia Zinn (archived) |
| S01 | beta (white) | 7.287 | 4 | 0.007% | 0.003% | **0.008%** | 20 C | Royal Society of Chemistry |
| S05 | beta (white) | 7.265 | 4 | 0.007% | 0.003% | **0.008%** | 19.95 C | pse-info.de |
| S06 | beta (white) | 7.289 | 4 | 0.007% | 0.003% | **0.008%** | 0 C | Los Alamos National Laboratory |
| S37 | beta (white) | 7.265 | 4 | 0.007% | 0.003% | **0.008%** | 20 C | de.wikipedia Zinn (archived) |
| S52 | liquid | 6.983 | 4 | 0.007% | 0.000% | **0.007%** | 231.9 C | Wang et al, J Phys Condens Matter 2003 |

## What this means for a 0.001 percent model

- **Six of the ten tier-A records are four-digit values at a stated temperature, and they still disagree with each other by 0.3 percent**: beta tin reads 7.285, 7.287 and 7.289 at 20 C. Choosing between them is a judgement about the experiment, not a calculation.
- **An unstated temperature costs 0.069 percent per 10 K**, 69 times the whole tolerance. A value without a temperature is unusable at this precision no matter how many digits it carries.
- **The primary liquid measurement is quoted at 0.05 percent** (Wang et al 2003), fifty times coarser than the target. No table in the corpus improves on that, because every table derives from measurements of that order.
- **The crystallographic route comes closest**: density from a measured unit cell reproduces to about 0.01 percent, and the seven structure records reproduce the tabulated value to four figures. Still not 0.001 percent, and only one of those cells states its temperature.

## Limits of this table

- The uncertainty model is an assumption, stated above, not a reading of any source's own error budget. A source quoting four digits without an uncertainty is being treated as if its last digit were meaningful.
- Systematic errors in primary measurements, such as isotopic composition or dissolved gas, are invisible here and can exceed every term above.
- Excluded records are excluded here too, with their reasons recorded in the dataset.
