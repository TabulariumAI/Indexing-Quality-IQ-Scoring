# Index Quality (IQ) Scoring

An open specification for deterministic scoring of extracted index fields in official records.

**Published version:** 2.1 (2026-11-17)

## Specification

See [IQ-Scoring-Spec.md](IQ-Scoring-Spec.md) for the scoring model, inputs, decision logic, worked example, and audit requirements. The figure used by the specification is [iq-figure-1.png](iq-figure-1.png).

The specification is licensed under Apache License 2.0; see [LICENSE](LICENSE). It describes the mathematical scoring framework. Extraction pipelines, deployment configurations, and scoring parameters are outside the scope of this repository unless separately published here.

## Conformance

Machine-readable examples are provided in [conformance](conformance/README.md). They are informative test vectors for checking implementations against the normative equations and decision order.

## Versions and citation

Published versions are immutable and identified by Git tags. Changes to normative behavior require a new version and a corresponding [changelog](CHANGELOG.md) entry.

Citation metadata is provided in [CITATION.cff](CITATION.cff).

## Contributions

See [CONTRIBUTING.md](CONTRIBUTING.md) for the contribution and sign-off requirements.

## Scope

This repository publishes a specification. It does not provide an implementation, parameter set, or warranty that a particular implementation or configuration will produce a given result.
