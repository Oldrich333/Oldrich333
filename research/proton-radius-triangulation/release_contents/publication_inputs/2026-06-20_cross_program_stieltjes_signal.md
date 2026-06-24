# Cross-Program Signal: EM Stieltjes Envelope Method

program_slug=proton-radius-triangulation
created_at=2026-06-20
signal_status=ready_for_reuse_review
source_claim=RF-ENV-01

## Signal

The confirmed transferable method is narrow: for EM nucleon form factors where a positive spectral measure is justified, Stieltjes linear-programming envelopes can separate "data/function-space regularization limit" from "candidate hidden carrier" before mechanism search burns time.

The useful pattern is not "Stieltjes applies everywhere." RF-GEN-AXIAL-02 is the counterexample: G_A fails the first-principles positivity gate in the 3-pion channel. The reusable method is therefore a two-step gate:

1. Prove or source the positive-measure/Stieltjes property for the observable.
2. Only then use moment/envelope width against observed method spread to decide whether residuals are inside mathematical regularization freedom.

## Candidate Consumers

- resonance-physics: possible form-factor or response-function envelopes where a positive spectral representation is already part of the physics.
- future hadronic-form-factor work: EM G_E/G_M channels first; axial, weak, or multiparticle channels require a fresh positivity proof before reuse.

## Reuse Bar

The bar is a proof/metadata gate, not a numerical convenience. A same-shaped LP calculation without a sign-definite spectral measure is model-dependent and should not inherit RF-ENV-01's epistemic weight.

## One-Line Export

RF-ENV-01 converts the proton-radius post-resolution residual into a regularization-envelope result: if the observable is genuinely Stieltjes, moment LP width can prove that cross-method spread is not enough evidence for a hidden physical carrier; RF-GEN-AXIAL-02 shows the positivity gate is load-bearing.
