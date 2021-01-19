---
theme : "black"
slideNumber: "true"
transition: "slide"
---

<!-- .slide: style="text-align: left;" -->
## Macroeconomic Theory
### Francesco Franco - Nova SBE
#### T3 2021 

---

<!-- .slide: style="text-align: left;" -->
### Course content
- This course presents macroeconomic modeling at an intermediate level
-  3 mainstream models used in macroeconomics:
    - the neoclassical growth model: Ramsey-Cass-Koopmans
    - the overlapping generation model: Samuelson - Diamond
    - the new-Keynesian model: Fischer - Blanchard/Kiyotaki - Yun - Taylor - ...

---

<!-- .slide: style="text-align: left;" -->
### Course content
#### Mathematical methods
We learn the methods used to study the 3 models:
- Dynamic optimization/Optimal Control/DP
- Differential system of equations/Difference system of equations

---

<!-- .slide: style="text-align: left;" -->
### Course content
#### Mathematical methods
- Sometimes a model is more naturally cast in continuous time, sometimes in discrete time.
- The first two models are deterministic while stochastic in the third is kept at an elementary level.
- Everything is done analytically as opposed to a numerical macro course where the models are solved on the computer (will talk about one example) 

---

<!-- .slide: style="text-align: left;" -->
### Course content
#### Microeconomics channel and Macroeconomic questions
We learn the basic microeconomics channel at play in the three models, namely spending versus saving under
- Utilitarian behavior
- Perfect foresight / Rational Expectations

---

<!-- .slide: style="text-align: left;" -->
### Course content
#### Microeconomics channel and Macroeconomic questions
We learn the implications for benchmark questions on
- Government debt and fiscal policy in the long run
- Social security
- Fluctuations and macroeconomic stabilization policies (monetary and fiscal)

---

<!-- .slide: style="text-align: left;" -->
### Model 1 - Ramsey
#### Infinite horizon - continuous time
Sketch of the model: the social planner problem is the simplest version maximizes

$$ U(0)	=\int_{0}^{\infty}e^{-\rho t}u(c(t))dt $$

s.t.	

$$f(k(t))	=c(t)+\dot{k}(t)+nk(t)$$

$$k_{0}>0, c(t)\geq0,k(t)\geq0 $$

--

<!-- .slide: style="text-align: left;" -->
Objective: $$ U(0)	=\int_{0}^{\infty}e^{-\rho t}u(c(t))dt $$

--

<!-- .slide: style="text-align: left;" -->
Resources constraint:$$f(k(t))	=c(t)+\dot{k}(t)+nk(t)$$

--

<!-- .slide: style="text-align: left;" -->
Additional constraints:
$$k_{0}>0, c(t)\geq0,k(t)\geq0 $$
TVC

---

<!-- .slide: style="text-align: left;" -->
## Phase diagram

---

<!-- .slide: style="text-align: left;" -->
### Model 1 - Ramsey
- Economic aggregates dynamics are determined by decisions at the microeconomic level
- Centralized versus decentralized economy
- Real economy, nominal variables are decoupled
- How interest rates affect savings
- How does the choice between tax and debt financing affects capital accumulation
- Extension to small open economy and investment decisions

---

<!-- .slide: style="text-align: left;" -->
### Model 2 - OLG
#### Finite life - discrete time
Sketch of the model: time (discrete) represents the span of a generation (we will see 2 and 3 generations versions) and generations overlap. Population is $N_{t}$.

The problem of an agent that is born generation is
$$max\,u(c_{1t})+(1+\rho)^{-1}u(c_{2t+1})$$ subject to budget constraints.

--

<!-- .slide: style="text-align: left;" -->

Firm maximize profits: $$max\,F\left(K_{t},N_{t}\right)-w_{t}N_{t}-r_{t}K_{t}$$

with aggregate investment equals saving $$K_{t+1}-K_{t}=N_{t}s(w_{t},r_{t+1})-K_{t}$$

--

<!-- .slide: style="text-align: left;" -->
Objective households: $$max\,u(c_{1t})+(1+\rho)^{-1}u(c_{2t+1})$$ subject to budget constraints. 

---

<!-- .slide: style="text-align: left;" -->
### Model 2 - OLG
- Second basic model used in micro-based macroeconomics
- particularity: there are generations yet unborn whose preferences may not be registered in current market transactions
- life-cycle saving
- heterogeneity
- competitive equilibrium might not be Pareto optimal (over-accumulation of capital)

---

<!-- .slide: style="text-align: left;" -->
### Model 3 - NKM
#### Infinite horizon - discrete time
- Model that breaks the dichotomy between nominal and real side of the economy
- Nominal and real rigidities
- imperfect competition
- labor supply decisions
- Real short run effects of monetary policy and spending

---

<!-- .slide: style="text-align: left;" -->
### Model 3 - NKM
We will add to a discrete time version of a simplified Ramsey model ingredients that allow us ta meaningfully talk about:
- imperfect competition (Stiglitz-Dixit)

$$C=\left[\int_{0}^{1}C(i)^{\left(\eta-1\right)/\eta}di\right]^{\eta/(\eta-1)},\eta>1$$ 

- Nominal rigidities (Fisher, Taylor, Calvo, Rothemberg): price cannot adjust instantaneously, time or state dependent
- Dynamics are caused by shocks (think of the technology, government or interest rate shock

---

<!-- .slide: style="text-align: left;" -->
### Model 3 - NKM
The core model NKM is composed of three equations (after having solved for optimal decisions)

<span>
\[\begin{aligned}
\widetilde{y}_{t} &amp; =E_{t}\widetilde{y}_{t+1}-\sigma\left[i_{t}-E_{t}\left\{ \pi_{t+1}\right\} \right]+u_{t}^{IS} \\
\pi_{t} &amp;=\beta E_{t}\pi_{t+1}+\lambda\widetilde{y}_{t}+u_{t}^{PC} \\
i_{t} &amp;=MR(\pi_{t},\widetilde{y}_{t},...)+u_{t}^{MP}
\end{aligned} \]

<span>

- IS: where $\tilde{y}$ is the output gap: we introduce a notion of resources not fully allocated
- NKPC: where $\pi$ is inflation -> nominal side matters
- Monetary policy rule: we can analyze the role of monetary policy

---

<!-- .slide: style="text-align: left;" -->
### Conclusions
#### In this course
- we will have a lot of fun
- I will base the course on notes (presented in class)
- The final is worth 50% and the homework 50%. Participation in class can add a 10% bonus.
- There are 3 Problem Sets, each counting 1/3 of the 50%.
- Work is individual (?)
