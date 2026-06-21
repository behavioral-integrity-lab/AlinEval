# Kanon
A framework to evaluate behavioral stability in language models.



Current AI safety benchmarks are like periodic glucose tests. You go in, test, and it's done. It tries to tell you the general situation, but it is only a snapshot of a moment. Glucose monitors, on the other hand, provides a live evaluation of how well your insulin's effects are when encountering different levels of glucose during day-to-day eating. Kanon is the glucose monitor. Measuring model behaviors under pressure, and predicts the impacts those behaviors have on real-life operations. Unlike benchmarks which tells you surface level sycophancy scores, Kanon applies a wide variety of tests and measures a model's response to each. It's like trying a bunch of foods to see which ones raises your blood sugar the most, and what impact that will have on your diet. 

In response to this problem, we have devised three metrics, Constraint Compliance (CC), Social Alignment Sensitivity (SAS), and Epistemic Stability and Resistance (ESR). Details in docs/glossary.md.

