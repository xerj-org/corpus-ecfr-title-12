# eCFR Title 12 — Banks and Banking (corpus mirror)

Pinned text mirror of the **Code of Federal Regulations Title 12 (Banks and Banking)**,
built for the [XERJ Corpus Hub](https://github.com/xerj-org/xerj/tree/corpus-hub)
as reference-retrieval material for "what does the regulation actually say"
questions.

- Source (single bulk XML): https://www.govinfo.gov/bulkdata/ECFR/title-12/ECFR-title12.xml
- Downloaded: 2026-10-02 · amendment date in the source XML: see PROVENANCE.txt
- Shape: one plain-text file per CFR section (§) or appendix, grouped per part
  (`parts/part-<N>/sec-<id>.txt`), each with a title/part/subpart breadcrumb.
  Produced by `tools/xerj-code/hub/nonit/split_ecfr.py` in the xerj repo.
- Pin: the commit of this repository IS the snapshot; re-snapshotting is a new
  commit, never a force-push.

## Licence

Works of the U.S. federal government, including CFR text published by GPO, are
in the **public domain** (17 U.S.C. § 105; government edicts are not
copyrightable). GPO imposes no restrictions on bulk-data redistribution.
No attribution is legally required; the source link above is kept for
provenance.
