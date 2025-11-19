# User profiling

This code creates 1000 synthetic users: 
1. It defines the set of categories-apps and traffic percentage for each user based on the power-law distribution of the inter and intra-category probabilities. 
2. It assigns the corresponding traffic to each user using mobile app traces.
3. It profiles each user based on DNS traffic.

## Citation

If you use this code in your research, please cite our paper:

```bibtex
@ARTICLE{11250988,
  author={Jimenez-Berenguel, Andrea and Gil, César and Garcia-Rubio, Carlos and Forné, Jordi and Campo, Celeste},
  journal={IEEE Access}, 
  title={DNS Query Forgery: A Client-Side Defense Against Mobile App Traffic Profiling}, 
  year={2025},
  volume={},
  number={},
  pages={1-1},
  keywords={Domain Name System;Privacy;HTTP;Forgery;Data privacy;Telecommunication traffic;Metadata;Reviews;Mobile applications;Servers;DNS traffic;Data Perturbation Techniques;Privacy-Enhancing Technologies;Query Forgery;User Privacy;User Profiling},
  doi={10.1109/ACCESS.2025.3633695}
}
```

## Acknowledgements

This work was supported by Grant COMPROMISE (PID2020-113795RB-C32 and PID2020-113795RB-C31) funded by MICIU/AEI/10.13039/501100011033, Grant QURSA (TED2021-130369B-C32) funded by MICIU/AEI/10.13039/501100011033 and European Union NextGenerationEU/PRTR, Grant MOBILYTICS (TED2021-129782B-I00) funded by MICIU/AEI/10.13039/501100011033 and European Union NextGenerationEU/PRTR, Grant SISCOM (2021 SGR 01413) funded by Generalitat de Catalunya through Agència de Gestió d'Ajuts Universitaris i de Recerca (AGAUR), Grant DISCOVERY (PID2023-148716OB-C33 and PID2023-148716OB-C32) funded by MICIU/AEI/10.13039/501100011033 and FEDER, UE, and from the I-Shaper Strategic Project (C114/23), due to the collaboration agreement signed between the Instituto Nacional de Ciberseguridad (INCIBE) and the Universidad Carlos III de Madrid, this initiative is being carried out within the framework of the Recovery, Transformation and Resilience Plan funds, funded by the European Union (Next Generation).