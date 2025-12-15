# moar-boosters

A project for PHSCS 230 to find the most fuel-effective ascent trajectory to Kerbin orbit with the simplest rocket that we can build in Kerbal Space Program (KSP). The simplest rocket is the one with the fewest parts.

## Research

### KSP mods:

Need:
- easy way to export data
- use Python to calculate flight trajectories

#### Python:
[**kRPC**](https://spacedock.info/mod/69/kRPC)
- successfully used mod to run a basic program: [ksp_code.py](./ksp_code.py)

#### Export Data:
[**KSP Data Export**](https://spacedock.info/mod/2711)
- successfully used mod to collect thrust data

## Presentation Notes

### Topic Description

- finding the simplest and fastest to 10,000 m altitude?
- we calculated the rocket trajectories, then collected data to see if they matched

### Expected Results

- we want our predicted max height to match the actual max height in game
- we want the same for max velocity
- we know that drag will do something, but hoped our results would be relatively accurate nonetheless
- we will include the actual results in the presentation

### Methods Used

- used formulas in Mathematica that were sourced from a definitive book on rocket science, with the calculus pre-done
- used a mod to pull in-game data while we ran the simulation
- used the thrust and pressure curves to decide what numbers to use for ISP and thrust based on the altitudes traversed

### Found Results


### Discrepancies Between Expected and Actual