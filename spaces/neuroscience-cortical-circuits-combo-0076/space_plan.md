# Space Plan - neuroscience-cortical-circuits-combo-0076

## Scientific Scope
- Domain: neuroscience
- Theme: cortical_circuits
- Base models: neuroscience-neuroml-layer-5-burst-accommodating-bipolar-cell-2-nmlcl000138-model, neuroscience-neuroml-layer-5-burst-accommodating-bipolar-cell-3-nmlcl000139-model, neuroscience-neuroml-layer-5-burst-accommodating-bipolar-cell-4-nmlcl000140-model, neuroscience-neuroml-layer-5-burst-accommodating-bipolar-cell-5-nmlcl000141-model

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
