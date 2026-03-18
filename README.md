# SpacedOut
Design an early warning system showing how orbital factors and space weather influence the satellite drag using a Machine Learning (ML)  model

## The Problem
Satellites in Low Earth Orbit (LEO) face a persistent threat: atmospheric drag
driven by space weather causes progressive orbital decay, thereby shortening satellite
lifetimes and creating costly operational risks.

## The Goal
Build an ML-powered early warning system that predicts satellite decay rates
using orbital parameters and geomagnetic activity data.

---

## Approach
Six years of Two-Line Element (TLE) data from [Space-Track](https://www.space-track.org)
were combined with geomagnetic and solar activity indices to model how space
weather impacts satellite lifetimes.


---

## Key Results

| Achievement | Detail |
|---|---|
|  Prediction Accuracy | 0.90–0.92 for select orbital groups |
|  Decay Trend Modeling | Semi-major axis trends tracked across multiple years |
|  Feature Importance | Solar flux and geomagnetic storms identified as top drivers |
|  Interactive Tool | Decay Rate Predictor — input satellite parameters, get risk output |

---

## Recommendations
- **Maneuver satellites proactively** to extend operational lifetimes
- **Increase space weather monitoring** across mission planning workflows
- **Develop time-series models** for higher-resolution future decay forecasting

---

## Impact
> Predictive modeling can protect satellite operators, scientists, and commercial
> users from costly orbital risks, while supporting the long-term sustainability
> of Low Earth Orbit.
