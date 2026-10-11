# Axis-order controls

Presentation-only controls; no model refits, coefficient changes or new significance criteria.

X-axis options:

- Coefficient clustering preserves the archived average-linkage Euclidean order of complete 65-outcome coefficient profiles.
- Alphabetical sorts the cleaned display labels with case-insensitive English Unicode collation and numeric handling, using predictor IDs to break ties. IPA collation is a display convention, not phonetic distance.
- Phonetic uses an explicit, outcome-blind inventory order. Vowels precede consonants. Bigrams are grouped VV, VC, CV, CC, then sorted by first and second segment. Feature labels are grouped into vowel properties, consonant place and consonant manner. English g and Polish ɡ are treated alike for ordering only; their original IDs remain unchanged.

The exact segment/feature inventories are defined in audit_and_render.py. This is a fixed display convention, not a claim of a unique natural linear ordering of speech sounds.

Y-axis options:

- Original Binder order preserves the verified global Binder mapping.
- Alphabetical sorts outcome display names, not model coefficients.

The separate Binder-group selector filters the outcomes independently of either axis order. Alphabetical ordering within a selected group does not change that group's membership.

Defaults remain coefficient clustering on X and original Binder order on Y. Changing order does not change the BY/BH filter, cell-name toggle, coefficient colour scale, hover rules, scored examples or click details.
