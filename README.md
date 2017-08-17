# Stochastic-Optimization-Library

This repository contains the draft of a working paper on the creation of a common test-set for stochastic optimization problems.

This project will only work if the community collectively agrees on the underlying format these problems should be expressed in.

Therefore, we actively encourage any feedback and (especially) criticisms. To discuss, please open an issue, or send me an
email at odow003@aucklanduni.ac.nz.

Some critical decisions that need to be made are
- [ ] Is a risk measure a property of the model or the solution method? In other words, are we finding the best policy to a
risk-averse model, or a risk-averse policy to a model with no concept of risk.
- [ ] Is a risk measure present in every stage (i.e. a nested risk measure approach), or do we allow end-of-horizon risk
measures? If so, how does one express where the risk measures lie.
- [ ] What problems **cannot** be expressed in the format as it currently stands?

Oscar

