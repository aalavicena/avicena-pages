---
title: "U.S. Policy Rates"
aliases:
    - /contact.html
hidemeta: true
description: "How is the policy rate now?"
---

#### Taylor-Type Rule
We use the Taylor-type rule to evaluate the current policy rate in the United States. In specific, we follow Bullard (2023) and consider the rules of the following form:
$$R_t = \max\left[R^* + \pi^* + \phi_{\pi}(pi_t-pi^*) + \min(ygap_t,0),0\right],$$
+ $R_t$ is the recommended policy rate
+ $R^*$ is the real interest rate
+ $\pi^* = 2%$ is the inflation target
+ $\pi_t$ is the inflation index
+ $\phi_{\pi}$ describes the reaction of the policy maker to deviations of inflation from target
+ $ygap_t$ is the output gap

#### Inflation
![](/inflation.png)
#### Output Gap
We use Okun's law to compute the output gap.
![](/Output_gap.png)

#### The Sufficiently Restrictive Zone
![](/Policy_rate_new.png)

##### References
+ Bullard, J. (2023). Is Monetary Policy Sufficiently Restrictive?. The Regional Economist.
