# hiq-jupyter Plug-in
This is a Jupyter notebook plugin for graphically editing HiQ programs. 

## Installation

1. Clone repository and go inside
2. Run `python ./setup.py install --user`
3. Run `python ./setup.py develop --user`

## Usage

```
from qcircuit import QCircuit, Classic, Qubit, Qureg
```

```
n_qubits = 4
circuit_obj = QCircuit(qncilla=Qubit, c_in=Classic, qreg=(n_qubits, ))
circuit_obj
```

![Jupyter HiQ Plug-in inited](docs/resources/circuit_inited.png "Plug-in inited")


Using mouse draw any circuit schema with UI

![Jupyter HiQ Plug-in example](docs/resources/circuit_example.png "Plug-in example")


Try to change circuit parameters order or add/delete some or change QuReg size to see updated circuit

![Jupyter HiQ Plug-in example](docs/resources/circuit_reordered.png "Plug-in example reordered")
