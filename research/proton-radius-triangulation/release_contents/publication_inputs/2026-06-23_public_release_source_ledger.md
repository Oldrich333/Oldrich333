# Proton Radius Triangulation — Public Release Source Ledger

program_slug=proton-radius-triangulation
pub_id=8a42b5bf-1b76-4417-8c0c-d9cc6cc4b444
ledger_status=public_release_citation_ledger
created_at=2026-06-23

## Purpose

This ledger records the external source corpus behind the June 23 prove-gate-confirmed public packet without redistributing third-party source files in the public Zenodo archive. Local evidence hashes are retained so the internal evidence bundle can be audited, while the public release cites upstream sources and preserves copyright boundaries.

## External Source Inventory

| Source | Public reference | Local evidence path | Local SHA256 | Public release handling |
|---|---|---|---|---|
| Bernauer dissertation, Mainz elastic ep form factors | `https://download.uni-mainz.de/fb08-kpha1/doctor/bernauer.pdf` | `source_corpus/bernauer_2010_phd.pdf` | `78b3cc5cde5a163858b89990366a33fb272846126b8aa1f0e7c8f3e1e7a661b1` | Cited only; PDF not redistributed |
| Bernauer dissertation extracted text | derived from local OCR/text extraction of Bernauer dissertation | `source_corpus/bernauer_2010_phd.txt` | `f81c06c551c12b892cb90df2a3cdeb20aa908ba828fd45e902d61a9b742d6ac4` | Internal audit aid only; not redistributed |
| Mainz high-precision form factor measurement | `https://doi.org/10.1103/PhysRevLett.105.242001` | source family used by local Mainz/A1 analyses | n/a | Cited only |
| Mainz high-precision proton form factor measurement, 2014 analysis | `https://arxiv.org/abs/1307.6227` | `source_corpus/bernauer_2014_tpe_extracts_RF_TPE_01.txt` | `2243d07aceb90ae41d3b9c1ae413d1636cffcfd5de083c775b5cdbf20cb28c55` | Local extract not redistributed |
| Xiong dissertation, PRad proton radius | `https://dukespace.lib.duke.edu/dspace/handle/10161/20844` | `source_corpus/prad_thesis_wzxiong_2020.pdf` | `33dae3a043a371f95905faf4a06dafa1f124be070df70c3c89fe5236107664ea` | Cited only; PDF not redistributed |
| PRad Nature result | `https://doi.org/10.1038/s41586-019-1721-2` | source family used by PRad/source-ceiling analyses | n/a | Cited only |
| Alarcon, Higinbotham, Weiss DIχEFT paper and ancillary source family | `https://arxiv.org/abs/2002.05167` | `source_corpus/alarcon_2020_dixeft_anc/` | see internal bundle manifest | Cited only; ancillary files not redistributed |

## Source-Ceiling Caveat

The public source corpus still does not expose the full Mainz covariance/normalization/projection state or the full PRad denominator/acceptance/final-mask/control-spectra state required for total causal closure from public artifacts alone. Those private/source-complete packets remain reopen triggers, not missing files in this public release.

## Internal Bundle Linkage

The internal evidence/source bundle `build_artifacts/proton-radius-triangulation_zenodo_bundle_2026-06-23.zip` preserves the local source corpus used by the audit and verifies to SHA256 `f033d56716c800fd6827129889a8c2eea569ee759d6d0e6ca546ee2e4c9a7a2e`. It is preserved for internal audit continuity and should not be uploaded as the public release unless redistribution/licensing has been separately cleared.
