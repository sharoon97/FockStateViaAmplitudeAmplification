# Fock-State Preparation Based on Amplitude Amplification in Cavity QED

Companion materials for **[Fock-state preparation based on amplitude amplification in cavity QED](https://arxiv.org/abs/2607.14239)** by Sharoon Austin, Zhi-Yuan Wei, Kartik Srinivasan, and Alexey V. Gorshkov.

## Overview

This work develops coherent-control protocols based on amplitude amplification for two cavity-QED platforms:

1. **Traveling single-photon generation:** a three-level emitter coupled to an optical cavity is driven by weak control pulses. A variant of oblivious amplitude amplification coherently amplifies the desired single-photon mode.
2. **Fock- and NOON-state preparation:** a superconducting qubit dispersively coupled to a microwave cavity is controlled with fixed-point amplitude amplification, SNAP gates, and cavity displacements.

The protocols replace a single strong control operation with a sequence of weaker coherent operations, offering a route to improved scaling and, in relevant regimes, reduced loss.

## Main results

- We introduce **very oblivious amplitude amplification**, which uses reflections acting only on a signal qubit together with the state-preparation unitary and its inverse.
- For traveling single-photon generation, the required protocol length scales as \(N \sim 1/\sqrt{p}\), improving on the \(N \sim 1/p\) scaling of repeated heralded attempts, where \(p\) is the one-pulse success probability.
- The protocol can reduce error from intrinsic cavity loss relative to a single strong control pulse in experimentally relevant regimes.
- For circuit QED, fixed-point amplitude amplification yields a Fock-state-preparation sequence of length \(O(n^{1/4})\), where \(n\) is the target photon number. This is a quadratic improvement over the \(O(n^{1/2})\) scaling of the prior approach considered in the paper.
- The same framework is extended to NOON-state preparation using two dispersively coupled cavity-qubit systems and a beam-splitter interaction.

## Physical settings

### Optical cavity QED

A Lambda-type emitter is coupled to a cavity and a waveguide. A classical control field drives one emitter transition while the cavity couples the other transition to the target traveling-photon mode. The protocol uses weak pulses and coherent feedback through the cavity to amplify single-photon emission.

### Circuit QED

A superconducting qubit is dispersively coupled to a bosonic microwave cavity. Fixed-point amplitude amplification is implemented with number-dependent arbitrary-phase (SNAP) gates and cavity displacements to prepare high-photon-number Fock states. A two-cavity extension prepares NOON states.

## Reproducibility

The numerical work should reproduce the protocol fidelities, loss/error comparisons, and sequence-length scaling described in the paper. For each calculation, record the physical parameters, target state, amplitude-amplification phases, and numerical tolerances used to generate a figure.

Large simulation outputs, cached data, and generated figures should be excluded from version control unless they are intentionally released as a compact reproduction package.

## Citation

If you use this work, please cite:

```bibtex
@article{austin2026fock,
  title={Fock-state preparation based on amplitude amplification in cavity QED},
  author={Austin, Sharoon and Wei, Zhi-Yuan and Srinivasan, Kartik and Gorshkov, Alexey V.},
  journal={arXiv preprint arXiv:2607.14239},
  year={2026}
}
```

## License

Add a license before releasing the repository publicly. The MIT License or BSD 3-Clause License are common choices for research code.
