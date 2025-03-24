# Uncertainty Quantification in Structural Dynamics

## Overview
This series of Jupyter Notebooks is based on the book **Quantificação de Incerteza e Estimação de Parâmetros em Dinâmica Estrutural: Uma Introdução Baseada em Exemplos Computacionais** by Daniel Alves Castello and Thiago Gamboa Ritto.

## Project Objectives
- Summarize the theoretical contents of the book
- Explore the underlying mathematical formulae and their derivations
- Translate the original MATLAB codes to Python

## Computational Approach

### Probability Theory and Static Problem
We begin by introducing fundamental concepts in Probability Theory and tackle a static problem to determine the model's stiffness using experimental data.

<div align="center">
    <img src="diagrams\03_mechanical_test.svg" width="35%" style="max-width: 350px; margin: 0 2.5%"> 
    <img src="diagrams\03_identified_model.svg" width="35%" style="max-width: 350px; margin: 0 2.5%">
</div>

### Dynamic System Analysis
Next, we analyze a dynamical system represented by a mass-spring-damper model.

<div align="center">
    <img src="diagrams\04_dynamical_model.svg" width="45%" style="max-width: 400px; margin: 0 2.5%">
</div>

#### Frequency Response Exploration
For this dynamical system, we identified upper and lower limits for the Frequency Response based on a probability distribution of the uncertain parameter.

<div align="center">
    <img src="diagrams\04_frf_uncertain_zeta.svg" width="55%" style="max-width: 600px; margin: 0 2.5%">
</div>

#### Parameter Identification
Using experimental data and a reference model, we identified the uncertain parameter.

<div align="center">
    <img src="diagrams\04_identified_frf_residuals.svg" width="55%" style="max-width: 600px; margin: 0 2.5%">
</div>

## Complementary Topics
Throughout the project, we developed additional notebooks to provide insights into:
- Frequency Response Function and Fourier Transform
- Least-Squares Method
- Levenberg-Marquardt Method for Error Minimization

## References
1. Castello, D. A., & Ritto, T. G. (2016). *Quantificação de Incerteza e Estimação de Parâmetros em Dinâmica Estrutural: Uma Introdução Baseada em Exemplos Computacionais*. [Notas em Matemática Aplicada Vol. 81]
2. Riley, K. F., & Hobson, M. P. (2006). *Mathematical Methods for Physics and Engineering: Third Edition*. [Cambdrige University Press]
3. Mary L. Boas, (2005). *Mathematical Methods in the Physical Sciences: Third Edition*. [Wiley]
