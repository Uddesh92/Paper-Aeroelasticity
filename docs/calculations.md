# Calculations — Paper Aeroelasticity Flutter Study

## 1\. Specimen Dimensions

Constant chord: c = 5 cm = 0.05 m

|AR|Span b (cm)|Span b (m)|
|-|-|-|
|1|5|0.05|
|2|10|0.10|
|3|15|0.15|
|4|20|0.20|
|5|25|0.25|
|6|27.5|0.275|

## 2\. Paper Material Properties (80gsm A4)

```
Elastic Modulus:    E ≈ 2–5 GPa  (assume 3 GPa = 3 × 10⁹ Pa)
Density:            ρ ≈ 800 kg/m³
Thickness:          t ≈ 0.1 mm = 0.0001 m
Mass per unit area: 80 g/m² = 0.08 kg/m²
```

## 3\. Second Moment of Area

For a rectangular cross-section (strip bending about width axis):

```
I = (c × t³) / 12
I = (0.05 × (0.0001)³) / 12
I = 4.17 × 10⁻¹⁵ m⁴
```

## 4\. Cantilever Natural Frequency (First Bending Mode)

Euler-Bernoulli formula:

```
f₁ = (1.875)² / (2π × L²) × √(EI / ρA)

Where:
  A = c × t = 0.05 × 0.0001 = 5 × 10⁻⁶ m²
  EI = 3×10⁹ × 4.17×10⁻¹⁵ = 1.25×10⁻⁵ N·m²
  ρA = 800 × 5×10⁻⁶ = 4×10⁻³ kg/m
```

Example for AR=5 (L = 0.25m):

```
f₁ = (3.516 / (2π × 0.0625)) × √(1.25×10⁻⁵ / 4×10⁻³)
f₁ = 8.94 × √(3.125×10⁻³)
f₁ = 8.94 × 0.0559
f₁ ≈ 0.5 Hz
```

This is very low — confirming that long strips are extremely flexible and will flutter at low wind speeds.

## 5\. Flutter Onset Ratio Calculation

```
FOR = Average Flutter Distance (cm) / Reference Distance (50 cm)
```

Example:

* AR = 4, average flutter distance across 3 trials = 22 cm
* FOR = 22 / 50 = 0.44

## 6\. Expected Trend

Based on flutter speed scaling (V\_flutter ∝ 1/b^1.5 approximately):

|AR|Expected Relative Flutter Speed|
|-|-|
|3|High (far from source)|
|5|Medium|
|8|Low (close to source)|

Exact values depend on your experimental airflow source and will be filled in after testing.

