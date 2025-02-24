---
title: "US Policy Rates"
hidemeta: true
description: "How is the US policy rate now?"
---

We use the Taylor-type rules to evaluate the current U.S. policy rates. In specific, I follow Bullard (2023) and consider the following form of the Taylor rule:
$$R_t = \max\left[R^* + \pi^* + \phi_{\pi}(pi_t-pi^*) + \min(ygap_t,0),0\right],$$
+ $R_t$ is the recommended policy rate
+ $R^*$ is the real interest rate
+ $\pi^* = 2\%$ is the inflation target
+ $\pi_t$ is the inflation index
+ $\phi_{\pi}$ describes the reaction of the policy maker to deviations of inflation from target
+ $ygap_t$ is the output gap
   
##### Inflation

##### Output Gap
We use Okun's law to compute the output gap.
![](/Output_gap.png)

##### The Sufficiently Restrictive Zone

##### References
+ [1] Bullard, J. (2023). Is Monetary Policy Sufficiently Restrictive?. The Regional Economist.
