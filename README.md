**A guide for running protein MD simulations using GROMACS in Google Colab**
**Prerequisites**

Google account with Colab access
GPU runtime in Colab
Free Google Drive space

**Required Files**
All files needed are in input_files/:
**Parameter Files**

step4.0_minimization.mdp
step4.1_equilibration.mdp
step5_production.mdp

**Structure Files**

step3_input.gro
topol.top
index.ndx

**Setup Steps**

Open notebook in Google Colab
Enable GPU runtime
Mount Google Drive
Create working directory
Upload input files

**Running the Simulation**
Follow the notebook steps in order:

Installation
Energy Minimization
Equilibration
Production
Analysis

**Common Issues**

GPU not found: Enable GPU in Runtime settings
Space issues: Clear Colab runtime
Runtime disconnection: Save checkpoints
