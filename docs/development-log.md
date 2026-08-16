# Development Log

## 17 August 2026 — Phase 1

### Step
Project initialization

### Decision
Created a modular repository separating frontend, backend, ML and documentation.

### Reason
This structure keeps the application maintainable and allows each component to evolve independently.

### Status
Completed

 ### Version 2 — ML Pipeline

Phase: 1
Version: V2.0
Goal: Build and validate the machine-learning component independently before connecting it to FastAPI and React.

 ### V2 scope
Dataset
   ↓
Data loading
   ↓
Data exploration
   ↓
Data preprocessing
   ↓
Train / Test split
   ↓
Feature scaling
   ↓
Model training
   ↓
Model evaluation
   ↓
Select best model
   ↓
Save trained model

For this project, we'll use the Breast Cancer Wisconsin dataset first because it fits the prediction application we already defined.