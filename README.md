# Projeto de Mestrado

Este repositório contém os códigos utilizados no projeto de mestrado do autor, organizados em arquivos Jupyter Notebook (`.ipynb`). O trabalho explora uma extensão do framework **Physics-Informed Neural Networks (PINNs)**, adaptando-o para resolver equações diferenciais com parâmetros variáveis.

## Contexto

O método proposto adiciona uma dimensão de entrada para parâmetros variáveis, permitindo que o modelo generalize soluções para diferentes valores sem a necessidade de treinamento separado para cada caso. O estudo foi aplicado a três problemas:

1. **Equação de Segunda Ordem com Coeficientes Variáveis**: Validação inicial do método.
2. **Equação KdV (Korteweg-de Vries)**: Exploração de ajustes de hiperparâmetros e restrições físicas.
3. **Equação de Sine-Gordon**: Foco principal, com análise de soluções do tipo sóliton e validação do método para parâmetros variáveis.

## Estrutura do Projeto

O repositório está organizado em três pastas principais:

1. **Equação de Segunda Ordem**: Implementação do método para uma equação diferencial com coeficientes \( A \) e \( B \).
2. **Equação KdV**: Aplicação do método à equação KdV, com exploração de ajustes e restrições.
3. **Equação de Sine-Gordon**: Estudo da equação de Sine-Gordon, com dois notebooks: um para exploração inicial e outro com a implementação completa.

## Como Utilizar

1. Instale as dependências necessárias.
2. Abra os notebooks no Jupyter Notebook ou JupyterLab. Para melhor desempenho, use ambientes com suporte a GPU, como **Google Colab** ou **Nvida NGC**
3. Execute as células em sequência para reproduzir os resultados.
