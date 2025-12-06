🔬 Molecular Solubility Prediction Model

Machine Learning for Chemistry — Without Structural Encoding Dependencies

Solubility is a cornerstone property in drug development, materials science, and molecular engineering. A compound’s solubility influences absorption, stability, synthesis feasibility, and therapeutic usability. Accurate prediction helps reduce experimental workload while accelerating discovery.

This repository introduces a data-driven machine learning model designed to predict the solubility of molecules using pre-computed chemical features/descriptors––without depending on SMILES parsing tools or RDKit. The model learns patterns from numerical molecular attributes and delivers fast, reproducible solubility predictions at scale.

🌟 Features

  📈 ML-based solubility prediction using tabular chemical descriptors
  
  ⚡ Fast inference for thousands of entries in a single run
  
  🔁 Retrainable pipeline for experimenting with new descriptors or models

🧩 Tech & Tools
    Component	Role
        Python + Pandas	Dataset handling
        NumPy	Vectorized feature computation
        Scikit-Learn
        Matplotlib	Result visualisation & analysis

