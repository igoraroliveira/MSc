## README

### Português 🇧🇷

# Projeto de Mestrado

Este repositório contém os códigos utilizados no projeto de mestrado do autor, organizados em arquivos Jupyter Notebook (`.ipynb`). O trabalho explora uma extensão do framework **Physics-Informed Neural Networks (PINNs)**, adaptando-o para resolver equações diferenciais com parâmetros variáveis.

## Contexto

O método proposto adiciona uma dimensão de entrada para parâmetros variáveis, permitindo que o modelo generalize soluções para diferentes valores sem a necessidade de treinamento separado para cada caso. O estudo foi aplicado a três problemas:

1. **Equação de Segunda Ordem com Coeficientes Variáveis**: Validação inicial do método.
2. **Equação KdV (Korteweg-de Vries)**: Exploração de ajustes de hiperparâmetros e restrições físicas.
3. **Equação de Sine-Gordon**: Foco principal, com análise de soluções do tipo sóliton e validação do método para parâmetros variáveis.

## Estrutura do Projeto

O repositório está organizado em três pastas principais:

1. **Equação de Segunda Ordem**: Implementação do método para uma equação diferencial com coeficientes \(A\) e \(B\).
2. **Equação KdV**: Aplicação do método à equação KdV, com exploração de ajustes e restrições.
3. **Equação de Sine-Gordon**: Estudo da equação de Sine-Gordon, com dois notebooks: um para exploração inicial e outro com a implementação completa.

## Como Utilizar

1. Instale as dependências necessárias.
2. Abra os notebooks no Jupyter Notebook ou JupyterLab. Para melhor desempenho, use ambientes com suporte a GPU, como **Google Colab** ou **Nvidia NGC**.
3. Execute as células em sequência para reproduzir os resultados.

### English 🇺🇸

# Master's Project

This repository contains the codes used in the author's master's project, organized into Jupyter Notebook (`.ipynb`) files. The work explores an extension of the **Physics-Informed Neural Networks (PINNs)** framework, adapting it to solve differential equations with variable parameters.

## Context

The proposed method adds an input dimension for variable parameters, allowing the model to generalize solutions for different values without the need for separate training in each case. The study was applied to three problems:

1. **Second-Order Equation with Variable Coefficients**: Initial validation of the method.
2. **KdV Equation (Korteweg-de Vries)**: Exploration of hyperparameter tuning and physical constraints.
3. **Sine-Gordon Equation**: Main focus, with an analysis of soliton-type solutions and method validation for variable parameters.

## Project Structure

The repository is organized into three main folders:

1. **Second-Order Equation**: Implementation of the method for a differential equation with coefficients \(A\) and \(B\).
2. **KdV Equation**: Application of the method to the KdV equation, exploring adjustments and constraints.
3. **Sine-Gordon Equation**: Study of the Sine-Gordon equation, with two notebooks: one for initial exploration and another with the complete implementation.

## How to Use

1. Install the necessary dependencies.
2. Open the notebooks in Jupyter Notebook or JupyterLab. For better performance, use environments with GPU support, such as **Google Colab** or **Nvidia NGC**.
3. Run the cells sequentially to reproduce the results.
