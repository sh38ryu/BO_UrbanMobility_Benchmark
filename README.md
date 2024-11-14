# BO_UrbanMobility_Benchmark

This repository contains the code and resources for the workshop talk on **Bayesian Optimization for High-dimensional Urban Mobility Problems** presented at the **NeurIPS 2024 Workshop on Bayesian Decision-making and Uncertainty**. The project addresses optimization challenges in designing urban mobility digital twins and explores open questions and research opportunities in Bayesian optimization, uncertainty quantification, and inverse optimization.

## Overview
The repository presents a framework for tackling travel demand (origin-destination) estimation in urban networks, specifically targeting two road networks:
1. A simplified illustrative toy network.
2. The San Francisco metropolitan network.

The codebase provides tools for:
- **Setting up travel demand estimation problems** for urban mobility applications.
- **Applying Bayesian optimization** techniques to solve high-dimensional optimization problems relevant to urban transportation systems.
- **Evaluating optimization results** with focus on uncertainty quantification and inverse optimization.

## Repository Structure
- `bayesian_optimization/`: Contains Jupyter notebooks to run experiments and helper functions for Bayesian optimization tasks.
- `config/`: Configuration files specifying parameters for different networks and model settings.
- `network/`: Network data for the toy network and the San Francisco metropolitan network, including traffic and topology information.
- `output/`: Directory that will be automatically generated to store experiment results and logs.
- `README.md`: Project documentation.
## Network Data

The data for the San Francisco metropolitan network and toy network can be downloaded from the following link:
[Google Drive - Network Data](https://drive.google.com/drive/folders/1--mlsymabNWqtGUKvF1ujgmPg0BXaAyb?usp=sharing)

After downloading, place the data in the `network/` directory to ensure proper setup.

 - network
   - quickstart
   - SFO

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed. Recommended packages are listed in `requirements.txt`. Install dependencies with:
```bash
pip install -r requirements.txt
```

### Running the Code

To start with a simple example:
1. Run the Jupyter notebooks `bayesian_optimization/bo_vanilla.ipynb` for step-by-step guidance on solving the travel demand estimation problem for each network.

### Future Development Plans



## Citation

If you use this code or find it helpful, please cite:

```bibtex
@article{choispatiotemporal,
  title={Bayesian Optimization for High-dimensional Urban Mobility Problems},
  author={Choi, Seongjin and Rodriguez, Sergio and Osorio, Carolina},
  booktitle={NeurIPS workshop on Bayesian Decision-making and Uncertainty 2024}
}
```

If you use toy network, please cite:
```bibtex
@inproceedings{SUMO2018,
          title = {Microscopic Traffic Simulation using SUMO},
         author = {Pablo Alvarez Lopez and Michael Behrisch and Laura Bieker-Walz and Jakob Erdmann and Yun-Pang Fl{\"o}tter{\"o}d and Robert Hilbrich and Leonhard L{\"u}cken and Johannes Rummel and Peter Wagner and Evamarie Wie{\ss}ner},
      publisher = {IEEE},
      booktitle = {The 21st IEEE International Conference on Intelligent Transportation Systems},
           year = {2018},
        journal = {IEEE Intelligent Transportation Systems Conference (ITSC)},
       keywords = {traffic simulation, modelling, optimization},
            url = {https://elib.dlr.de/124092/}
 }
 ```
 
If you use SFO network, please cite:
```bibtex
@article{ambuhl2022traffic,
  title={Traffic Simulations for Boston, Lisbon, Los Angeles, Rio de Janeiro, San Francisco: SUMO simulation files for running 24h of car traffic},
  author={Amb{\"u}hl, Lukas and Menendez, Monica and Gonz{\'a}lez, Marta C},
  year={2022},
  publisher={ETH Zurich}
}
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For questions or feedback, please contact [Seongjin Choi](chois@umn.edu) or [Carolina Osorio](carolina.osorio@hec.ca).



