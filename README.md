# func-analysis

Functional analysis in Rust. Banach spaces, Hilbert spaces, and operators between them.

Implements core constructions from functional analysis — Banach and Hilbert spaces, bounded linear operators, compact operators, spectral theory, Fredholm theory, and Sobolev spaces. Built on [nalgebra](https://nalgebra.org) for linear algebra and [serde](https://serde.rs) for serialization.

## Install

```toml
[dependencies]
func-analysis = "0.1"
```

## Modules

- **banach** — Banach spaces with configurable norms (L¹, L², L∞), contraction mappings
- **hilbert** — Hilbert spaces, Gram-Schmidt, orthogonal projection
- **operator** — Bounded linear operators, adjoints, self-adjointness
- **compact** — Compact operators, singular values, low-rank approximation
- **spectral** — Spectral decomposition, functional calculus
- **fredholm** — Fredholm operators, index, solvability
- **sobolev** — Sobolev spaces, weak derivatives, embedding theorems

## License

MIT OR Apache-2.0
