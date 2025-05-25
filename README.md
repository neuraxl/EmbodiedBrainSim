# EmbodiedBrainSim
Un cerveau IA incarné avec simulation, visualisation et apprentissage par renforcement.
EmbodiedBrainSim/
├── generator/                  ← Générateur de scènes et métadonnées
│   └── generate_scenes.py
├── parser/                     ← Analyseur et outils de parsing
│   └── parse_logs.py
├── visualizer/                 ← Visualisation des graphes de scènes
│   └── scene_graph_viewer.py
├── interface/                  ← Interface Web (Streamlit)
│   └── dashboard.py
├── models/                     ← Politiques RL avec PyTorch/RLlib
│   └── dummy_policy.py
├── envs/                       ← Environnement AI2-THOR ou Habitat
│   └── thor_env_wrapper.py
├── data/
│   └── generated_scenes.json   ← Fichier de données généré
├── requirements.txt
├── README.md
└── run_all.py                  ← Script central de démonstration
