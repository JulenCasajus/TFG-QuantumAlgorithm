# TFG-QuantumAlgorithm

Quantum-circuit prototypes for a bachelor's final project on window-based search over discrete grids.

## Contents

- `TFG_V0.ipynb`: one-dimensional baseline circuit that loads each valid window into a work register.
- `TFG_V1.ipynb`: one-dimensional optimisation using Gray-like mask traversal and coherent penalisation/postselection.
- `TFG_V2.ipynb`: extension of the window-loading circuit to N-dimensional grids.
- `TFG_V3.ipynb`: N-dimensional circuit with an oracle/interference stage.
- `TFG_V4.ipynb`: N-dimensional cost-phase plus local-mixer prototype for biasing probability toward valid windows without Grover diffusion.
- `Deutsch-Jozsa.ipynb`: reference implementation for phase kickback and interference.
- `Simon.ipynb`: reference implementation for Simon's hidden-string interference condition.
- `Report.txt`: technical report describing the circuit sequence, improvements, limitations, and future work.
- `TFG_Pruebas*.ipynb`: exploratory notebooks and tests.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Then open the notebooks with Jupyter or VS Code.

## Notes

Notebook outputs are intentionally cleared before publication to keep the repository compact and reproducible.
IBM Quantum credentials must be supplied locally by the user and must not be committed to the repository.
