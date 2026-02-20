# Space Plan - neuroscience-cortical-circuits-combo-0068

## Scientific Scope
- Domain: neuroscience
- Theme: cortical_circuits
- Base models: neuroscience-neuroml-layer-4-delayed-stuttering-bipolar-cell-5-nmlcl001091-model, neuroscience-neuroml-layer-4-delayed-stuttering-large-basket-cell-1-nmlcl001092-model, neuroscience-neuroml-layer-4-delayed-stuttering-large-basket-cell-2-nmlcl001093-model, neuroscience-neuroml-layer-4-delayed-stuttering-large-basket-cell-3-nmlcl001094-model

## Wiring Plan
- Comparative mode with monitor-only routing.
- Each base model state-like output connects to monitor ports `state_a..state_d`.
- No direct causal links among base models unless explicitly upgraded later.

## Visualization Plan
- Include `StateComparisonMonitor` and `StateMetricsMonitor`.
- Require at least:
  - one timeseries visual,
  - one summary table visual.

## Validation Gates
- space schema validity
- wiring endpoint validity
- smoke run success
- repo manifest/entrypoint validators pass
