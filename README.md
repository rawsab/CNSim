# Consensus Network Simulator

A simulation and visualization platform for experimenting with consensus network protocols and modeling client/node interactions in distributed systems. Supports configurable client and node behavior (including malicious actors), blockchain structure modeling, and state visualization for real-time consensus tracking. Features a UI to explore account, node, and client dynamics under varied network configurations. Models currently supported: Bitcoin, Tangle, DDLN, etc.

<img width="1920" height="1280" alt="cnsim_concept_art" src="https://github.com/user-attachments/assets/a9defe23-74ee-4b0e-bdeb-f135e5aac263" />

<!--
![cnsim_github](https://github.com/user-attachments/assets/0b315c89-bd58-48d5-9f06-d32ccf81843d)
-->

## Running the Project

To run the project on your local machine, navigate to the `consensus-network-sim/CNSim/resources/test-blockchain/Visualization/CNSVisualization` directory in the terminal and run the Flask server:

```bash
  python app.py
```

In a new terminal, run the web application:

```bash
  python -m http.server 8000
```

Then go to `localhost:8000` on your browser to use the tool.

See the [Demo (Alpha)](https://youtu.be/_oITtijlbb8)

## Contributors

- Rawsab Said
- Amirreza Radjou

## Credits

> This repository is based on **CNSim (Consensus Network Simulator)**, a discrete-event simulation framework whose Java core includes authorship notices for **Sotirios Liaskos** and the **Conceptual Modeling Group / Enterprise Systems Group at York University** (see `@author` tags under `CNSim/src/cmg/cnsim/`). Additional authorship is noted in source files.
> 
> The project was originally developed as **academic/research software** and later extended for **simulation and research** use. I am **Rawsab Said**, a **contributor** to this codebase. **Amirreza Radjou** led the prior academic/work integration.
