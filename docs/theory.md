# Theory Paper Aeroelasticity Flutter Study

## 1\. What Is Flutter?

Flutter is a dynamic aeroelastic instability. It occurs when aerodynamic forces and structural vibration couple together at a critical wind speed, creating a self-sustaining and growing oscillation.

Below the flutter speed:

* Aerodynamic damping absorbs energy from structural vibration
* Oscillations die out

At the flutter speed:

* Net system damping = 0
* Oscillations are self-sustaining

Above the flutter speed:

* The system feeds energy into oscillations
* Amplitude grows until structural failure

## 2\. Aeroelastic Triangle

Flutter sits at the intersection of three disciplines:

```
         Aerodynamics
              /\\
             /  \\
            /    \\
    Elasticity — Inertia
```

* **Aerodynamics** provides the forcing
* **Elasticity** (structural stiffness) provides the restoring force
* **Inertia** (mass) governs the oscillation frequency

## 3\. Aspect Ratio

For a rectangular wing:

```
AR = Span / Chord = b / c
```

Higher AR → longer, narrower wing → lower structural stiffness → flutters at lower wind speed.

## 4\. Why AR Affects Flutter Speed

From Euler-Bernoulli beam theory, the bending stiffness of a cantilever scales as:

```
EI / L³
```

Where L is the span. As span increases (higher AR at constant chord), stiffness drops with the cube of span. This means the natural frequency drops, and the coupling with aerodynamic forces occurs at a lower wind speed.

## 5\. Flutter Onset Ratio (FOR)

Since airspeed is not directly measured in this experiment, we use a normalized metric:

```
FOR = Flutter Onset Distance / Reference Distance (50cm)
```

A lower FOR means flutter happened closer to the airflow source i.e., at a higher effective wind speed. A higher FOR means flutter happened farther away i.e., at a lower effective wind speed.

Expected trend: **As AR increases, FOR decreases.**

## 6\. Real-World Relevance

* De Havilland Comet (1950s): Early jet airliners required extensive flutter clearance testing
* F-16 prototype: Wing flutter encountered during early flight test program
* Tacoma Narrows Bridge (1940): Wind-induced flutter destroyed the structure
* Flutter is a primary certification requirement under FAA FAR Part 25 and EASA CS-25

Flutter must be shown not to occur below 1.2× the design dive speed for any certified aircraft.

