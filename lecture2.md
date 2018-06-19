# Data8 Course - Lecture 2 Notes
## Reading: [Chapter 2](https://www.inferentialthinking.com/chapters/02/causality-and-experiments.html)

**Observational Study**: study in which scientists make conclusions based on data they **observe** but do not **generate**. Often, they contain three main elements:
- Individual
- Treatment (factor of interest)
- Outcome

Question: does the treatment **affect** the outcome?
**Association**: any **relation** between treatment and outcome.
**Causality**: association in which treatment **causes** the outcome.

In order to establish **causality** we need to be able to make a **comparison** between two groups:
- Treatment Group (receives the treatment)
- Control Group  (does not recieve the treatment)

In order to make that **comparison**, that these two groups must be **similar** in everything but the treatment received. If any factor other than the treatment is different between the two groups, the differences in the outcome could be a product of that factor, and not the treatment. These factors are called **confounding factors**.

One way to **avoid confounding factors** is determining which individuals will get or not get the treatment using **randomization**, keeping the groups similar. Experiments using these techniques are called  **Randomized Controlled Trials (RCT)**. In RCTs, in order to preserve the results, it is sometimes best to keep the individuals from knowing which group they're in. These are called **blind experiments**, and they rely on giving the control group **placebos**, which look like the treatment but have no effect.

Properly designed randomization techniques allow for chances to be accounted for mathematically, leaving two consequences:
- It's possible to **mathematically account** for the possible **differences** between the two groups.
- It's possible to make **precise mathematical statements** on **how different** those two groups are, which allow justifiable **conclusions** on the treatment's **effects**.
