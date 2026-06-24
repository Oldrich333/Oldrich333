# Proton Radius Triangulation Public Release Manifest

program_slug=proton-radius-triangulation
pub_id=8a42b5bf-1b76-4417-8c0c-d9cc6cc4b444
bundle_status=public_release_sanitized_from_prove_gate_confirmed_successor
target_venue=Zenodo DOI archive
assembled_at_utc=2026-06-23T20:46:03Z
source_packet=publication_inputs/2026-06-23_revised_prove_gate_packet.md
prove_gate_confirmation_ref=catalog:events/proton-radius-triangulation.md#research_finding:8290ba3bb8942b0d
supersedes_public_candidate=none
internal_evidence_bundle=build_artifacts/proton-radius-triangulation_zenodo_bundle_2026-06-23.zip
internal_evidence_bundle_sha256=f033d56716c800fd6827129889a8c2eea569ee759d6d0e6ca546ee2e4c9a7a2e

## Disposition

This is the public upload target for the June 23 Proton Radius Triangulation release. It supersedes the earlier plan to upload the full internal evidence/source bundle. The internal bundle remains preserved for audit continuity, but it contains third-party PDFs and ancillary source files and should not be uploaded publicly unless redistribution/licensing has been separately cleared.

Mechanism search remains parked/monitor-only. The publication claim is calibrated to the June 23 prove-gate successor packet: Triangulation A remains the lead no-fit support leg, Triangulation B is convention-explicit conditional support, and RF-ENV-01 is artifact-validated conditional rather than a terminal proof.

## Included Public Files

| Path | SHA256 |
| --- | --- |
| publication_inputs/2026-06-20_cross_program_stieltjes_signal.md | 50d5218e03bd19cf27796efd41c3d0f185e1101f2dd698af925884c97b235bd3 |
| publication_inputs/2026-06-20_external_falsifier_monitor.md | 41e4e046e401b69ce8a7ea48c4fd289b9c886da018cfcc7077065594bdf4b994 |
| publication_inputs/2026-06-20_regularization_envelope_output_packet.md | 3e1a69423125e3fc011a214cf1fc44c5f5b1aca989dea1eec186265b8668588b |
| publication_inputs/2026-06-23_revised_prove_gate_packet.md | 2e236199df4897558790e59939b33c040e5e41c5f27f71946f0ce72b5e06381d |
| publication_inputs/2026-06-23_public_release_readme.md | ff602b478f7f55be883d03d98a7d478cc9eee7d1ce5095850770201c0d2de3c8 |
| publication_inputs/2026-06-23_public_release_source_ledger.md | cfd70b54d83fbd793c429c10abbddda75b43cefc41ec5c5a8ff1dfd499a5f89f |
| publication_inputs/2026-06-23_public_release_zenodo_metadata.json | 283d5d03b265d53bcdd597e7c7e2c5637ca9bd8ac857745832768246ded029f3 |

## Excluded From Public Upload

The following files are present only in the internal evidence bundle and are intentionally excluded from the public upload target:

- `source_corpus/bernauer_2010_phd.pdf`
- `source_corpus/bernauer_2010_phd.txt`
- `source_corpus/bernauer_2014_tpe_extracts_RF_TPE_01.txt`
- `source_corpus/prad_thesis_wzxiong_2020.pdf`
- `source_corpus/alarcon_2020_dixeft_anc/*`

These sources are cited in `publication_inputs/2026-06-23_public_release_source_ledger.md`; the public release does not relicense or redistribute them.

## Reopen Triggers

Reopen only on MUSE, PRad-II, MAGIX/MESA, Mainz/A1 private packets, or PRad collaboration packets that change the typed source/correlation accounting. New generic mechanism generation, additional public-only clamp/sweep/envelope runs, or untyped scalar `r_p` claims do not reopen the program.

## Generated Artifacts

- `build_artifacts/proton-radius-triangulation_public_release_2026-06-23.zip`
- `build_artifacts/proton-radius-triangulation_public_release_2026-06-23.zip.sha256`
- `build_artifacts/verify_public_release_bundle.sh`

## Verification

To verify the public release bundle from any working directory, run:

```bash
programs/proton-radius-triangulation/build_artifacts/verify_public_release_bundle.sh
```

The `.sha256` sidecar stores the bundle basename, so `sha256sum -c` must be executed from the bundle directory unless this helper is used.
