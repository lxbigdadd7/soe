# soe
Open code for paper Sequence of Expert: Boosting Imitation Planners for Autonomous Driving from A Novel Dimension

# Release time

The code and models to reproduce results will be published as long as the paper is published.

But I'm pretty sure you can reproduce soe and try it with your IL planners. It's very easy as:

```
if index % interval == 0:
  model_o.infer()
else:
  model_star.infer()
```
