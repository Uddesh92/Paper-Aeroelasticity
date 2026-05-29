# Experimental Procedure — Paper Aeroelasticity Flutter Study

## Materials Required

* A4 paper, 70gsm (same ream throughout)
* 30cm ruler
* Pencil
* Scissors
* Binder clip (large)
* Airflow source (desk fan / USB fan / AC with redirector)
* Masking tape
* Notebook
* Smartphone with slow-motion video (120fps or higher)

\---

## Step 1 - Cut Specimens

Cut strips with constant chord = 5cm.

|Wing ID|AR|Span (cm)|
|-|-|-|
|W1|1|5|
|W2|2|10|
|W3|3|15|
|W4|4|20|
|W5|5|25|
|W6|5.5|27.5|

Cut 3 identical strips per AR (for 3 trials). Label each strip at the root end in pencil: W3-1, W3-2, W3-3 etc.

Mark a line 5mm from the root on every strip — this is your clamping depth mark.

\---

## Step 2 - Set Up Mount

Clamp the binder clip to the edge of a stable surface (table edge, upright book spine). Orient so the strip points **vertically upward** — this eliminates gravitational sag.

Grip exactly 5mm of the strip root inside the clip. The clamping depth mark you drew should sit exactly at the clip edge.

\---

## Step 3 - Set Up Measurement Track

Place your ruler flat on the surface. Mark distances from your airflow source outlet at: 50cm, 40cm, 30cm, 20cm, 10cm, 5cm using masking tape labels.

The airflow source should point **horizontally** at the strip face.

\---

## Step 4 - Run Tests

For each strip:

1. Mount the strip (5mm root in clip, strip pointing up)
2. Start airflow source at lowest/fixed setting
3. Begin at 50cm distance (strip tip to source outlet)
4. Slowly move source closer — approximately 1cm every 3 seconds
5. Watch for **self-sustaining rhythmic oscillation** (flutter)
6. When flutter begins: hold position, record the distance
7. Confirm by releasing strip — if it flutters again on its own, it is genuine flutter
8. Record distance in data table
9. Let strip rest 30 seconds before next trial
10. Repeat 3 trials per AR, use fresh replicate strips if any strip gets creased

\---

## Step 5 - Identify Flutter vs Non-Flutter

|What You See|What It Is|
|-|-|
|Strip deflects and stays deflected|Static bending — not flutter|
|Strip twitches once and stops|Damped vibration — not flutter|
|Strip oscillates rhythmically, keeps going|**Flutter — record this distance**|
|Strip oscillates, then dies out when source is held steady|Not flutter — move closer|

\---

## Step 6 - Calculate FOR

```
FOR = Average Flutter Distance (cm) / 50 cm
```

Fill in the data table in README.md.

\---

## Step 7 - Plot Results

Plot AR (x-axis) vs FOR (y-axis) in Google Sheets or on graph paper. Draw a smooth best-fit curve. Expected shape: downward sloping — higher AR = lower FOR.

\---

## Notes

* Run entire experiment in one session (avoids humidity-related paper property changes)
* Keep fan/source setting identical for every test
* Always measure from source outlet to free tip of strip
* Slow-motion video (240fps) makes flutter onset much easier to identify precisely

