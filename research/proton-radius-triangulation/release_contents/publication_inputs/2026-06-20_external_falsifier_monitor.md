# External Falsifier Monitor

program_slug=proton-radius-triangulation
created_at=2026-06-20
monitor_status=active_until_parked
source_finding=catalog:events/proton-radius-triangulation.md#research_finding:c79987d851442f46

## Standing Prediction

The current program state predicts that future same-apparatus lepton scattering, higher-precision PRad repetition, and Mainz-successor low-Q2 measurements should land in or be compatible with the small-radius basin once source/correlation structure is handled explicitly. A robust large-radius successor result, a same-apparatus mu-p/e-p split, or newly released source packets that change the nuisance accounting would reopen the relevant typed branch.

## Monitor Keys

| Source | Typed object | Expected compatible signal | Reopen trigger |
| --- | --- | --- | --- |
| MUSE | same-apparatus mu-p/e-p scattering comparison | no robust lepton-universality split after source/correlation handling | confirmed mu-p/e-p radius split with shared apparatus controls |
| PRad-II | Sachs G_E slope / ep-Moller normalization source topology | small-radius-compatible result or source-corrected PRad shift | robust large-radius result or released denominator/acceptance/event-selection packets changing RF-MA/RF-KT accounting |
| MAGIX/MESA | low-Q2 Mainz-successor Sachs-slope extraction | small-radius-compatible low-Q2 result or explicit nuisance explanation | high-precision large-radius successor result with source-complete covariance |
| Mainz/A1 private packets | Sachs G_E slope and covariance topology | resolves remaining private replay/source-ceiling questions without new carrier | exact covariance/projection/MINUIT/profile artifacts that reverse RF-ENV/RF-MQ/RF-KT source accounting |
| PRad collaboration packets | denominator, acceptance, event-selection, Moller normalization | signed per-bin controls demote scalar envelopes below materiality | per-bin signed spectra or direct nuisance refit showing >=0.010 fm coherent carrier |

## Handling Rule

Any future monitor event must be classified as one of: Sachs G_E slope, bound-state contact/Wilson coefficient, CODATA adjusted parameter, or convention/translation object. Untyped scalar r_p language is not admissible for branch routing.

## Program Disposition Rule

After publication assembly and cross-program signal delivery are complete, move the program to PARKED_MONITOR_ONLY unless one of the reopen triggers above changes the factual state.
