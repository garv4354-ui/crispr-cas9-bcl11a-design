# CRISPR-Cas9 guide design for BCL11A (in silico)

Design of an SpCas9 guide RNA against a coding exon of human *BCL11A* (GRCh38/hg38, chr2:60,462,265) with CHOPCHOP and CRISPOR v5.2, including primers for validation and the predicted repair profile.

Part of a four-repository project. Comparison and shared code: `genome-editors-bcl11a-comparison`. Sister repositories: `talen-bcl11a-design`, `zfn-bcl11a-design`.

## Contents
| Folder | What it holds |
|---|---|
| `docs/` | Plain-language walkthrough PDF (CRISPR_Cas9_BCL11A_walkthrough.pdf) |
| `figures/` | Figures 4-9: CHOPCHOP results, Rank 1 gene model, primers and off-target, repair model, CRISPOR map and scores |
| `data/` | Top-5 guides, Rank 1 repair prediction (Shen et al. 2018 model), primer pairs, CRISPOR scores |

## Key results (predicted)
- Rank 1 guide: `CCTGAAGGGATACCAACCCG` + PAM `CGG`, chr2:60462265 (+), GC 60%, predicted efficiency 76.99 (CHOPCHOP) / Doench '16 = 77 (CRISPOR; probably the same model).
- No predicted look-alike sites at 0-2 mismatches; 3 mismatches: 1 (CHOPCHOP) vs 4 (CRISPOR).
- Predicted frameshift outcomes 83.91% (a model share, not a fraction of cells).
- Validation amplicon: primer Pair 1, 236 bp.

## Important limits
- Everything here is a computational prediction or rule-based count. Nothing was built or tested in the laboratory.
- Tools were accessed on 24 October 2026; the genome build is GRCh38/hg38.
- Tool screenshots show a faint "Activate Windows" watermark; recapture them before journal submission.

