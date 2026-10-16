# Validation scope

Assessment date: 2026-10-16. Historical saved evidence and current checks are distinct.

## Current lightweight check

The existing saved clean-core Python environment ran `pytest -p no:cacheprovider tests/test_metrics.py tests/test_experiment_schema.py tests/test_reproducibility.py` with bytecode generation disabled: **5 passed**, exit 0, approximately 15.19 seconds. No training, model export, dataset acquisition, full runtime benchmark or complete application suite was run. This is validation in the canonical local environment, not a test that the documentation-only export can run the system.

## Historical evidence

The saved release manifest records version 0.8.0, text-only core, research Docker recovery PASS and Phase 8 exit PASS. Original clean-core evidence reported a scikit-learn artifact-version warning and a Starlette TestClient warning. The new export neither removes those qualifications nor recertifies the entire project.

## Public export checks

Relative Markdown/image links, selected asset equality, every payload file's manifest size/SHA-256, extension/path constraints, exact byte counts and secret/privacy patterns were checked against this exact staging tree. No external README link is claimed to be a published flagship repository. The manifest's own integrity is recorded in the separate publish inventory to avoid a recursive self-hash. These checks do not settle source or asset ownership.

## Remaining review

Owner publication/screenshot attribution approval; any source license; B2 lineage and model/data redistribution. Speech quality and synthetic multimodal confounding remain research limitations, not publication-cleanup tasks.
