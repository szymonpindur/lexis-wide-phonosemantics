# Word examples in the structural-control heatmaps

Display-only revision, 2026-10-11. No data, estimates, eligibility flags, penalties or multiplicity decisions are changed.

Each cell has four example groups, with up to ten words in each:

- Carriers with outcome percentile >=90.
- Carriers with outcome percentile <=10.
- Non-carriers with outcome percentile >=90.
- Non-carriers with outcome percentile <=10.

Bands refer to the full-language outcome percentile, not percentiles recomputed within carriers. Word scores appear in parentheses. An empty or short group is disclosed; score bands are never widened to fill it.

Spellings are NFC-normalized and casefolded for selection. Each group contains at most one normalized spelling and one recorded lexical family. Missing family IDs fall back to word identity; this does not establish actual linguistic independence. For each family, the most extreme qualifying score supplies its representative, with deterministic spelling/row tie-breaking.

Orthographic difference is Jaccard distance between sets of character bigrams, including start/end markers. A greedy farthest-first algorithm prioritizes the largest minimum distance to examples already selected. The first example is farthest from the candidate list's lexical median. For efficiency, pools larger than 128 are sampled at evenly spaced positions in spelling-sorted order before this diversity search.

This is a deterministic diversity heuristic, not an exact global optimum or an unbiased representative sample. Orthographic diversity is not evidence of morphological, semantic or statistical independence. Examples describe observed outcome ranks, not partialled effects or words' contributions to the adjusted coefficient.

EXAMPLE_VALIDATION.json within each language folder records selection checks for band membership, carrier status, count, unique spelling and unique recorded family. The heatmap data/filter checks remain in VALIDATION.json.
