# dea-catalog-regulations

> DEA catalog for **Regulation** — OpenDEAM v0.3.0 (ADR-0003).

## Regulation (`REG`)

- **Entity id:** `dea:entity-regulation`
- **Allocation:** L2 · L2-risk-compliance
- **Status:** proposed

An externally imposed obligation (law, industry standard with force, contractual mandate) the enterprise must comply with.

## Relationships (from the OpenDEAM model)

- **REG → CTL** — mandates (governance, 1:0..N)

## Allocation contract

This repo's `metamodel-pointer.yaml` is validated in CI against the pinned
OpenDEAM root model (`v0.3.0`) via the reusable
`validate-against-model.yml` workflow. Drift fails CI.

Content (entity instances) lands when the entity promotes from
`proposed` to `planned`/`scaffold` per the model lifecycle.

## License

Apache 2.0 — see [LICENSE](./LICENSE) and [NOTICE](./NOTICE).
