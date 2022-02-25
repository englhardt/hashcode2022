# Hashcode 2022

Our solution for the coding challenge [Hashcode 2022](https://codingcompetitions.withgoogle.com/hashcode).<br>
Team name: `Road Blizzards`

### Competition results
Place 1108 out of 10177 teams.

```
A              30
B         412,603
C          24,664
D          75,904
E       1,637,258
F         249,868
-----------------
Total:  2,400,327
```

### Approach

Implementation of reader, writer and scoring function.

* *Greedy*: schedule projects with contributors that have required skill level (no learning, no mentoring)
* *Greedy with Reordering*: greedy + reordering of projects and contributors at the beginning + learning + mentoring
* *Simulation*: simulate time and schedule possible projects (NOTE: way too slow to compute)

#### Post-competition results
Available in the [notebook](https://github.com/englhardt/hashcode2022/blob/main/hashcode2022.ipynb).
```
A              30
B         469,442
C          24,664
D          63,576
E       1,637,258
F         247,107
-----------------
Total:  2,442,077
```
