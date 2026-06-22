# Kanon
A framework to evaluate behavioral stability in language models.



Current AI safety benchmarks are like periodic glucose tests. You go in, test, and it's done. It tries to tell you the general situation, but it is only a snapshot of a moment. Glucose monitors, on the other hand, provides a live evaluation of how well your insulin's effects are when encountering different levels of glucose during day-to-day eating. Kanon is the glucose monitor. Measuring model behaviors under pressure, and predicts the impacts those behaviors have on real-life operations. Unlike METR and SALAD-Bench, which measures a model's dangerous capabilities, Kanon measures model stability, which can be considered more useful in real-world deployments. This gives organizations real-time insight into how their deployed models behave under pressure and what that means for the people relying on them.

In response to this problem, we have devised three metrics, Constraint Compliance (CC), Social Alignment Sensitivity (SAS), and Epistemic Stability and Resistance (ESR). 

CC measures a model's adherence to its given, stated rules under pressure.

SAS measures a model's resistance to social pressure, such as authority pressure, conformity pressure, etc..

ESR measures a model's ability to not only detect false or assumed premises in a prompt, but to prevent itself from reasoning with the false/assumed premise.
