# Pediatric PBPK Prediction Using Adult Models

## Overview
Apply adult PBPK models to predict pediatric PK across neonates, infants, children, and adolescents, including preterm populations.

## Objective
Predict PK profiles for Voriconazole, Levetiracetam, Clopidogrel, and Etanercept using validated adult PBPK models.

## Tools
- PK-Sim (pediatric modules)
- mrgsolve (population simulations)
- Python/R for plotting

## Innovation / Twists
- Include **preterm neonates**
- Model **enzyme ontogeny** (CYP2C19, renal maturation, prodrug activation, biologic clearance)
- Evaluate **formulation differences** (oral solution, capsule, IV)
- Simulate **population variability** using mrgsolve

## Deliverables
- `/pk-sim/pediatric_models/*.pksim5`
- `/mrgsolve/pediatric_simulations/*.R`
- `/analysis/pediatric_predictions.ipynb` with age-stratified PK plots, violin plots for variability

