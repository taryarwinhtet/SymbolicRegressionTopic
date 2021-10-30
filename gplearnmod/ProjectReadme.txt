This folder consist of various symbolic regression run to test the different effects of symbolic regression bloat control method.
This folder contain simplification on symbolic regression output for different generation limit (10,  20, 30, 40, 50 and 100 )

We used the algebraic expression x₀³+4x₁-0.75 a target expression
We did 4 different run of symbolic regression (1) No parsimony pressure
                                              (2) No parsimony or Hoist mutation
                                              (3) Parsimony set to automatic
                                              (4) Default 
The result conclude that while bloat control methods such as hoist muatation and parsimony pressure could help maintain the program at a smaller size, in the process it could destroy good building blocks for evolution