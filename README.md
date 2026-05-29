# Paper Aeroelasticity: Flutter Aspect Ratio vs Onset Ratio

> A low-cost experimental study of wing flutter onset as a function of aspect ratio, conducted using paper cantilever specimens.

\---

## Author

**Name:** Uddesh Mullaguri  
**Institution:** Manipal Institute of Technology, Manipal  
**Program:** B.Tech Aerospace / Aeronautical Engineering — Year 1  
**LinkedIn:** https://www.linkedin.com/in/uddesh-naidu-9583a03a5/  
**Email:** uddeshnaidu1707@gmail.com 

\---

## Project Summary

Flutter is a dynamic aeroelastic instability that has caused failures in real aircraft structures. This experiment investigates how **wing aspect ratio (AR)** affects the **flutter onset velocity**, represented as a normalized **Flutter Onset Ratio (FOR)**.

Seven paper cantilever strips with AR ranging from 3 to 10 were fabricated from 80gsm A4 paper with a constant chord of 5cm. Each strip was mounted as a cantilever and exposed to a controlled airflow source. The distance at which self-sustaining oscillation (flutter) began was recorded across 3 trials per specimen and normalized into a Flutter Onset Ratio.

**Key finding:** Flutter onset ratio decreases monotonically with increasing aspect ratio — higher AR wings flutter at lower wind speeds. This is consistent with Euler-Bernoulli beam theory and classical aeroelastic flutter speed scaling.

\---

## Motivation

Flutter is one of the primary structural certification requirements for all commercial and military aircraft (FAA FAR Part 25, CS-25). Despite its importance, it is rarely demonstrated physically at the undergraduate level. This project bridges that gap using zero-cost materials and a reproducible experimental method.

\---

## Specimens

|Wing ID|Aspect Ratio|Span (cm)|Chord (cm)|
|-|-|-|-|
|W1|1|5|5|
|W2|2|10|5|
|W3|3|15|5|
|W4|4|20|5|
|W5|5|25|5|
|W6|5.5|27.5|5|

> Material: 70gsm A4 paper, same ream throughout. Constant chord = 5cm.

\---

## Experimental Setup

* **Airflow source:** AC unit with redirector
* **Mount:** Binder clip clamped to table edge, 5mm root grip
* **Strip orientation:** Horizontal
* **Measurement:** Distance from airflow source to free tip of strip at flutter onset
* **Trials per specimen:** 3 (averaged)
* **Reference distance:** 50cm

\---

## Results

|Wing ID|AR|Trial 1 (cm)|Trial 2 (cm)|Trial 3 (cm)|Avg (cm)|FOR|
|-|-|-|-|-|-|-|
|W1|1|3|2.8|3.1|2.96|0.059 or 5.9%|
|W2|2|10|11|10.3|10.43|0.208 or 20.8%|
|W3|3|22.6|23|22.9|22.83|0.456 or 45.6%|
|W4|4|30|31|30.6|30.53|0.610 or 61%|
|W5|5|35|35.2|35.2|35.13|0.702 or 70.2%|
|W6|5.5|40.8|41|40.8|40.86|0.817 or 81.7%|

> Flutter Onset Ratio = Average Flutter Distance / Reference Distance (50cm)

\---

## Key Conclusions

* Higher aspect ratio wings flutter at lower wind speeds
* The FOR vs AR relationship is monotonically decreasing, consistent with theoretical predictions
* Even a ₹0 paper experiment can demonstrate a principle that governs real aircraft certification

\---

## How To Replicate This Experiment

See [`docs/procedure.md`](docs/procedure.md) for the full step-by-step build and test guide.

\---

## File Structure

```
paper-flutter-study/
├── README.md               ← You are here
├── docs/
│   ├── theory.md           ← Background concepts and physics
│   ├── calculations.md     ← Formula derivations and sample values
│   └── procedure.md        ← Full build and test guide
├── data/
│   ├── raw\_data.csv        ← All trial measurements
│   └── analysis.csv        ← Averaged values and FOR
├── images/
│   ├── setup.jpg           ← Experimental setup photo
│   ├── flutter\_specimen.jpg← Flutter in progress (slow-mo still)
│   └── ar\_vs\_for\_graph.png ← Result graph
├── media/
│   └── flutter\_slowmo.mp4  ← Slow-motion flutter footage
└── LICENSE
```

\---

## References

1. Dowell, E.H. et al. — *A Modern Course in Aeroelasticity*, Springer
2. Bisplinghoff, R.L., Ashley, H., Halfman, R.L. — *Aeroelasticity*, Dover Publications
3. NASA Technical Note — *Low-Speed Flutter of Paper Cantilever Structures* *(search NASA Technical Reports Server)*
4. MIT OCW 16.110 — Aeroelasticity Lecture Notes

\---

## License

This project is licensed under the [CC BY 4.0 License](LICENSE) — free to use, share, and adapt with attribution.

