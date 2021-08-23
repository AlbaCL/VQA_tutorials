# Variational Quantum Algorithms tutorials

In this repository you will find some well-known Variational Quantum Algorithms (VQA) demos implemented with Tequila language.

You will need to install Tequila and some quantum simulator backend to run them:
- [Tequila repository](https://github.com/aspuru-guzik-group/tequila) for installation instruction
- [Tequila tutorials](https://github.com/aspuru-guzik-group/tequila-tutorials) for usage.
- [Tequila paper](https://iopscience.iop.org/article/10.1088/2058-9565/abe567) (eprint: [arXiv:2011.03057](https://arxiv.org/abs/2011.03057)).

Feel free to fork it and play with these VQA algorithms or use it for your own work.
Please, consider citing Tequila paper and the papers used to produce these tutorials.

**Content**

- `Meta-VQE` and `Molecular-Meta-VQE`: two demo examples (XXZ spin chain and $H_{2}$ molecule, respectively) of the meta-VQE algorithm (QML + quantum simulation).
- `QAOA`: basic code with a four-qubit QAOA example (Max-Cut problem) and its comparison with a hardware-efficient VQE ansatz.
- `QFit`: a single-qubit function learner (quantum supervised learning example).
- `SingleQubitClassifier`: a single-qubit quantum classifier example.