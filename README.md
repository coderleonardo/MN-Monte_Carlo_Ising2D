# Método de Monte Carlo aplicado à Mecânica Estatística

Neste trabalho buscamos verificar a acurácia do método de Monte Carlo em encontrar aproximações para soluções da energia, magnetização, capacidade térmica e susceptibilidade magnética do modelo de Ising 2D, e posteriormente comparar com as soluções exatas obtidas por Onsager[2]. Após análises observou-se que o método numérico adotado de fato gera boas aproximações para as quantidades de interesse, principalmente quando temos um número suficientemente grande de configurações possíveis para o nosso sistema.


## Tabela de conteúdo
(1) Introdução
<br>
(2) Método de Monte Carlo aplicado ao modelo de Ising 2D
<br>
  (2.1) Validade do método de Monte Carlo em Mecânica Estatística
  <br>
  (2.2) Método de Monte Carlo via Algoritmo de Metropolis
  <br>
  (2.3) Energia, Magnetização, Capacidade Térmica e Susceptibilidade Magnética no modelo de Ising 2D
  <br>
  (2.4) Algoritmo de Metropolis aplicado ao modelo de Ising 2D
  <br>
    (2.4.1) Algoritmo de Metropolis em Python
    <br>
  (2.5) Resultados obtidos dos valores L=4, L=8, L=12 e L=16
  <br>
(3) Conclusões
<br>
<br>
## Bibliografias
### Bibliotecas usadas

  - https://numpy.org
  - https://mpmath.org
  - https://matplotlib.org

### Livros de referência

[1] Introdução à Física Estatística, Salinas.
<br>
[2] Harvey Gould, Jan Tobochnik - Statistical and Thermal Physics With Computer Applications-Princeton University Press (2010).
<br>
[3] (Graduate Texts in Physics) Kurt Binder, Dieter W. Heermann - Monte Carlo Simulation in Statistical Physics An Introduction-Springer International Publishing (2019)
