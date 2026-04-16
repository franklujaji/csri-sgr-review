# SESSION RESUME CARD -- 2026-04-16
# Say "continue student papers" to Hermes to reload this context

## WHERE WE ARE
Paper 1 for Kusyama Lameck is drafted and live on GitHub.
Frank is reviewing the draft before the next session continues.

## GITHUB REPO (LIVE)
https://github.com/franklujaji/csri-sgr-review
- main.tex: 947 lines, ~8,500 words, full systematic review
- references.bib: 27 entries, all verified
- elsarticle.cls v3.5 included (compiles on Overleaf or Windows LaTeX)
- Branch: main | 4 commits

## PAPER DETAILS
Title: Degradation Mechanisms and Maintenance Strategies for Composite
       Silicone Rubber Insulators in Electrified Railway Catenary Systems:
       A Systematic Review
Authors: Kusyama Lameck Kusyama (1st), Frank Lujaji (corresponding)
Target: Engineering Failure Analysis, Elsevier (IF 4.4) -- Review Article
Alt:    Reliability Engineering & System Safety, Elsevier (IF 9.4)
Format: LaTeX, elsarticle-num (numbered citations, Vancouver style)

## WHAT FRANK NEEDS TO DO BEFORE NEXT SESSION
1. Compile on Windows LaTeX or Overleaf -- check it renders cleanly
2. Read the draft -- especially:
   - Introduction (humanized)
   - Table 1 (degradation mechanisms)
   - Table 2 (diagnostic techniques)
   - Section 7 (SSA context + environmental comparison table)
   - Conclusions (numbered list -- Frank's style)
3. Flag any technical inaccuracies or sections to expand/cut

## WHAT HERMES DOES IN NEXT SESSION
Priority order:
1. Act on Frank's review comments
2. Humanize remaining sections (3-9) using 4-stage pipeline
3. Create PRISMA flow diagram (tikz or table figure)
4. Zotero: Frank needs to regenerate API key at
   https://www.zotero.org/settings/keys (current key gives 403)
   -- then Hermes adds 12 verified DOIs to ME24MM-CSRI collection
5. GitHub: create repos for Rajabu and Peter papers
6. Begin Paper 1 for Ramadhani Rajabu (ML fault prediction review)
7. Begin Paper 1 for Yared Peter (HV transmission MMS review)

## REFERENCE VERIFICATION NEEDED (Frank to fetch from SciSpace/Elicit)
These 3 entries in references.bib need proper BibTeX from Frank:
  [NEEDS-PDF] Kindersberger & Kuhl -- HC recovery kinetics (1993 ISH paper)
  [NEEDS-PDF] Chege et al. 2019 -- Kenyan SGR CBM model (IEK journal)
  [NEEDS-PDF-VERIFY-DOI] BrittleFracture2021 -- Wang et al. IEEE TDEI

If Frank searches SciSpace or Elicit for these, paste the full BibTeX
and Hermes updates references.bib + pushes to GitHub.

## KEY WORKFLOW NOTES (learned this session)
- Windows LaTeX installed -- use it for compilation, not WSL
- RStudio installed on Windows -- useful for R-based analysis figures
- Frank shares BibTeX from SciSpace/Elicit/Consensus when API search fails
- Semantic Scholar: free tier rate-limits hard after ~15 req -- always use
  Perplexity (web_search) first, S2 only for DOI confirmation
- Zotero API key: regenerate if 403 appears
- GitHub token stored in ~/.git-credentials (franklujaji)

## PAPER QUEUE (all systematic reviews, pre-data)
Paper 1 Kusyama:  csri-sgr-review              -- IN PROGRESS (v0.2)
Paper 1 Rajabu:   ml-fault-prediction-mv-review -- NOT STARTED
Paper 1 Peter:    hv-mms-transmission-review    -- NOT STARTED

## FOLDER STRUCTURE CONVENTION (use for all 3 papers)
RESEARCH/PAPERS/NN_SLUG/
  latex/       main.tex + references.bib + elsarticle files
  latex/figures/  figure files (pdf/eps/png)
  drafts/      markdown versions
  references/  downloaded PDFs
  submission/  final package
  notes/       supervisor notes, review comments
