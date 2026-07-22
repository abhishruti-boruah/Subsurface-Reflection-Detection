
# SHARAD Dataset Organisation

This project uses SHARAD radar observations collected from NASA's Planetary Data System (PDS) Mars Orbital Data Explorer(MRO).

Current Dataset

Region:
- Oxia Planum

Storage

Large scientific datasets are stored in Google Drive rather than GitHub because GitHub is intended for source code and documentation. The notebooks in this repository access the dataset directly from Google Drive, ensuring the repository remains lightweight and easy to maintain.

Google Drive Structure

SHARAD_Project
│
└── Data
    ├── Oxia_Planum
    │   └── Observations
    │
    ├── Libya_Montes
    │   └── Observations
    │
    ├── Hellas_Basin
    │   └── Observations
    │
    └── Valles_Marineris
        └── Observations

Current Dataset Statistics

- Region: Oxia Planum
- Number of observations: 262
- Each observation contains:
  - Radargram (.png)
  - Clutter Simulation (.png)
 
Current Status

- ✔ Oxia Planum uploaded
-  Libya Montes in progress
-  Hellas Basin pending
-  Valles Marineris pending
-  Martial South Pole pending

The notebooks access the dataset directly from Google Drive using Google Colab.
