# Mathematical Modelling of Mechanical Ventilation Using ODEs

## Overview

This project investigates the use of ordinary differential equation (ODE) models to study the interaction between mechanical ventilation, respiratory mechanics, and cardiovascular dynamics.

The broader aim is to develop a patient-specific cardiorespiratory modelling framework capable of analysing how ventilation settings, particularly Positive End-Expiratory Pressure (PEEP), affect lung mechanics, gas exchange, venous return, and cardiac output.

As part of the project, we reviewed and synthesised mathematical models from the respiratory and cardiovascular literature, with particular attention to physiologically interpretable ODE-based approaches and their potential use in personalised mechanical ventilation.

## Research Objectives

The project focuses on:

- Modelling respiratory mechanics using airway resistance, lung elastance, airflow, and lung volume;
- Representing cardiovascular dynamics using lumped-parameter compartment models;
- Incorporating time-varying ventricular elastance into cardiac modelling;
- Studying the physiological effects of PEEP on alveolar recruitment and haemodynamics;
- Exploring parameter estimation and patient-specific model calibration;
- Identifying modelling approaches suitable for integrated cardiorespiratory simulation.

## Modelling Framework

### Respiratory System

A common starting point is the single-compartment equation of motion:

\[
P_{aw}(t) = RQ(t) + EV(t) + P_0
\]

where:

- \(P_{aw}\) is airway pressure;
- \(R\) is airway resistance;
- \(Q(t)\) is airflow;
- \(E\) is respiratory-system elastance;
- \(V(t)\) is lung volume;
- \(P_0\) represents baseline pressure such as PEEP.

More advanced models incorporate:

- Recruitment and derecruitment dynamics;
- Time-varying respiratory elastance;
- Gas exchange between alveolar, blood, and tissue compartments;
- Parameter updating under different ventilation conditions.

### Cardiovascular System

The cardiovascular component is based on lumped-parameter modelling, in which vascular compartments are represented using resistance and compliance.

Ventricular pressure-volume behaviour can be described using time-varying elastance:

\[
P(t) = E(t)[V(t) - V_0]
\]

This allows the model to represent changes in cardiac contraction and relaxation throughout the cardiac cycle.

## Mechanical Ventilation and PEEP

A major focus of the project is the role of Positive End-Expiratory Pressure (PEEP).

Increasing PEEP may improve alveolar recruitment and lung compliance, but can also increase intrathoracic pressure and potentially reduce venous return and cardiac output.

The modelling framework therefore aims to investigate the trade-off between respiratory improvement and cardiovascular compromise, supporting the study of personalised ventilation strategies.

## Literature Review

The project draws on previous research in:

- Patient-specific cardiovascular modelling;
- Coupled cardiovascular-respiratory models;
- Model-based PEEP optimisation;
- Recruitment-derecruitment dynamics;
- Time-varying elastance;
- Gas-exchange modelling;
- Parameter estimation and model validation.

The literature review also examines the strengths and limitations of different ODE-based approaches, including their interpretability, identifiability, computational efficiency, and clinical applicability.

## My Contribution

My contribution focused on:

- Reviewing and synthesising literature on respiratory and cardiovascular ODE modelling;
- Identifying mathematical formulations suitable for an integrated cardiorespiratory model;
- Comparing alternative modelling approaches for lung mechanics, cardiovascular dynamics, and gas exchange;
- Investigating methods for parameter estimation and patient-specific calibration;
- Analysing how PEEP-related physiological effects could be represented mathematically;
- Contributing to the development of the overall modelling framework.

## Keywords

`ODE Modelling` · `Mechanical Ventilation` · `Cardiorespiratory Modelling` · `PEEP` · `Respiratory Mechanics` · `Cardiovascular Modelling` · `Patient-Specific Modelling`
