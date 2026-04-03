# Prescribed-Time-Formation-Control-of-Caputo-Fractional-Order-Multi-Agent-System


This project addresses a prescribed-time formation tracking problem in fractional-order multi-agent systems: 
The Caputo fractional derivative does not satisfy the standard product rule, 
making it challenging to derive the desired stability inequality directly from the system dynamics. 


To bridge the theoretical gap caused by the fractional-order product rule, 
a residual term $R(t)$ is introduced to quantify the difference between the truly obtained fractional derivative and the expression needed for stability analysis. 


<p align="center">
$R(t) = \phi^{-k_{3}}_{\sigma(t)}(t){_{t_{0}}^C}D_{t}^{\gamma}{H}(t)-k_{3}\phi^{-k_{3}-1}_{\sigma(t)}(t)\dot{\phi}_{\sigma(t)}(t)H(t)-{_{t_{0}}^C}D_{t}^{\gamma}\Big(\phi^{-k_{3}}_{\sigma(t)}(t){H}(t)\Big)$ 
</p>

A neural network model is employed as a numerical tool to learn a positive definite matrix $\bar{P}$ such that the prescribed behavior of $R(t)$ is enforced and thus the following inequality is satisfied: 

<p align="center">
${_{t_{0}}^C}D_{t}^{\gamma}\Big(\phi^{-k_{3}}_{\sigma(t)}(t){H}(t)\Big)\leq -q_{1}\phi^{-k_{3}}_{\sigma(t)}(t)H(t)$ 
</p>

thereby enabling the prescribed-time stability proof in a practical way.
