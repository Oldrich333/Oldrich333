# Proton Radius Triangulation — Prove-Gate Revision Packet

program_slug=proton-radius-triangulation
pub_id=8a42b5bf-1b76-4417-8c0c-d9cc6cc4b444
packet_status=prove_gate_confirmed_rebuild_source
target_venue=Zenodo DOI archive (blocked until prove passes)
created_at=2026-06-23
predecessor=publication_inputs/2026-06-21_final_publication_packet.md
adjudication_ref=ca11404886ba4a5f8c8bbcceb9714a0b
attacker_report_ref=e859fd9c427c495cb06f461943330eee
prove_gate_confirmation_ref=catalog:events/proton-radius-triangulation.md#research_finding:8290ba3bb8942b0d

## Revision Scope

This successor packet supersedes the June 21 packet for live publication routing after prove-gate adjudication on 2026-06-23 returned `needs_revision`.

- The June 21 packet and June 22 Zenodo bundle are preserved as historical artifacts and provenance, not as live upload targets.
- This revision narrows Triangulation B and RF-ENV-01 to match independently reproduced evidence.
- No Discord manuscript, Zenodo upload, or external publication path should use the June 21 packet until this successor passes prove gate and a fresh bundle is built from it.

## Core Claim

Small-radius convergence remains strongest in Triangulation A and is conditionally supported by Triangulation B as one ordinary-H covariance-class leg. RF-ENV-01 is retained only as an artifact-validated regularization-envelope diagnostic pending an independent raw-input rerun; it is not used here as a decisive or terminal proof. The honest publication claim is source-calibrated small-radius support plus explicit scattering/source-ceiling caveats, not full terminal closure.

## Scientific Results Summary

### Triangulation A (CONFIRMED, independently reproduced)

Lattice QCD (Djukanovic et al. 2024, `0.820 +/- 0.014 fm`) plus dispersion theory (Lin-Hammer-Meissner 2022, `0.840 +/- 0.003 fm`) combine to `r_E^p = 0.83912 +/- 0.00293 fm`, matching the prior packet's `0.839(3) fm`. This is the unscaled uncorrelated inverse-variance average; a PDG/Birge-scaled presentation would widen the uncertainty to about `0.00410 fm` without moving the central value. This agrees with modern small-radius references and remains the cleanest no-fit support leg. The old `0.877 fm` reference is excluded at about `9-13 sigma` depending the averaging and reference-uncertainty convention; the simplest exact-reference calculation gives `12.91 sigma`, while the PDG/Birge-scaled presentation gives about `9.24 sigma`.

### Triangulation B (SUPPORTED_CONDITIONAL / PASS_RANK_SURVIVES)

The ordinary-H/electronic-H normal-equation audit remains qualitatively supportive, but its headline significance is convention-sensitive and should not be compressed into one invariant scalar. The six-row design matrix is full rank (`4/4`, condition number `8.40e4`), and the finite-size column is not fully absorbed by the nuisance subspace. However:

- With no priors in the full six-row model, the small-versus-large-radius separation is only `Delta chi2 = 4.71` (`2.2 sigma`).
- The machine-written summary in `rf_cl_03_output.json` gives `Delta chi2 = 69.34`, sqrt-equivalent `8.3 sigma`, for the stated `1 kHz` prior configuration.
- The same runner also emits a separate diagnostic at about `11.9 sigma` under a different objective/prior convention.

Retain Triangulation B only as one conditional ordinary-H bound-state covariance-class support leg for the small radius. Do not present it as multiple independent optical confirmations and do not collapse `8.3 sigma` and `11.9 sigma` into one publication scalar.

### RF-ENV-01 (ARTIFACT_VALIDATED_CONDITIONAL / NOT_RAW_RERUN)

The durable June 21 packet reports an `M=3` Stieltjes LP interval width of `11.63 fm` and an observed Mainz cross-method spread of `0.1285 fm`, giving a ratio of `90.51x`, rounded to `91x`. Clean-room review validated the presence of those numbers and their arithmetic in the durable artifact, but did not independently rerun the LP from raw inputs or surface a standalone raw-input driver for the envelope calculation.

Therefore RF-ENV-01 supports only the following conditional claim:

> If the stated positive-measure Stieltjes setup and source inputs are accepted, the observed spread lies inside the reported envelope.

RF-ENV-01 is not treated here as `CONFIRMED`, `decisive`, or `terminal`, and it is not used to claim that scattering is mathematically incapable of carrying a hidden physical effect under every admissible source/accounting choice.

### RF-GEN-AXIAL-02 (RULED_OUT)

The axial `G_A` transfer does not inherit the electromagnetic Stieltjes claim. The `3pi` channel lacks a first-principles sign-definite spectral measure, so same-shaped LP reasoning there is model-dependent. This remains a real lessons-forward result: the EM positivity gate is load-bearing and must not be silently generalized.

### RF-BC-02 (NARROWED)

Source-backed stacked-systematics accounting still narrows simple stacked closure as a primary explanation. Under Bernauer source semantics, determinate source-backed closure remains about `25-28%` of the `0.038 fm` split, with the residual-sign envelope spanning about `19-34%`. This continues to argue against an easy stacked-carrier explanation, but it is not identical to a terminal proof that only RF-ENV-01 can explain the residual.

## Claim Calibration

The June 21 packet overreached in three places. This revision removes that overreach explicitly.

- Triangulation B is no longer labeled `CONFIRMED` with one scalar sigma.
- RF-ENV-01 is no longer labeled `CONFIRMED`, `decisive discriminator`, or `terminal explanation`.
- The packet no longer states that A, B, and RF-ENV-01 are uniformly confirmed at the same evidentiary grade.

## Evidence Map

| Finding | Verdict | Calibrated publication use |
|---|---|---|
| Triangulation A | CONFIRMED | Lead no-fit support leg; independently reproduced |
| Triangulation B (RF-CL-03) | SUPPORTED_CONDITIONAL / PASS_RANK_SURVIVES | One ordinary-H covariance-class support leg; sigma convention must stay explicit |
| RF-ENV-01 | ARTIFACT_VALIDATED_CONDITIONAL / NOT_RAW_RERUN | Conditional diagnostic only; not a terminal proof |
| RF-GEN-AXIAL-02 | RULED_OUT | Lessons-forward counterexample; positivity gate is load-bearing |
| RF-BC-02 | NARROWED | Stacked sub-gate systematics not primary, but not replaced by a prove-clean terminal proof |

## Source-Ceiling Note

The source ceilings in the June 21 packet remain load-bearing. Public PRad and Mainz artifacts still do not expose the full denominator/acceptance/final-mask/covariance/projection state required to claim total causal closure from public artifacts alone. This revision makes that limit visible at the packet level instead of hiding it behind RF-ENV-01 terminal language.

## Disposition

The program remains operationally parked and no mechanism-search branch is reopened by this revision. The publication lane has passed successor-packet prove re-entry via `catalog:events/proton-radius-triangulation.md#research_finding:8290ba3bb8942b0d`; the live downstream action is a fresh bundle rebuild from this packet.

Next required steps:

1. Build and verify a fresh bundle from this successor packet, not the June 21 packet.
2. Keep the June 22 Zenodo bundle as a historical build artifact only; do not upload it.
3. If stronger RF-ENV-01 language is still desired, dispatch a dedicated raw-input LP rerun mission and promote only after independent reproduction exists.
