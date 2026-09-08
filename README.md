# COSMOWEAVE UNISON

Created by Yucong Duan (段玉聪).

Causal-Tuning Unified Physics and Grand-Unification Compiler

COSMOWEAVE UNISON extends the original causal-tuning world model from life and consciousness into fundamental physics. It studies a precise candidate principle:

> Physical law is the stable, gauge-covariant, causally composable transport structure that remains after alternative routes interfere, local frames are changed, and descriptions are coarse-grained.

The project does not announce a completed theory of everything. It provides an executable bridge from this principle to quantum interference, gauge covariance, connection holonomy, Standard Model coupling running, grand-unification candidate selection, and a dual-connection gauge-gravity architecture.

## 1. Project overview

The reference suite contains six linked probes:

1. Path coherence - compares phase-tuned, diffuse, and destructively split route ensembles.
2. Gauge covariance - performs random local U(1) frame transformations and verifies invariance of plaquette and Wilson-loop observables.
3. Gauge-coupling running - runs the Standard Model couplings at one loop and computes the threshold mismatch at the non-Abelian meeting scale.
4. Grand-unification compiler - evaluates SU(5), Pati-Salam, Spin(10), E6, and a dual-connection meta-unification candidate against explicit hard gates.
5. Dual-connection probe - demonstrates that spacetime-frame and internal-frame connections can share one covariance/holonomy law without being forced into one ordinary simple group.
6. Fundamental-question compiler - publishes scoped answers, status labels, and falsifiers for eighteen major questions.

## 2. Core problem

Grand unification and quantum gravity are often conflated. The project separates them:

- Internal grand unification asks which high-energy internal symmetry best unifies quarks, leptons, charges, and gauge couplings.
- Full physical unification asks why quantum amplitudes, gauge fields, spacetime geometry, matter, and effective law all use connection, composition, curvature, and coarse-graining structures.

Under explicit conventional hard gates, Spin(10) is selected as the strongest minimal internal GUT candidate. Full unification is represented instead by a dual-connection causal-transport law: a spacetime spin connection and a Spin(10) internal connection are different low-energy sections of one local-covariance principle.

## 3. Key innovations

- treats transition/transport as more primitive than isolated objects;
- interprets classical actuality as phase-coherent causal routing, not raw path count;
- derives gauge redundancy operationally from local frame relabeling;
- treats curvature as nontrivial closed-route holonomy;
- separates internal group unification from law-level gauge-gravity unification;
- uses hard gates and Pareto-style comparison rather than a subjective weighted GUT score;
- registers explicit falsifiers for each theoretical bridge;
- preserves open problems such as three generations, exact constants, the cosmological constant, dark matter, and the full quantum-gravity continuum limit.

## 4. System architecture

```text
causal events
  -> local transport maps
  -> complex route composition
  -> phase-coherent effective histories
  -> local frame covariance
  -> gauge and spacetime connections
  -> holonomy / curvature
  -> stable representations and defects
  -> Spin(10) internal unification candidate
  -> dual-connection gauge-gravity candidate
  -> registered predictions and falsifiers
```

## 5. Directory structure

```text
src/cosmoweave_unison/   package source
tests/                    automated tests
schemas/                  JSON schemas
examples/                 example configuration
docs/figures/             original figures
outputs/                   deterministic reference outputs
studio/                    offline interactive studio
run_demo.py               run the reference suite
run_tests.py              run automated tests
```

## 6. Installation

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .
```

Or install the wheel from the release package.

## 7. Quick start

```bash
python run_demo.py
```

## 8. Command examples

```bash
python -m cosmoweave_unison --output outputs --seed 20260802
python run_tests.py
```

## 9. Input and output formats

Inputs are JSON configuration files. Outputs include:

- `gauge_covariance.json`
- `path_coherence.json`
- `gauge_coupling_running.json`
- `gut_candidates.json` and `.csv`
- `dual_connection.json`
- `generation_spectrum.json`
- `fundamental_questions.json` and `.csv`
- `registered_predictions.json` and `.csv`
- `metrics.json`
- `ledger.json`
- `run_proof.json`

## 10. Configuration

Edit `examples/default_config.json` or pass a seed on the command line.

## 11. Test instructions

```bash
python run_tests.py
```

Expected result: all tests pass.

## 12. Reproducibility

All reference probes use deterministic seeds. `run_proof.json` records SHA-256 hashes of generated outputs. `ledger.json` is a hash-chained experiment history.

## 13. Evidence boundaries

The system demonstrates executable relations and compares candidate theories. It does not prove:

- that the proposed causal-tuning principle is the final law of nature;
- that Spin(10) is uniquely realized in nature;
- that gravity and internal gauge fields have already been derived from one microscopic action;
- that three generations have been explained;
- that the cosmological constant or dark matter has been identified;
- that a theory of everything has been certified.

The fixed public status is:

```text
theory_of_everything_claim = NOT_CERTIFIED
```

## 14. Limitations

- gauge probes use U(1) and two-dimensional analogues rather than full non-Abelian quantum field theory;
- coupling running is one-loop and does not include model-specific thresholds;
- group properties are compiled from explicit metadata, not a computer-algebra proof system;
- the generation-spectrum probe is a deliberately exposed toy hypothesis;
- no nonperturbative continuum quantum-gravity limit is computed;
- proton-lifetime and neutrino predictions remain model dependent.

## 15. Security and privacy

The project is offline and uses synthetic data plus published numerical constants. It has no network, shell, credential, payment, robot, or external-control interface.

## 16. Governance

A claim may be upgraded only with a versioned scope, executable probe or independent evidence, explicit falsifier, and migration note. Failed predictions cannot be silently redefined.

## 17. Contribution guide

See `CONTRIBUTING.md`.

## 18. License

Apache-2.0.

## 19. Changelog

See `CHANGELOG.md`.

## 20. Citation

See `CITATION.cff`.

## Reference run snapshot

```text
gauge covariance: PASS
path-coherence gain: approximately 302x
Standard Model full one-loop unification: FALSE
strict internal GUT hard-gate pass: Spin(10)
dual-connection covariance: PASS
fundamental question contracts: 18
registered predictions: 8
theory of everything: NOT_CERTIFIED
```

## Selected source basis

- Particle Data Group, *Grand Unified Theories*, 2026 review.
- Super-Kamiokande Collaboration, proton-decay search, Phys. Rev. D 102, 112011.
- Ambjorn and Loll, *Causal Dynamical Triangulations: New Lattice Theory of Quantum Gravity*, 2026.
- Masina and Quiros, *The Standard Model partial unification scale as a guide to new physics model building*, 2026 version.
- Saad, *Reality-constrained Minimal Yukawa Structure in SO(10) GUT*, 2026.
- Kofman et al., *Defining Life: A Conversation*, 2026.
