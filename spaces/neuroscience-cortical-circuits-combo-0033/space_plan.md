# Space Plan - neuroscience-cortical-circuits-combo-0033

## Scientific Scope
- Domain: neuroscience
- Theme: cortical_circuits
- Base models: neuroscience-neuroml-layer-5-burst-irregular-nest-basket-cell-3-nmlcl000244-model, neuroscience-neuroml-layer-5-burst-irregular-nest-basket-cell-4-nmlcl000245-model, neuroscience-neuroml-layer-5-burst-irregular-nest-basket-cell-5-nmlcl000246-model

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
