# Quantitative Finance
This repository covers the following topics: asset pricing theory and its applications, financial optimization, market equilibrium, dynamics trading strategies, risk management, and selected advanced topics in financial engineering and technology.

### Public Data Sources
**Name** | **Data types**
-------------------- | --------------------
**Yahoo Finance**: | Historical price, annual and quarterly financial statements, and so on
**Google Finance**: | Current, historical trading prices
**Federal Reserve Economic Data**: | Interest rates, rates for AAA, AA rated bonds
**Prof. French's Data Library**: | Fama-French factor time series, market index returns, and industry classification
**Census Bureau**: | Census data
**US. Department of Treasury**: | US. Treasure yield
**Bureau of Labor Statistics**: | Inflation, employment, unemployment, pay and benefits
**Bureau of Economic Analysis**: | Gross Domestic Product (GDP) and so on
**NBER**: | Business cycles, vital statistics, report of presidents

### Stochastic Processes
**1.1** Definition: Given a probability space (Ω, ℱ , P), a stochastic process is any collection {X(t) ∶ t ∈ I} of random variables defined on this probability space, where I is an index set. The notations Xt and X(t) are used interchangeably to denote the value of the stochastic process at index value t.

**1.2** General Characteristics of Stochastic Processes
1.2.1 The Index Set I
The set I indexes and determines the type of stochastic process. This set can be quite general but here are some examples:
- If I = {0, 1, 2 …} or equivalent, we obtain the so-called discrete-time stochastic processes. We shall often write the process as {Xn}n∈ℕ in this case.
- If I = [0, ∞), we obtain the continuous-time stochastic processes. We shall write the process as {Xt}t≥0 in this case. Most of the time t represents time.
- The index set can be multidimensional. For example, with I = ℤ × ℤ, we may be describing a discrete random field where at any combination (x, y) ∈ I we have a value X(x, y) which may represent some node weights in a two-dimensional graph. If I = [0, 1]×[0, 1] we may be describing the structure of some surface where, for instance, X(x, y) could be the value of some electrical field intensity at position (x, y).

1.2.2 The State Space 𝒮
The state space is the domain space of all the random variables Xt. Since we are discussing about random variables and random vectors, then necessarily 𝒮 ⊆ ℝ or ℝn. Again, we have several important examples:
- If 𝒮 ⊆ ℤ, then the process is integer valued or a process with discrete state space.
- If 𝒮 = ℝ, then Xt is a real-valued process or a process with a continuous state space.
- If 𝒮 = ℝk, then Xt is a k-dimensional vector process.

The state space 𝒮 can be more general (for example, an abstract Lie algebra), in which case the definitions work very similarly except that for each t we have Xt measurable functions.

We recall that a real-valued function f defined on Ω is called measurable with respect to a sigma algebra ℱ in that space if the inverse image of set B, defined as f^−1(B) ≡ {𝜔 ∈ E ∶ f(𝜔) ∈ B)} is a set in sigma algebra ℱ , for all Borel sets B of ℝ.



To be continued

### Reference
Mariani, M. C., & Florescu Ionuţ. (2020). Quantitative finance. Hoboken, NJ: Wiley.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
